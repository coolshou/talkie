# Talkie
A cross-platform app for system-wide push-to-talk, written in C++ with Qt.


[![GitHub release (latest by date)](https://img.shields.io/github/v/release/alexandrvicente/talkie)](https://github.com/alexandrvicente/talkie/releases/latest)
![GitHub](https://img.shields.io/github/license/alexandrvicente/talkie)

![Demo](misc/readme/demo.gif)
## Build from source
```bash
git clone https://github.com/coolshou/talkie.git
cd talkie
git submodule init
git submodule update
qmake
make
```
## Installing
Download the latest release:

- [Windows](https://github.com/alexandrvicente/talkie/releases/latest/download/Talkie.msi)
- [Mac](https://github.com/alexandrvicente/talkie/releases/latest/download/Talkie.dmg)
- [Linux (x86-64 AppImage)](https://github.com/alexandrvicente/talkie/releases/latest/download/Talkie-x86_64.AppImage)
  - ⚠️ **Wayland is not supported**, as it doesn't support global hotkeys and [QHotkey](https://github.com/Skycoder42/QHotkey) does not currently use desktop env APIs
  - Requires OpenSSL 1.1 and amixer

## License
Talkie is licensed under the [3-Clause BSD License](https://opensource.org/licenses/BSD-3-Clause).
