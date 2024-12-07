FROM nixos/nix:2.25.3

ENV NIXPKGS_ALLOW_UNFREE=1
# enable nix-command and flakes
RUN echo "experimental-features = nix-command flakes" >> /etc/nix/nix.conf
