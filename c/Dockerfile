FROM ubuntu:18.04
RUN set -eux && \
    apt update; \
    apt install -y gcc make gdb vim git; \
    apt install -y language-pack-ja-base language-pack-ja; \
    echo export LANG=ja_JP.UTF-8 >> $HOME/.bashrc
