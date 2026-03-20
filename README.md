<div align="center">

# VS DarkCode

A minimal and high-contrast dark theme for Visual Studio Code, focused on clarity, consistency, and a distraction-free coding experience.

</div>

---

## Overview

VS DarkCode is designed with a strict dark palette and carefully balanced contrast. It provides a clean interface across all major areas of the editor, including the sidebar, terminal, and settings UI.

---

## Preview

![Editor Preview](./images/editor.png)

---

## Features

* Deep dark interface with minimal visual noise
* High contrast for improved readability
* Consistent styling across UI components
* Clean terminal and panel integration
* Subtle focus and selection states
* Balanced use of accent colors

---

## Download

<div align="center">

<a href="https://github.com/kirito666coder/VS-DarkCode/releases/download/v0.0.2/VS-DarkCode-0.0.2.vsix">
  <img src="https://img.shields.io/badge/Download%20Theme-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</a>

</div>

---

## Trust & Safety

You can safely use this `.vsix` file — it only contains theme configuration for Visual Studio Code and does not include any harmful scripts or code.

However, if you still prefer not to trust a prebuilt file, you can easily generate your own VSIX package by following the steps below.

---

## Build Your Own VSIX (Optional)

If you don’t trust downloading the VSIX file, you can create it yourself:

### Requirements

* Install **Node.js**
* Install VS Code Extension tool:

```
npm install -g vsce
```

### Steps

1. Open the project folder in terminal
2. Run:

```
vsce package
```

3. A `.vsix` file will be generated in your project folder

### Notes

* You can delete old `.vsix` files anytime
* If you want a custom file name, edit the `"name"` field in `package.json` before packaging
* The generated VSIX file name will follow your package name and version

---

## Installation

### From VSIX

1. Open **Visual Studio Code**
2. Go to **Extensions** (Ctrl + Shift + X)
3. Click the **three dots (⋯)** in the top-right corner
4. Select **Install from VSIX...**
5. Choose your `.vsix` file

---

## Usage

1. Open Command Palette:
   **Ctrl + Shift + P**

2. Search and select:
   **Preferences: Color Theme**

3. Choose:
   **VS DarkCode**

---

## Customization

This theme is designed to be easily adjustable. You can override colors in your own settings if needed.

---

## Versioning

This project follows semantic versioning:

* Patch releases for small fixes
* Minor releases for improvements
* Major releases for significant design changes

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Author

<div align="center">

<a href="https://github.com/kirito666coder">
  <img src="https://img.shields.io/badge/kirito-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
</a>


Creator of **VS DarkCode**, a high-contrast, minimal VS Code theme designed to improve focus, readability, and productivity for developers.

[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/kirito666coder)

</div>
