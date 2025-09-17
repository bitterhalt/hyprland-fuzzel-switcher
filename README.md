# hyprland-fuzzel-switcher

A simple bash script to use fuzzel to quickly switch to a specific window in hyprland

Install Requirements:

1. bash
2. jq
3. fuzzel
4. hyprland

How to use:

1. Download niri_fuzzel_switcher, make it executable, and put it somewhere in your $PATH
2. Add a keybinding to the binds section in ~/.config/hyprland/hyprland.conf (e.g. `bind = SUPER, TAB, exec, hyprland-fuzzel-switcher`)
