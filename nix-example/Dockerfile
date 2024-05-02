FROM nixos/nix
RUN nix-env -iA nixpkgs.cowsay nixpkgs.fortune nixpkgs.lolcat
ENTRYPOINT fortune | cowsay | lolcat
