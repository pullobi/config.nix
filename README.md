# These are my NixOS Configurations. 
### You can find my configuration at [here.](https://github.com/pullobi/config.nix/blob/main/configuration.nix)
----
## Screenshots
![Screenshot_2023-08-18-18-21-21_23363](https://github.com/pullobi/config.nix/assets/52003948/36c9b907-8ec4-4fb2-80e2-9677db658fe9)
![Screenshot_2023-08-18-18-23-21_2381](https://github.com/pullobi/config.nix/assets/52003948/33058bad-9425-4849-bc06-b5a395109cf0)
----
# Installation

Install i3,i3-gaps,thunar,nvim,rofi,polybar and gcc with nix-env:
``` nix-env -i i3 i3-gaps thunar nvim rofi polybar gcc13 git```

Copy the configuration:
``` git clone https://github.com/pullobi/config.nix/ && cd config.nix && cp -r * ~/.config```

(optional) Restart your computer to set wallpaper or run:
 ``` feh --bg-fill ~/.config/i3/walls/*```

