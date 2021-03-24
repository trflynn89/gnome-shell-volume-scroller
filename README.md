# Volume Scroller for GNOME Shell

Use the mouse wheel on the GNOME Top Bar to increase or decrease volume.

## Release

To prepare for uploading to [GNOME Shell Extensions](https://extensions.gnome.org/):

```bash
zip -j  volume_scroller@trflynn89.pm.me.zip volume_scroller@trflynn89.pm.me/*
```

## Manual Installation

```bash
ln -sf $(pwd)/volume_scroller@trflynn89.pm.me ~/.local/share/gnome-shell/extensions
```

Restart GNOME Shell. You may either log out and log back in, or enter `Alt+F2` to open the run
dialog, then type `r` to restart the GNOME Shell.
