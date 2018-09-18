FROM ubuntu:18.04


RUN set -ex && \
    apt update; \
    apt install -y curl gcc vim git; \
    curl https://sh.rustup.rs -o rust-init; \
    chmod +x rust-init; \
    ./rust-init -y; \
    rm rust-init; \
    echo 'PATH="$HOME/.cargo/bin:$PATH"' > $HOME/.bashrc
