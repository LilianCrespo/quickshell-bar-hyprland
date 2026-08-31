# quickshell-bar-hyprland

A lightweight Quickshell status bar for Hyprland featuring an interactive, physics-based vinyl player synced with Spotify.

---

## Features

- **Realistic tonearm movement:** The needle tracks and progresses smoothly across the record, synchronized with the current Spotify track's playback position.
- **Inertia physics:** Smooth acceleration when starting a track and natural deceleration when paused.
- **Interactive playback:** Click anywhere on the player to toggle play/pause.
- **Lightweight resource usage:**
  - **RAM:** ~250 MB (entire bar included)
  - **CPU:** ~0.8%

---

## Environment

- **OS:** Arch Linux
- **Window Manager:** Hyprland
- **Framework:** Quickshell
- **Player:** Spotify (MPRIS)

---

## Prerequisites

Ensure you have the following packages installed:

- `quickshell`
- `playerctl`

# Example on Arch Linux
sudo pacman -S quickshell playerctl

Make sure Spotify is running and exposing standard MPRIS controls.

## License

This project is dedicated to the public domain under The Unlicense. You are free to copy, modify, distribute, or use this code for any purpose, with or without attribution.

I chose this license because I absolutely don't feel legitimate using a restrictive license for something 99.99% made with AI.
