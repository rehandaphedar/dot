# dot

These are my dotfiles. They are based on Arch Linux, Emacs and Wayland (Hyprland).

# Installation

These are mainly for my personal use and thus do not have great documentation. However, the general installation process is as follows:

- Install a minimal Arch Linux profile through the `archinstall` script. Keep these options in mind:
  - The bootloader is GRUB.
  - The audio server is Pipewire.
  - The network configuration is NetworkManager.
  - The `multilib` optional repository is enabled.
- Follow `Install.org` step by step (Some steps may fail on the first try as there may be some circular dependencies.).

Make sure to read all the files beforehand, as there are some configurations specific to my system (Such as password locations in `pass`, expected directory structure, expected GPG and SSH keys present, SMTP accounts, etc.).

