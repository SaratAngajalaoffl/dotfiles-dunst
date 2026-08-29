# dotfiles-dunst

Config for [dunst](https://dunst-project.org) (notification daemon), theme-integrated via the `theme` submodule.

Part of the [dotfiles-arch](https://github.com/SaratAngajalaoffl/dotfiles-arch) multi-repo dotfiles system.

## Layout

- `config` → `~/.config/dunst` (see `.links`)
- `config/dunstrc` is gitignored — it's a symlink to the active theme's `dunstrc`, not tracked content (see the `theme` submodule)

## Setup

Not used standalone — applied by the parent repo's `install.sh`, which reads `.links` and symlinks `config` into place.
