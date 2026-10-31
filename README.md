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

### Bedienung

`wallpaper list` zeigt verfügbare Bilder; `wallpaper set DATEI` setzt den Standard. Mit `wallpaper set DATEI --monitor DP-1` lässt sich ein Bildschirm getrennt konfigurieren. `wallpaper doctor` prüft die Voraussetzungen.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/wallpaper-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/wallpaper-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
