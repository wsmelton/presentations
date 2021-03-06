## Visual Studio Code
### Getting Started
@snap[south]
@size[small](PSPowerHour - August 30, 2018)
@snapend
---?include=aboutme/aboutme.md

---
## Builds

- Stable
![stable](images/vscode/stablebuildicon.png)

- Insider
![insider](images/vscode/insiderbuildicon.png)

- Non-Admin Installer [here](https://code.visualstudio.com/updates/v1_25#_user-setup-for-windows)

Note:
- VS Code is built on Electron framework (based on NodeJs)
    - Allows for embedding and modifying it for other uses (i.e. Azure Cloud Shell, SQL Operations Studio)
- Stable is released on a monthly cadence
- Insider is released anywhere from every few hours, days, or weeks
- Insider you won't see the version number change much.
    - Based on the commit and date value
- Preview of a non-admin installer, only for Insider Build right now
---
@transition[none]
## Interface Overview

@snap[north-east]
@size[small]([more details](https://code.visualstudio.com/docs/getstarted/userinterface))
@snapend

---?image=images/vscode/interface_overview.png&size=contain

Note:
- Help > Welcome > Learn > Interface Overview
- Activity Bar - growing as more extensions support new UI options
- Editor Groups - Big feature is grid layout, snap an editor to right, left, up or down
- Panel - offers view of what is going on from output logs
- Status Bar - varies on data displayed based on what extensions you are using

---
## Zoom Zoom
@snap[north-east]
@size[small]([more details](https://code.visualstudio.com/docs/editor/accessibility))
@snapend

- Environment (including editor)
- Editor text (only)

---
## Extensions

@snap[north-east]
@size[small]([more details](https://code.visualstudio.com/docs/editor/extension-gallery))
@snapend

- Marketplace @size[small]([https://marketplace.visualstudio.com/vscode](https://marketplace.visualstudio.com/vscode))
- Extensions Activity Bar (within VS Code)
- VSIX file (via Activity Bar)
    - Rolling back an extension
    - Test pre-release extensions
- Command line option (`code-insiders --install-extension author.extension-name`) [example one-liner](https://twitter.com/wsmelton/status/1025029106612744192)

---
## Settings
@snap[north-east]
@size[small]([more details](https://code.visualstudio.com/docs/getstarted/settings))
@snapend

New UI default as of 1.27.0

- User Settings
- Workspace Settings (override user settings)

Note:
- Settings from user and workspace at times will overwrite each other
- Presenting? Use workspace settings for the ideal environment setup for display (i.e. zoom level, color, text size/font, disable extensions)

---
## Command Palette

- CTRL @fa[plus] SHIFT, P
- View @fa[angle-right] Command Palette

![git example](/images/vscode/commandpalette_git.png)

---
## Extensions
### PowerShell Development

@size[small](`code-insiders --installed-extensions`)

---

- [PowerShell](https://marketplace.visualstudio.com/items?itemName=ms-vscode.PowerShell)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [VS Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)

Note:
- Basic list of extensions
- Code Spell Checker respects camel-casing and is available in other language extensions as well
- Settings Sync is a must if you use multiple devices (i.e. work and home office), can use private or public gist to store data
- VS Live Share is still in preview
    - Released today that you can have read-only access for guest (built for mentoring or online presentations)

---
### PowerShell Extension

- PowerShellEditorServices [PSES] ([GitHub](https://github.com/PowerShell/PowerShellEditorServices))
- Integrated Terminal vs Terminal
- Debugging options

Note:
- PowerShell Editor Services is the meat of the PowerShell extension
- The "terminal" is VS Code's terminal
    - Respect to PowerShell that is the PowerShell.exe session
- Integrated Terminal is a custom host built by the PSES
    - You will have different experiences
    - Please submit issues if you find them

---

## Submitting Issues

- Help @fa[angle-right] Report Issue

---

@fa[hourglass-end fa-4x]