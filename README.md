# bashrc-config

A git-managed `.bashrc` configuration file.

## Setup

Clone the repo and create a symlink from `~/.bashrc` to the repo's `.bashrc`:

Run the following commands from this project directory:

```bash
rm ~/.bashrc
ln -s $PWD/.bashrc ~/.bashrc
```

## Usage

Edit `.bashrc` in this repo directly. Changes are version-controlled and take effect in new shell sessions (or run `source ~/.bashrc` to apply immediately).

## Files

- `.bashrc` — main bash configuration file
