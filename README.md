# i3wm/polybar/rofi/picom/kitty configuration of amiriox

## Included

- **i3wm** In `i3/config` file. Basic keybindings, settings (actually i forgot what i've done)
- **polybar** A awesome polybar ui modified from [gxt-kt/dotfiles](https://github.com/gxt-kt/dotfiles/tree/master/polybar/.config/polybar), changed some modules, adapted for 1920*1080
- **picom** Mixer of i3wm, set corner radius, opacity, detail animation
- **rofi** Applications and commands runner. `drun`, `windowcd` were useful
- **kitty** terminal simulator. opacity, color theme
- **others** In `br.c` file. A direct way to change the brightness, more universal.

## What You Should Change

- **i3wm** It includes `fcitx5`(input method) autostart, `feh`(wallpaper) autostart,
            `polybar`, `kitty`, `rofi`, `flameshot`, `ranger`, `br`(see br.c)
- **polybar**

- **br.c** See comments in `br.c`. Just compile it, chmod, copy it to /usr/local/bin, etc.

Damn it, I'm too lazy to write, please look at the config file yourself and add the packages or fonts you need to install.

To synchronous/install a package from archlinux/aur, use:
```
$ sudo pacman -S {package_name}
$ yay {package_name}
```
