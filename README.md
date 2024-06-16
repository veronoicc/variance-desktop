# Variance desktop

<a href="https://github.com/veronoicc/variance-desktop/releases">
  <img alt="GitHub release downloads" src="https://img.shields.io/github/downloads/veronoicc/variance-desktop/total?style=social"></a>

Variance is a matrix client focusing primarily on simple, elegant and secure interface. The desktop app is made with Tauri.

## Download

Installers for macOS, Windows and Linux can be downloaded from [Github releases](https://github.com/veronoicc/variance-desktop/releases).

Operating System | Download
---|---
Windows | <a href='https://github.com/veronoicc/variance-desktop/releases/latest/download/Variance_desktop-x86_64.msi'>Get it on Windows</a>
macOS | <a href='https://github.com/veronoicc/variance-desktop/releases/latest/download/Variance_desktop-x86_64.dmg'>Get it on macOS</a>
Linux | <a href='https://github.com/veronoicc/variance-desktop/releases/latest/download/Variance_desktop-x86_64.AppImage'>Get it on Linux</a>

## Local development

Firstly, to setup Rust, NodeJS and build tools follow [Tauri documentation](https://tauri.app/v1/guides/getting-started/prerequisites).

Now, to setup development locally run the following commands:
* `git clone --recursive https://github.com/veronoicc/variance-desktop.git`
* `cd variance-desktop/variance`
* `npm ci`
* `cd ..`
* `npm ci`

To build the app locally, run:
* `npm run tauri build`

To start local dev server, run:
* `npm run tauri dev`
