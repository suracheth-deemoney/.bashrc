# AGENTS.md

Guidelines for AI agents working in this repository.

> **You must be working inside this project** for all edits and commands.

## Purpose

This repo manages a single `.bashrc` file. `$HOME/.bashrc` is a symlink pointing to `.bashrc` in this repo.

## Key facts

- The only config file is `.bashrc` at the repo root.
- `$HOME/.bashrc` symlinks to `.bashrc` in this repo.
- Do not break the symlink (e.g. by moving or renaming `.bashrc`).

## Making changes

- Edit `.bashrc` directly.
- Test changes by running `bash --norc` and sourcing the file, or opening a new shell.
- Keep changes focused: one logical change per commit.
- Do not add secrets, tokens, or machine-specific paths that won't generalize.
