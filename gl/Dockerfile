FROM ubuntu:18.04
RUN set -eux && \
    apt update; \
    apt install -y gcc g++ make gdb vim git x11-apps; \
    apt install -y language-pack-ja-base language-pack-ja; \
    echo export LANG=ja_JP.UTF-8 >> $HOME/.bashrc; \
    apt install -y freeglut3 freeglut3-dev
    
