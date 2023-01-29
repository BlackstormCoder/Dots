<div align="center">
    <h1>♠Nicohlas Samuel's Configuration: ♠</h1>
    <h3>The git repository with all my config files.</h3>
</div>

<div align="center">

![](https://img.shields.io/github/stars/phant80m/dots?style=for-the-badge&logo=starship&color=8bd5ca&logoColor=D9E0EE&labelColor=302D41)
[![](https://img.shields.io/github/repo-size/phant80m/dots?color=%23DDB6F2&label=SIZE&logo=codesandbox&style=for-the-badge&logoColor=D9E0EE&labelColor=302D41)](https://github.com/phant80m/dots)
<a href="https://github.com/phant80m/dots/blob/main/LICENSE">
<img alt="License" src="https://img.shields.io/github/license/phant80m/dots?style=for-the-badge&logo=starship&color=ee999f&logoColor=D9E0EE&labelColor=302D41" />
</a>
<a href="https://github.com/phant80m/dots/issues">
<img alt="Issues" src="https://img.shields.io/github/issues/phant80m/dots?style=for-the-badge&logo=bilibili&color=F5E0DC&logoColor=D9E0EE&labelColor=302D41" />
</a>
</div>
<details><summary>Preview</summary><blockquote>
<h1> Preview </h1>

![](https://raw.githubusercontent.com/phant80m/dots/main/3.png)
![](https://raw.githubusercontent.com/phant80m/dots/main/2.png)
![](https://raw.githubusercontent.com/phant80m/dots/main/1.png)
</div>
</blockquote></details>

⚠ This specific configuration is designed to be used with ArchLinux ⚠
> Using on other distributions may come with some unwated errors

<details><summary>1: Download the dependecies required for this setup: </summary><blockquote>

- firstly download the latest Hyprland from the AUR, refer to the [wiki](https://wiki.hyprland.org/Getting-Started/Installation/) to get started:
```zsh
paru -S hyprland-git
```
- Or use any other aur helper, for example YAY:
```zsh
yay -S hyprland-git
```
-- setup minimal configuration:

  - Install Rofi, SwayBG, Kitty, waybar-hyprland, Grim, Slurp, Swappy, Nvim, Pavucontrol:
  
  ```
  paru -S rofi swaybg kitty waybar-hyprland grim slurp swappy nvim pavucontrol
  ``` 
  - Install fonts:
  [fira code nerd](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/FiraCode.zip) and
  [jetbrain mono nerd](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/JetBrainsMono.zip)
  place font into `~/.local/share/fonts/` if fonts directory does not exist create it.
  then run:
  ```zsh
  fc-cache -fv
  ```
  this will sync all installed fonts.
  fonts should install.
<details><summary>2: Installing the configuration:</summary><blockquote>

- Copy all of the configuration files to /home/<<username>username>/.config/:


```zsh 
cp -r dots/.config/* ~/.config/
```
- copy wallpaper into required directory:
```zsh
cp dots/wallpaper/* ~/Pictures/
```
- All keybind can be found inside the hyprland config:
<details><summary>3: final step:</summary><blockquote>
- Manually log out using `SUPER + M` and relog into your hyprland

</blockquote></details>
</blockquote></details>
</blockquote></details>

<details><summary>3: final step:</summary><blockquote>
<div align="center">

<h3> Enjoy the config, dont forget to report issues with my config if any appear! </h3>

![](https://raw.githubusercontent.com/phant80m/dots/main/3.png)