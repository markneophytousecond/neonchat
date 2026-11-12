<div align="center">

# ✦ NeonChat

### A new way to stay connected.

**Your conversations. Your community. Your NeonChat.**

A modern desktop client built to bring the NeonChat experience to Windows and Linux.

<br>

[![Version](https://img.shields.io/badge/version-0.15.0-8b5cf6?style=for-the-badge)](https://github.com/)
[![Electron](https://img.shields.io/badge/Electron-36-47848f?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![Windows](https://img.shields.io/badge/Windows-Available-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/markneophytousecond/neonchat/releases/download/neonchat-0150-win/neonchat-desktop-windows.exe)
[![Linux](https://img.shields.io/badge/Linux-Available-FCC624?style=for-the-badge&logo=linux&logoColor=black)](ttps://github.com/markneophytousecond/neonchat/releases/download/neonchat-0150-linux/neonchat-desktop-linux.deb)

<br>

**[🌐 Visit NeonChat](https://d9devproject.neocities.org/neonchat/neonchat/)** · **[📦 Releases](../../releases)** · **[🐛 Report a Bug](../../issues)**

</div>

---

## ✦ About NeonChat

NeonChat is a desktop client project developed under **D9 Dev Project**, focused on bringing the NeonChat platform to desktop environments.

Built with Electron, the application packages the NeonChat experience into a desktop application for supported operating systems.

Whether you're using Windows or Linux, NeonChat aims to provide a convenient way to access the platform directly from your desktop.

## 🚀 Downloads

**Get the latest version of NeonChat Desktop.**

<div align="center">

| Platform | Package | Download |
|:---:|:---:|:---:|
| 🪟 Windows | `.exe` | [Download for Windows](../../releases/latest) |
| 🐧 Ubuntu / Debian | `.deb` | [Download for Linux](../../releases/latest) |
| 🐧 Linux | `.AppImage` | [Download AppImage](../../releases/latest) |

</div>

> **Important:** Download links above point to the latest GitHub Release for this repository. Open the release and select the appropriate file under **Assets**.

### Which version should I download?

- **Windows:** Choose the `.exe` installer.
- **Ubuntu / Debian:** Choose the `.deb` package.
- **Other compatible Linux distributions:** Try the `.AppImage` package.

Always download releases from the official repository.

---

## ✨ Features

### 💬 Desktop experience
Access NeonChat through a dedicated desktop application rather than relying exclusively on a browser.

### 🖥️ Multi-platform support
Desktop packages are available for Windows and Linux.

### ⚡ Electron-powered
Built using Electron, combining web technologies with desktop application capabilities.

### 📦 Multiple package formats
Choose an installer or portable package that suits your operating system.

### 🔄 Versioned releases
Download published builds and find release-specific updates through GitHub Releases.

---

## 🛠️ Installation

### 🪟 Windows

1. Open the [latest release](../../releases/latest).
2. Download the NeonChat `.exe` installer.
3. Run the installer.
4. Follow the installation instructions.
5. Launch NeonChat.

Windows may display security warnings for unsigned applications. Only run installers you trust and have obtained from the official release page.

### 🐧 Ubuntu / Debian

1. Open the [latest release](../../releases/latest).
2. Download the `.deb` package.
3. Open a terminal in the directory containing the downloaded file.
4. Run:

```bash
sudo apt install ./neonchat-desktop-linux.deb
```

Replace the example filename with the actual downloaded filename.

After installation, launch NeonChat from your applications menu if the desktop entry is available.

### 🐧 Linux AppImage

1. Download the `.AppImage` file from the [latest release](../../releases/latest).
2. Open a terminal in the download directory.
3. Make the file executable:

```bash
chmod +x NeonChat-0.15.0.AppImage
```

4. Launch the application:

```bash
./NeonChat-0.15.0.AppImage
```

Replace the example filename with the actual downloaded filename.

If the application reports a missing FUSE dependency, install the appropriate compatibility package for your Linux distribution.

---

## ⚙️ Built With

| Technology | Purpose |
|---|---|
| [Electron](https://www.electronjs.org/) | Desktop application framework |
| [Node.js](https://nodejs.org/) | JavaScript runtime |
| [electron-builder](https://www.electron.build/) | Application packaging and distribution |
| HTML / CSS / JavaScript | Web technologies, where used by the client |

---

## 👨‍💻 Development

Want to run NeonChat Desktop locally?

### Requirements

- Node.js and npm
- Git, if cloning the repository
- A supported desktop operating system

### Setup

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Enter the desktop project directory:

```bash
cd YOUR_REPOSITORY_DIRECTORY/build-clients/desktop
```

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npm start
```

### Build for Linux

Create Linux packages:

```bash
npm run build:linux
```

Or build an individual format:

```bash
npm run build:deb
```

```bash
npm run build:appimage
```

### Build for Windows

```bash
npm run build:win
```

Windows builds may require Windows-specific tooling or a compatible build environment.

Build outputs are written to the `dist/` directory.

> **Development note:** These commands assume the repository contains the `build-clients/desktop` directory and the corresponding npm scripts. Adjust the paths if your repository layout differs.

---

## 📁 Project Structure

The desktop build directory contains the Electron application configuration.

```text
desktop/
├── main.cjs
├── server-url.json
├── package.json
├── package-lock.json
├── node_modules/
└── dist/
    ├── NeonChat-0.15.0.AppImage
    └── neonchat-desktop-linux_0.15.0_amd64.deb
```

The generated `dist/` files are build artifacts. The Windows installer is also generated there when a Windows build succeeds.

Your complete repository may contain additional frontend, backend, and configuration directories.

---

## 🔐 Security & Privacy

- Download releases from trusted sources.
- Keep NeonChat updated to the latest stable release.
- Never share passwords, authentication tokens, or private credentials.
- Review the project's privacy policy before relying on it for sensitive communications.

**Important:** Security, encryption, and privacy protections depend on the actual implementation of the NeonChat platform. This README does not claim end-to-end encryption or other security features that have not been independently verified.

---

## 🐛 Bug Reports & Feedback

Found a bug or have an idea for NeonChat?

Please open an issue through the repository's **Issues** tab.

When reporting a bug, include:

- Your operating system and version.
- Your NeonChat Desktop version.
- Steps to reproduce the issue.
- Relevant error messages or screenshots.

Please remove passwords, tokens, and other sensitive information before posting logs.

---

## 🗺️ Roadmap

Potential areas for future development:

- [ ] Improve desktop integration.
- [ ] Refine installation and update workflows.
- [ ] Improve compatibility across Linux distributions.
- [ ] Enhance error handling and diagnostics.
- [ ] Expand platform-specific testing.

This roadmap is a set of development goals, not a guarantee that these features are already implemented or scheduled.

---

## 🏢 About D9 Dev Project

**NeonChat is part of D9 Dev Project**, a project focused on software development and digital tools.

🌐 **Website:** [D9 Dev Project](https://d9devproject.neocities.org/)

💬 **NeonChat:** [Visit the platform](https://d9devproject.neocities.org/neonchat/neonchat/)

---

<div align="center">

### ✦ Stay Connected.

**NeonChat Desktop · Version 0.15.0**

Developed by **D9 Dev Project**

<sub>Thank you for checking out NeonChat. Every bug report and piece of constructive feedback helps improve the project.</sub>

</div>
