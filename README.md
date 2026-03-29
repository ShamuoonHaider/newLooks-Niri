# NewLooks Niri Setup (From Scratch)

This folder is my starting point for a custom **Niri + Rofi** look.
I will build and tweak the setup step by step, using the `newLooks` style.

## Goal

- Start with a clean setup
- Apply my own theme/look (`newLooks`)
- Keep everything simple and easy to edit later

## Folder Contents

- `newLooks.rasi` → Rofi theme file
- `README.md` → setup notes and commands

## Prerequisites

Make sure these are installed on your system:

- `niri`
- `rofi`
- A Nerd Font or any font you like
- `waybar` (optional, if you use a panel)
- `mako` or another notification daemon (optional)

## Basic Setup Flow

1. Install Niri and Rofi
2. Create/adjust your Niri config
3. Point Rofi to `newLooks.rasi`
4. Add keybinds for launcher and common actions
5. Restart/reload and keep iterating

## Use This Rofi Theme

Test the theme directly:

```bash
rofi -show drun -theme ~/.config/rofi/newLooks.rasi
```

If you want it as default, set your launcher command in Niri to:

```bash
rofi -show drun -theme ~/.config/rofi/newLooks.rasi
```

## Suggested Niri Keybind Idea

In your Niri config, bind a key to run Rofi (example idea):

- `Super + D` → open app launcher

Use your own preferred syntax based on your current Niri config format.

## Customization Checklist

- [ ] Choose font + size
- [ ] Tune window spacing/gaps
- [ ] Set monitor layout
- [ ] Add/adjust launcher keybinds
- [ ] Match Rofi colors with overall desktop theme
- [ ] Add power menu / clipboard / screenshot shortcuts

## Theme Tweaks (Rofi)

Edit `newLooks.rasi` to customize:

- Colors (background, foreground, accent)
- Border radius / window padding
- Font family and size
- Entry spacing and selection highlight

## Iteration Workflow

After each change:

1. Save config/theme
2. Relaunch Rofi or reload session
3. Note what you like/dislike
4. Keep small edits until it feels right

## Notes

This README is intentionally minimal and built for gradual customization.
I will keep updating it as my Niri setup evolves.
