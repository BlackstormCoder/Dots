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

![](https://raw.githubusercontent.com/phant80m/dots/main/3.png)

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
<details><summary>2: Installing the configuration:</summary><blockquote>

- Copy all of the configuration files to /home/<username>/.config/:

```zsh 
cp -r dots/.config/* ~/.config/
```