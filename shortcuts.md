    Mod+B hotkey-overlay-title="Open a browser" { spawn "google-chrome-stable"; }

    Mod+C hotkey-overlay-title="Open VS Code" { spawn "code"; }

    Mod+Space { spawn "bash" "-c" "rofi -show drun -show-icons -display-drun $'\\uf002' -theme /home/shamuoon/.config/rofi/newLooks.rasi"; }

    Mod+D hotkey-overlay-title="Open filemanager" { spawn "nautilus"; }

    Mod+Escape { spawn "qs" "ipc" "call" "sessionMenu.open"; }

    Mod+N hotkey-overlay-title="Open neovim" { spawn "alacritty" "-e" "nvim"; }

    Mod+A hotkey-overlay-title="Open Claude" { spawn "google-chrome-stable" "--app=https://claude.ai"; }

    Mod+S hotkey-overlay-title="Open Spotify" { spawn "spotify"; }

    Mod+H hotkey-overlay-title="Open helix" { spawn "alacritty" "-e" "helix"; }

    Mod+Z hotkey-overlay-title="Open zed" { spawn "zeditor"; }

    Mod+Return hotkey-overlay-title="Open a Terminal: alacritty" { spawn "alacritty"; }

    Mod+Alt+L hotkey-overlay-title="Lock the Screen: hyprlock" { spawn "hyprlock"; }
