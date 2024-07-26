# Mac Mini Home Server

The repository contains the configuration files for a lightweight NixOS server
with no graphical environment, for an early 2010s Mac Mini. It contains the necessary non-free drivers
for WiFi support and fan control. The OpenSSH daemon starts automatically and it has server necessities like
docker.

Currently, it's pinned to NixOS release 24.05 "Uakari".

The default interactive shell is `fish` and `nvim` with no configuration files is the default editor.
