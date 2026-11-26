<p align="justify"> <b> ## I'm maintaining and updating this theme to ensure compatibility with the latest versions of the Cinnamon and XFCE desktop environments. You may occasionally notice improvements, fixes, and refinements. Thank you for your support! </b> </p>

<h1 align="center"> WhiteSur GTK Theme for Cinnamon and XFCE </h1>
<h1 align="center"> (Nord Color Scheme) </h1>

<p align="center"> <img src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/macbook.png"/> </p>

<br>
<p align="center"> <b> A macOS Big Sur-inspired theme for your GTK apps </b> </p>
<br>

## Features of the WhiteSur GTK theme:

The theme has been specifically adapted for Cinnamon and XFCE desktop environments. It includes the Nord color scheme, support for both left- and right-aligned Nemo and Nautilus title buttons, optimized sizing for laptop displays, and a Nautilus-style "Glassy" appearance.

## Installation:

Just copy the Whitesur theme to the Cinnamon themes directory: /usr/share/themes. If you copy it to ~/.themes, some applications that require superuser password will be displayed incorrectly, and the styles of this theme will not be applied to them.

## Fix for libadwaita

Since GNOME 43, more apps use libadwaita, which does not support custom themes. This means themes cannot be changed through GNOME Tweaks or dconf-editor.

The only workaround is to overwrite the GTK 4 configuration files with theme files. This forces all GTK 4 apps to use one theme and prevents switching themes or dark mode. To change the theme, you must replace the GTK 4 files again.

Unpack gtk-4.0 (Light Nord).tar.gz or gtk-4.0 (Dark Nord).tar.gz and copy the files to $HOME/.config/gtk-4.0.

### WhiteSur Wallpapers
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-wallpapers">
  <img class="image" src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/wallpaper.gif"/>
</a> </p>
<br>
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-wallpapers">
  <img src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/download-button.svg"/>
</a> </p>
<br>

## Features of the WhiteSur Icon theme:

Additional icon sizes (16×16, 22×22, and 24×24) have been added to the places category to improve compatibility with Cinnamon, XFCE, and other desktop environments.

## Installation:

To install Whitesur Icon Theme for Cinnamon, run in the terminal:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:           | |
|:--------------------|:-------------|
|-d, --dest           | Specify theme destination directory (Default: $HOME/.local/share/icons)|
|-n, --name           | Specify theme name (Default: WhiteSur)|
|-t, --theme          | Specify theme color variant(s) [default/purple/pink/red/orange/yellow/green/grey/all] (Default: blue)|
|-a, --alternative    | Install alternative icons (redesigned MacOS default icons)|
|-b, --bold           | Install bold panel icons version|
|--black              | Black panel icons version|
|-r,--remove,-u,--uninstall | Uninstall (remove) icon themes|
|-h, --help           | Show this help|

</details>

> **Note for snaps:** To use these icons with snaps, the best way is to make a copy of the application's .desktop located in `/var/lib/snapd/desktop/applications/name-of-the-snap-application.desktop` into `$HOME/.local/share/applications/`. Then use any text editor and change the "Icon=" to "Icon=name-of-the-icon.svg"

> For more information, run: `./install.sh --help`

<p align="center"> <img src="https://raw.githubusercontent.com/vinceliuice/WhiteSur-icon-theme/master/alt-version.png"/> </p>

<p align="center"> <img src="https://raw.githubusercontent.com/vinceliuice/WhiteSur-icon-theme/master/bold-size.png"/> </p>

> The Bold version is recommended for `high-resolution displays`, such as 4K monitors using 200% display scaling.

## Preview
<p align="center"> <img src="https://github.com/vinceliuice/WhiteSur-icon-theme/blob/master/preview.png"/> </p>
<p align="center"> <img src="https://github.com/vinceliuice/WhiteSur-icon-theme/blob/master/preview01.png"/> </p>

## Recommended Settings

For the Whisker Menu (XFCE) to display correctly, open the Whisker Menu settings and enable Background opacity.

## Links to original theme for Gnome-based desktops
[WhiteSur-icon-theme](https://github.com/vinceliuice/WhiteSur-icon-theme)
<br>
[WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme)
<br>
