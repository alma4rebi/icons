<img title="Various icons" src="/README.png">

# elementary Icons
An original set of vector icons designed specifically for [elementary OS](http://elementary.io) and its desktop environment: Pantheon.

These icons are licensed openly under the terms of the [GNU General Public License](COPYING). Redistributing, forking, remixing, etc. are encouraged!

If you feel the desire to compensate the artists who maintain these icons for your usage, [please see this page](http://elementary.io/get-involved#funding) and thank you!

## Contributing Icons
It is recommended to use the free and open source [Inkscape](http://inkscape.org) vector editor to create elementary icons. Any and all icons must follow the elementary [Icon Design Guidelines](http://elementary.io/docs/human-interface-guidelines#iconography).

To contribute to the elementary icon set, open a pull request to this repository with your icon(s).

It is strongly encouraged to vacuum all vectors with [Inkscape](http://inkscape.org). This keeps the repository lean, clean, and fast for everyone. For convenience, a git pre-commit hook is included. To install, run these commands from your local repository folder:
```bash
$ cp pre-commit .git/hooks/
$ chmod +x .git/hooks/pre-commit
```

## Not a Universal Icon Set
Since this set is designed specifically for elementary OS, pull requests to add icons or symlinks that are specific to other desktop environments (such as `xfce-*` or `gnome-*` named icons) will be rejected.

Use of icon names in line with the [FreeDesktop.Org Icon Naming Specification](http://standards.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html) is encouraged.

## Third-Party Brand Preservation
elementary icons do not attempt to supply icons for third-party apps. Pull requests to add icons or symbolic links that would overwrite the branding of third-party apps will be rejected.
