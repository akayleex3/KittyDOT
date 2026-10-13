# KittyDOT

KittyDOT is my personal Arch/EndeavourOS desktop build for Hyprland and Noctalia.
This is mostly for @IsJenkz on Twitch since I wanted hin to have my dotfiles, It is recommended to use EndeavourOS, I don't know how it works on Arch because I never tested it, but I don't see a reason it shouldn't work.

## What makes it mine

- Noctalia-first desktop flow
- A first-login setup assistant with colored onboarding
- One-click `Ari desktop` preset for the browser and common apps
- A live, searchable Hyprland cheatsheet
- Default-browser, mirrors, and GPU guidance built into the flow

## Quick Start

On a fresh Arch or EndeavourOS install:

```bash
git clone https://github.com/akayleex3/KittyDOT.git
cd KittyDOT
./setup install
```

The installer brings in the Hyprland stack for Arch-based systems, then copies the rice and first-login assistant on top.

## How To Install

1. Install Arch Linux or EndeavourOS.
2. Open a terminal after the base system is ready.
3. Clone this repo and run `./setup install`.
4. Log into Hyprland for the first time.
5. Use the setup assistant to finish the desktop or hit `Install Ari desktop` for the curated app preset.

## First Login

- `Super + /` opens the cheatsheet
- `Super + Enter` opens a terminal
- `Super + .` opens the launcher
- `Super + W` opens the default browser
- `Super + N` opens Noctalia control center

## Presets

The `Install Ari desktop` button installs a curated bundle:

- Brave Origin
- Steam
- Discord
- VLC
- LibreOffice
- GIMP
- OBS Studio
- Thunderbird
- Signal
- Prism Launcher
- Flatpak support

## Project Shape

This repository was built from my own desktop setup and reshaped into a cleaner, beginner-friendly install.
Upstream Hyprland-dotfiles influence is part of the history, but the current goal is different: a personal rice that is easy to install and easy to live with.
