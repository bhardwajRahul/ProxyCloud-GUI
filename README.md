# ProxyCloud GUI

[![GitHub issues](https://img.shields.io/github/issues/code3-dev/ProxyCloud-GUI)](https://github.com/code3-dev/ProxyCloud-GUI/issues)
[![License](https://img.shields.io/github/license/code3-dev/ProxyCloud-GUI)](LICENSE)

ProxyCloud GUI is a free, fast, and user-friendly desktop application for managing proxy connections across multiple platforms.

## Features

- Cross-platform support (Windows, macOS, Linux)
- Easy-to-use graphical interface
- Multiple proxy protocol support
- Country-based proxy selection
- System tray integration
- Custom configuration options

## Installation

### Windows

- Download the latest Windows installer or portable version from the [Releases](https://github.com/code3-dev/ProxyCloud-GUI/releases) page
- Run the installer or extract the portable version
- Launch the application

### macOS

- Download the latest macOS DMG or ZIP from the [Releases](https://github.com/code3-dev/ProxyCloud-GUI/releases) page
- Open the DMG and drag the application to your Applications folder or extract the ZIP
- Launch the application

### Linux

- Download the latest Linux package (DEB, RPM, AppImage, or tar.gz) from the [Releases](https://github.com/code3-dev/ProxyCloud-GUI/releases) page
- Install the package using your package manager or extract the archive
- Launch the application

#### Arch Linux

ProxyCloud is now on the [AUR](https://aur.archlinux.org/packages/proxycloud-gui-bin), therefore you can install it using your prefered AUR helper.

```bash
paru -S proxycloud-gui-bin

# or if you are using yay

yay -S proxycloud-gui-bin
```

## Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- npm or yarn

### Setup

```bash
# Clone the repository
git clone https://github.com/code3-dev/ProxyCloud-GUI.git
cd ProxyCloud-GUI

# Install dependencies
npm install

# Start the application
npm start
```

### Building

```bash
# Build for Windows
npm run build:win

# Build for Linux
npm run build:linux

# Build for all platforms
npm run build
```

## Configuration

Configuration files are stored in the `config/` directory. You can modify these files to customize your proxy settings.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Bug Reports and Feature Requests

Please use the [GitHub issue tracker](https://github.com/code3-dev/ProxyCloud-GUI/issues) to report bugs or request features.

## Contact

For questions or support, please contact the developer at [h3dev.pira@gmail.com](mailto:h3dev.pira@gmail.com).
