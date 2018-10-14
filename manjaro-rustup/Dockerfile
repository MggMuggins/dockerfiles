FROM jonathonf/manjaro:latest

RUN pacman-mirrors -c all && \
    pacman -Syuu --noconfirm --noprogressbar base-devel rustup && \
    pacman -Scc --noconfirm --noprogressbar && \
    rm -fr /var/cache/pacman/pkg/* && \
    rm -f /var/lib/pacman/sync/*
