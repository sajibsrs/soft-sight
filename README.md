![banner](https://raw.githubusercontent.com/sajibsrs/soft-sight/master/banner.png)

[![version](https://img.shields.io/vscode-marketplace/v/sajibsrs.soft-sight.svg?style=flat&label=current)](https://marketplace.visualstudio.com/items/sajibsrs.soft-sight) &nbsp;
[![installs](https://img.shields.io/vscode-marketplace/d/sajibsrs.soft-sight.svg?style=flat&label=downloads)](https://marketplace.visualstudio.com/items/sajibsrs.soft-sight) &nbsp;
[![ratings](https://img.shields.io/vscode-marketplace/r/sajibsrs.soft-sight.svg?style=flat&label=rating)](https://marketplace.visualstudio.com/items/sajibsrs.soft-sight)

# Soft sight color theme for vscode

A color theme for __vscode__ that feels soft and pleasant to eyes.

![go-sample](https://raw.githubusercontent.com/sajibsrs/soft-sight/master/preview/go.png)

## Languages
While most languages should work out of the box, it's currently optimized for:
- HTML, CSS, JSON
- JavaScript, TypeScript, JSX
- Go, PHP, Ruby
- More language support are being added.

## Installation

### 1. Using marketplace
- This color theme is freely available in the [visual studio code marketplace.](https://marketplace.visualstudio.com/items/sajibsrs.soft-sight)

### 2. Using vscode
- Press `Ctrl+P`
- Copy & paste

```shell
ext install sajibsrs.soft-sight
```
- Enter

## Recommended settings
> Here are vscode `settings` if you want your editor to look similar to `preview` screenshots.

### 1. Titlebar settings
```json
{
    "workbench.colorCustomizations": {
            "[soft sight]": {
                "titleBar.activeBackground": "#1b1e2b",
                "titleBar.activeForeground": "#53677a",
            }
        },
        "window.titleBarStyle": "custom"
}
```

### 2. Editor settings.
```json
{
    "editor.fontFamily": "'Fira Code', Menlo, Monaco, 'Courier New', monospace",
    "editor.fontSize": 18,
    "editor.lineHeight": 25,
    "editor.fontLigatures": true,
    "editor.cursorWidth": 3,
    "editor.cursorBlinking": "phase",
    "editor.renderWhitespace": "none",
    "editor.cursorSmoothCaretAnimation": true,
    "editor.scrollbar.vertical": "hidden",
    "editor.scrollbar.verticalScrollbarSize": 0
}
```

## What's new
Click here to view the [changelog](https://github.com/sajibsrs/soft-sight/blob/master/CHANGELOG.md)

## Notes
* Still in `beta` version. So there might be some issues.
* Please feel to submit your opinion and problem as [issue](https://github.com/sajibsrs/soft-sight/issues/new/choose).
* You can send modifications and improvements as __PR__.
* Licensed under [MIT License](https://github.com/sajibsrs/soft-sight/blob/master/LICENSE).

---
Made with ❤️ by Sajidur Rahman. If you like it, then please rate it.
