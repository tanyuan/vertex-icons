# Vertex Icons for GNOME

This is a light icon theme features gray folders from **Vertex Icons** and mimetype icons from **Elementary Icons**. Looks good with GNOME default theme **Adwaita**.

This icon theme is not complete and with no application icons.

![Original Cover](http://i.imgur.com/paECSRR.png)

## Installation

1. Copy to `~/.icons` or to `/usr/share/icons` for system-wide use.
2. Select **Vertex** in **GNOME Tweak Tool**.

## Customization

### Activities Icon

Install GNOME extension **[Activities configurator](https://extensions.gnome.org/extension/358/activities-configurator/)** and you can add Linux distro icons in `places/symbolic/start-here-*-symbolic.svg` to top panel.

### Application Icons

Add PNG or SVG icons with name of the application like `APPLICATION.png` (replace `APPLICATION` with your application name) and in corresponding pixel size to folders at least `apps/48/`, `apps/64/`, `apps/128/` and `apps/256/`.

Application mono SVG icons on GNOME Top Panel can be added to `apps/symbolic/` with file name `APPLICATION-symbolic.svg` (replace `APPLICATION` with your application name).

### File Icons

Put SVG icons or symbolic links under `mimetypes/128/` is sufficient.

#### Add new file types

Make sure Nautilus recognize your file type (mimetype) by right click on the file, open **Properties** and check **Type**.

If it does not recognize your mimetype, define yours in `~/.local/share/mime/packages/`, for example `stl.xml` for `.stl` files.

Run after you add a file:
```
update-mime-database ~/.local/share/mime/
```

## Credits

* [Vertex Icons](https://github.com/horst3180/vertex-icons): GPL v3

* [Elementary Icons](https://github.com/elementary/icons): GPL v3

* [GNOME Icons](https://github.com/gnome-design-team/gnome-icons): Creative Commons Attribution-Share Alike 3.0 United States License

Other icons are licensed under GPL v3.
