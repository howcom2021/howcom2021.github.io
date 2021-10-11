---
layout: page
title: Cases and installation
permalink: /cases-and-installation
order: 5
---

# Cases

* [CMCM](/cases/cmcm.pdf)
* [MetaEdit+](https://docs.google.com/document/d/1XXdHRFIky4tAcK4DbJzw7jQvr97w5xiu0QhHsxbScLE/edit#)
* [TGRL](/cases/tgrl.pdf)

# Installation details

### CMCM (1-3 minutes)
* Download and install from [https://uol.de/se?cmcm](https://uol.de/se?cmcm).
* Requires Java 8 and JavaFX (included in download).

### MetaEdit+ (1-3 minutes)

[Instructions are here](https://docs.google.com/document/d/1XXdHRFIky4tAcK4DbJzw7jQvr97w5xiu0QhHsxbScLE/edit#)

You’ll be accessing our server with Microsoft’s Remote Desktop Connection (mstsc.exe). This is installed by default on Windows, but for other platforms you can install it:
* Mac: Microsoft Remote Desktop @[App Store](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)
* Linux: [Remmina](https://linuxkamarada.com/en/2020/04/20/remote-desktop-connection-to-windows-from-linux-using-rdp-clients/#remmina) (pre-installed on Ubuntu), [FreeRDP](https://linuxkamarada.com/en/2020/04/20/remote-desktop-connection-to-windows-from-linux-using-rdp-clients/#freerdp) etc.


### TGRL (1-5 minutes)
* Install the desktop-based VS Code application on your system from the [VS Code site](https://code.visualstudio.com/download).
* Download our tool in the form of vsix file (`vscode-xtext-turn-0.0.2.vsix`) from the [GitHub repository](https://github.com/Rijul5/vscode-turn) of our tool. We provide further details in our repository to develop or debug the extension.
* Open a Terminal to create a project run directory (workspace) and launch VS code extension using the below commands:
```
mkdir workspace
cd workspace
code .
```
* Install the downloaded VSIX file (`vscode-xtext-turn-0.0.2.vsix`) of our proposed TGRL extension in VS Code by using shortcut key CTRL + SHIFT + X or navigating in menu bar: View → Extensions → Install from VSIX... → Select the downloaded vsix file.
* Install the VS Code Live Share extension using the “Search extensions in Marketplace” or using the below command after using CTRL + P (VS Code Quick Open) shortcut key:
```ext install MS-vsliveshare.vsliveshare-pack```.
* Click on the “LiveShare” option in the bottom left corner of VS Code to start a collaboration session.
* Modeller can create TGRL Models (file with .turn extension) collaboratively. For quick start, we have provided a sample TGRL model ”example.turn” in the “examples” folder of the [repository](https://github.com/Rijul5/vscode-turn).
