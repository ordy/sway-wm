# sway-wm
A darker version of the Kanagawa theme for sway wm.

#### GTK theme

Extract the zip file to the themes directory, usually in `~/.local/share/themes/` or `~/.themes/` (create it if necessary). Then create a symbolic link to the gtk-4.0 folder in your `./.config` directory.
```
ln -s ~/.local/share/themes/Juno/gtk-4.0 ~/.config/
```

To set the theme on gtk-2 and gtk-3 applications, either updated your config files manually or ruse a GUI like lxappearance. For gtk-4 based applications, run the following commands in Terminal:
```
gsettings set org.gnome.desktop.interface gtk-theme "Juno"
gsettings set org.gnome.desktop.wm.preferences theme "Juno"
```
To change the icons theme
```
gsettings set org.gnome.desktop.interface icon-theme 'Colloid-dracula-dark'
```
To change the font
```
gsettings set org.gnome.desktop.interface font-name 'Inter'
```

