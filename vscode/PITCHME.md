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

Note:
- Stable is released on a monthly cadence
- Insider is released anywhere from every few hours, days, or weeks
- Insider you won't see the version number change much.
    - Based on the commit and date value
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

- `CTRL` @fa[plus] `SHIFT`, `P` shortcut
- View @fa[angle-right] Command Palette

![git example](/images/vscode/commandpalette_git.png)