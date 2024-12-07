FROM nixos/nix:2.25.3
RUN echo "nixpkgs.config.allowUnfree = true" >> /etc/nix/nix.conf
# enable nix-command and flakes
RUN echo "experimental-features = nix-command flakes" >> /etc/nix/nix.conf
