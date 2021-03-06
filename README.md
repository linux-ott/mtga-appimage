
![GitHub Logo](res/magic_logo.jpg)

<p align="center"><i>"Magic The Gathering is a collectible and digital collectible card game created by Richard Garfield. Released in 1993 by Wizards of the Coast.</i>"
</p>


**Download: [mtga-appimage](https://github.com/linux-ott/mtga-appimage/releases/tag/mtga-appimage)**

No wine installation required

## Dependencies

### Arch
```
sudo pacman -S wget jq curl
```

### Debian/Ubuntu/elementaryOS
```
sudo apt install wget jq curl
```

## Install Magic

Do not change the folder-paths on Windows

```
git clone https://github.com/linux-ott/mtga-appimage.git
cd mtga-appimage/
./mtga-appimage.sh --install
```

Installation directory ```$HOME/.local/apps/magic```

## Usage Arguments

| Arguments       |    | What its does                                   |
|-----------------|----|-------------------------------------------------|
| --install       | => | Installed Magic                                 |
| --run           | => | Run Magic                                       |
| --remove        | => | Removed Magic                                   |
| --update        | => | Update Magic                                    |
| --winetricks    | => | Start Winetricks                                |

## Sources

**[Wine32-AppImage](https://github.com/sudo-give-me-coffee/wine32-deploy)**

**[MTGA-Version](https://mtgarena.downloads.wizards.com/Live/Windows32/version)**

**[Logo](https://cdn.wccftech.com/wp-content/uploads/2018/09/Magic-the-Gathering-Arena-Art.jpg)**

