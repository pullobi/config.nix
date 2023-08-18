# These are my NixOS Configurations. 
### You can find my configuration at [here.](https://github.com/pullobi/config.nix/blob/main/configuration.nix)
----
## Screenshots
![Screenshot_2023-08-18-18-21-21_23363](https://github.com/pullobi/config.nix/assets/52003948/36c9b907-8ec4-4fb2-80e2-9677db658fe9)
![Screenshot_2023-08-18-18-23-21_2381](https://github.com/pullobi/config.nix/assets/52003948/33058bad-9425-4849-bc06-b5a395109cf0)
----
# Installation

Install i3,i3-gaps,thunar,nvim,rofi,polybar and gcc with nix-env:
``` nix-env -i i3 i3-gaps thunar nvim rofi polybar gcc13 git feh```

Copy the configuration:
``` git clone https://github.com/pullobi/config.nix/ && cd config.nix && cp -r * ~/.config```

(optional) Restart your computer to set wallpaper or run:
 ``` feh --bg-fill ~/.config/i3/walls/*```

#Installation for Pop!_OS or any Debian based systems:
### Update and Upgrade your System:
``` sudo apt-get update -y && sudo apt-get upgrade -y```
### Reboot before making any changes.
`reboot`
### Install required packages:
```sudo apt-get install i3-i3-gaps feh polybar rofi nvim thunar```
### Clone the repo, cd into it and copy the configuration
`git clone https://github.com/pullobi/config.nix/ && cd config.nix && cp -r * ~/.config `
### Logout from your Desktop Environment, and log in to i3.
## Notes
This configuration may not work on your system, Copy my changes (marked with "==") in the configuration.nix file, and add them.
I don't know what will happen if you copy the file to your configuration.nix file. So I dont recommend doing it, and i am not responsable for any damages.

