---
layout: page
title: dotfiles
description: My config files
img: assets/img/dotfiles.jpg
importance: 2
category: I actually use
giscus_comments: true
---

## Using [stow](https://www.gnu.org/software/stow/)

1. Clone this repo to `$HOME`.
1. Each folder contains the things you want to link to. To link config for nvim: `stow nvim`.

By `stow`ing once, you'll see changes in `dotfiles` automatically reflected in `~/.config` (where apps actually read from).
