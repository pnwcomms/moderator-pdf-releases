# Moderator PDF downloads

Moderator PDF is a lightweight PDF editor for Windows, Linux, and Android. No AI assistant, no cloud account, no integrations. Files open from and save to the device.

This repository holds the installers only. The app checks here for new versions.

## Get the latest version

Open the [latest release](https://github.com/pnwcomms/moderator-pdf-releases/releases/latest) and download the file for your system:

| System | File |
| --- | --- |
| Windows | `Moderator.PDF_x.y.z_x64-setup.exe` |
| Debian, Mint | `Moderator.PDF_x.y.z_amd64.deb` |
| Other Linux | `Moderator.PDF_x.y.z_amd64.AppImage` |
| Android | `Moderator.PDF_x.y.z_android.apk` |

### Windows

The installer is not code-signed, so Windows shows a SmartScreen warning the first time. Choose "More info", then "Run anyway".

### Debian and Mint

```
sudo apt install ./Moderator.PDF_x.y.z_amd64.deb
```

### Android

Open the `.apk` from your browser's downloads or a file manager, and allow that app to install unknown apps when asked.

## Updates

Once installed, the app looks for a new version when it starts and offers to update. You can also check from Help > Check for Updates, and turn the automatic check off from the same tab.

- Windows and Linux update inside the app. Linux asks for your password to install.
- Android opens the new `.apk` in your browser to download, and you confirm the install.
