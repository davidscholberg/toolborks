# Creates a development image with chicken scheme installed.

# Base image off of our local neovim image.
FROM localhost/neovim

# Install chicken scheme and extra deps.
RUN sudo dnf install -y chicken openssl-devel redhat-rpm-config zlib-devel
