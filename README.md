# HaTeX_Editor 🧪

> **H**uyouyang + L**aTeX** = **HaTeX**
> A bi-directional formula editor designed to lower the barrier of entry for LaTeX.

---

## 0. 💭 Developer's Note

This is my first project. I took the initial of my surname **H** to form **HaTeX**, which ironically spells the word `hate` 😂. After all, it's easy to get "red-faced" 🤬 whenever LaTeX renders something weird.

This is only the **first phase (v1.2)**. Although the feature set is limited, it is sufficient for daily use. Future plans include inserting more functions, and even utilizing **CNN** to achieve handwritten formula recognition.

If you have any bugs or ideas for the project, feel free to contact me:
📧 [youyanghu@mail.ustc.edu.cn](mailto:youyanghu@mail.ustc.edu.cn)

---

## 1. 📥 Installation Guide

If you are reading this, it means you have already unzipped the files. The operation is very simple:

1.  Simply double-click **`HaTeX _v1.2.2.exe`** in the folder to run it.
2.  💡 **Tip**: You can right-click to create a shortcut on the desktop for easy startup next time.

> ⚠️ **Important Notice**:
> **DO NOT MOVE** anything inside the `HaTeX _v1.2.2-beta` folder (including the `.exe` program itself), otherwise the software may fail to run!

---

## 2. ⚠️ Important Notes (Must Read)

### ❗ Core Warning
**DO NOT MOVE OR RENAME any file structures inside the `HaTeX _v1.2.2-beta` folder!**

### 📁 Path Requirements
This software relies on a local CDN to load the math formula engine (**MathLive**).
-   ✅ **Usage**: Please ensure `HaTeX _v1.2.2.exe` and `_internal` are in the same folder.

### 💻 System Requirements
-   **Operating System**: Windows 10 or Windows 11
-   **Environment Dependency**: No Python environment installation required, ready-to-use (Standalone EXE).

### 🛡️ Antivirus Warning
Since the software is packaged, some antivirus software (like Windows Defender) might **flag it as false positive**.
-   If intercepted, please select **"Allow to run"**.
-   Or add the entire `HaTeX` folder to the antivirus software's **whitelist/trusted zone**.

---

## 3. 📘 User Guide

This software is designed for simplicity and is easy to pick up. Here is a brief introduction to the core functions:

### 🚀 Quick Check
When you first open the software, if the upper window successfully renders **Euler's Identity** ($e^{i\pi} + 1 = 0$), it means the software is running normally.
-   If no LaTeX code is displayed below, it does not affect usage.
-   **If the formula is NOT rendered in the upper window**: Please first check the **path issues** mentioned above. If the problem persists, please report it to the developer via email (preferably with your PC information, which can be obtained by typing `systeminfo` in CMD).

### ⌨️ Editing Methods
-   **Lower Window (Code Area)**:
    -   You can directly type LaTeX source code.
    -   Supports **Copy/Paste**.
    -   *Fault Tolerance*: If compilation fails, the upper window will retain and render the **last correct** result (currently does not support displaying specific compiler error messages).
    -   You can use `Ctrl+Z` to undo!

-   **Upper Window (Preview Area)**:
    -   You can directly type English letters, numbers, and basic symbols (`+ - * / = % ^`).
    -   **Virtual Soft Keyboard**: Other complex symbols can be input via the soft keyboard.
        -   💡 **Tip**: Hold down the `Shift` key to enable the hidden symbols in the upper right corner of the soft keyboard (the layout logic is consistent with Casio calculators).

### 🧩 Advanced Features
-   **Formatting**: Click **Format Matrix** on the toolbar or press `Ctrl+Shift+F` to format LaTeX code! The current version supports auto-formatting code~
-   **Matrix Editing**: Click the **≡** icon in the menu bar; there are many useful matrix templates and functions inside!
-   **Auto-complete Code**: In the upper editing area, type `\` and then a letter to bring up intended symbols; in the lower code area, type `\` (you can also skip this, but if there is also a `\` before it, it will cause an error) and then a letter to bring up intended symbols. Press `Tab`, `Enter`, or click to input.

> 🐢 **Developer's Note**: I am extremely lazy, so I'll stop writing the documentation here. Most input methods that feel intuitive to normal people are valid. The full version will be uploaded to GitHub later. If you need it urgently, please contact me by email.

---

## 4. 🛠️ Tech Stack

This project is built with the following hardcore technologies:

| Component | Technology |
| :--- | :--- |
| **Programming Language** | Python 3.14 |
| **GUI Framework** | PySide6 (Qt for Python) |
| **Formula Engine** | MathLive (Web Component) |
| **Packaging Tool** | PyInstaller 6.19.0 |

> 🤖 During development, **Qwen (Tongyi Qianwen)** was used to assist with coding and packaging the EXE.

---

## 5. 📝 Changelog

### v1.0.0 (2026-03-26)
-   🎉 **Initial Release**.
-   ✨ Supports basic LaTeX formula editing and real-time preview.
-   ⌨️ Integrated virtual soft keyboard (supports Shift extension symbols).
-   🐛 Known Issue: Cannot render offline.
### v1.0.1 (2026-04-10)
-   🎉 **Completed MathLive local deployment**, enabling offline usage.
-   🐛 Known Issue: Matrix LaTeX code readability is poor; no auto-complete code feature.
### v1.1.0 (2026-04-10)
-   🎉 **Added formatting feature**, LaTeX code can be formatted manually.
-   🐛 Known Issue: No auto-complete code feature.
### v1.1.1 (2026-04-10)
-   🎉 **Added auto-formatting feature**, LaTeX code can be auto-formatted.
-   🐛 Known Issue: No auto-complete code feature.
### v1.2.0 (2026-04-10)
-   🎉 **Developed code auto-complete feature**
-   🐛 Known Issue: Many bugs.
### v1.2.1 (2026-04-10)
-   🎉 **Rewrote completion logic**
### v1.2.2 (2026-04-10)
-   🎉 **Further optimization**
-   🐛 Known Issue: Formatting has issues when using matrix functions. It is temporarily released as a beta version. The developer will come back to debug after finishing the mid-term exam QwQ.
-   (｡•̀ᴗ-)✧ Updating six times in one day, what a feat~

---

<div align="center">
  <p>Made with ❤️ by Youyang Hu</p>
  <p><i>May your formulas always compile successfully.</i></p>
</div>
