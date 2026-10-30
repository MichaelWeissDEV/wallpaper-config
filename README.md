# Wallpaper switcher

Hyprpaper-CLI und Fuzzel-TUI mit globalem Default, Monitor-Overrides und Hot-Plug-Wiederherstellung.

**[Dokumentation und CLI-Befehle](https://arch-dotfiles.readthedocs.io/en/latest/components/#wallpaper)** ·
[Desktop-Anleitung](https://arch-dotfiles.readthedocs.io/en/latest/hyprland/) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- wallpaper
```

Paket: `arch-dotfiles-wallpaper`. Datei: `~/.config/wallpaper/wallpaper.conf`.
Private Bilder sind kein Paketinhalt; beispielsweise `~/Pictures/Wallpapers` verwenden.
`wallpaper doctor` prüft die Laufzeitumgebung. Befehle und Konfiguration stehen im Handbuch.

Hier auf `main` pushen; nach erfolgreichem Registry-Build mit `sudo pacman -Syu`
aktualisieren. Entwicklung und lokale Builds: [PACKAGING.md](PACKAGING.md).

[![Package safety](https://github.com/MichaelWeissDEV/wallpaper-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/wallpaper-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
