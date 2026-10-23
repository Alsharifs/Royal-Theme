<p align="center">
  <img src="https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/banner.png" alt="Royal Theme for Visual Studio Code" width="100%">
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme"><img src="https://img.shields.io/visual-studio-marketplace/v/alsharifs.royal-theme?style=for-the-badge&label=Marketplace&color=ffc600&labelColor=21252b&logo=visualstudiocode&logoColor=white" alt="Marketplace version"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme"><img src="https://img.shields.io/visual-studio-marketplace/i/alsharifs.royal-theme?style=for-the-badge&color=61afef&labelColor=21252b" alt="Installs"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme&ssr=false#review-details"><img src="https://img.shields.io/visual-studio-marketplace/r/alsharifs.royal-theme?style=for-the-badge&color=98c379&labelColor=21252b" alt="Rating"></a>
  <a href="https://github.com/Alsharifs/Royal-Theme/stargazers"><img src="https://img.shields.io/github/stars/Alsharifs/Royal-Theme?style=for-the-badge&color=c678dd&labelColor=21252b&logo=github" alt="GitHub stars"></a>
</p>

<p align="center">
  <b>A rich, gold-accented dark theme for Visual Studio Code.</b><br>
  Built on the familiar Atom One Dark palette, then customised across <b>139 UI colours</b> and <b>257 syntax rules</b>.
</p>

---

## ✨ Highlights

- 👑 **Royal gold accents.** The cursor, active tab, panel border, badges, search highlights and notifications all use the signature `#FFC600` gold, so you always know where your focus is.
- 🎨 **Atom One Dark at heart.** A calm `#282C34` canvas with the purple, blue, green, orange and red syntax colours you already know, so it's easy on the eyes for long sessions.
- 🧩 **Language-aware highlighting.** Hand-tuned scopes for **JavaScript / TypeScript, Python, HTML, CSS / SCSS / Less, JSON, Java, C / C++, Rust, Go, Haskell, Markdown, regex, diffs** and more.
- 🖥️ **Fully themed workbench.** Activity bar, sidebar, tabs, breadcrumbs, panels, suggest and hover widgets, peek view, merge conflicts, git decorations and the status bar all match.
- 💻 **Integrated terminal palette.** All 16 ANSI colours are tuned to fit the theme, so CLI output looks as good as your code.
- 🔍 **Readable search and selection.** Find matches, word highlights and selections are clearly visible without hiding the code underneath.

---

## 📸 Screenshots

### JavaScript, with the integrated terminal
![Royal Theme: JavaScript with the integrated terminal](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/screenshot-javascript.png)

### Python
![Royal Theme: Python](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/screenshot-python.png)

### TypeScript, with IntelliSense suggestions
![Royal Theme: TypeScript with the suggest widget](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/screenshot-typescript.png)

### HTML & CSS
![Royal Theme: HTML and CSS](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/screenshot-html.png)

### In the wild
<details>
<summary>The original screenshot from a real VS Code session</summary>

![Royal Theme in VS Code](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/example1.png)
</details>

---

## 🎨 Colour palette

![Royal Theme colour palette](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/images/palette.png)

| Role | Colour | Used for |
| --- | --- | --- |
| Accent | ![#FFC600](https://img.shields.io/badge/-%23FFC600-ffc600?style=flat-square) | Cursor, active tab and panel borders, badges, warnings, highlights |
| Editor background | ![#282C34](https://img.shields.io/badge/-%23282C34-282c34?style=flat-square) | Editor, terminal, title bar, activity bar |
| Sidebar background | ![#21252B](https://img.shields.io/badge/-%2321252B-21252b?style=flat-square) | Explorer, tab strip, widgets, hovers |
| Keywords | ![#C678DD](https://img.shields.io/badge/-%23C678DD-c678dd?style=flat-square) | `if`, `for`, `class`, `import`, `new` |
| Functions | ![#61AFEF](https://img.shields.io/badge/-%2361AFEF-61afef?style=flat-square) | Function and method names, links |
| Strings | ![#98C379](https://img.shields.io/badge/-%2398C379-98c379?style=flat-square) | String literals, inserted diff lines |
| Numbers & constants | ![#D19A66](https://img.shields.io/badge/-%23D19A66-d19a66?style=flat-square) | Numbers, booleans, CSS values |
| Types & classes | ![#E5C07B](https://img.shields.io/badge/-%23E5C07B-e5c07b?style=flat-square) | Class names, types, `self`, constants |
| Variables & tags | ![#E06C75](https://img.shields.io/badge/-%23E06C75-e06c75?style=flat-square) | Variables, object keys, HTML tags, deleted diff lines |
| Operators | ![#56B6C2](https://img.shields.io/badge/-%2356B6C2-56b6c2?style=flat-square) | Operators, CSS operators, DOM objects |

---

## 🚀 Installation

**From VS Code**

1. Open the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`).
2. Search for **Royal Theme** and click **Install**.
3. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme** and pick **Royal Theme**.

**From the command line**

```bash
code --install-extension alsharifs.royal-theme
```

**From the Marketplace**

Install it from the [Visual Studio Marketplace page](https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme).

**Activate it in `settings.json`**

```jsonc
{
  "workbench.colorTheme": "Royal Theme"
}
```

---

## ⚙️ Recommended settings

These are the settings used in the screenshots. Add any of them to your `settings.json` (**Preferences: Open User Settings (JSON)**):

```jsonc
{
  "workbench.colorTheme": "Royal Theme",

  // Editor
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.cursorBlinking": "expand",
  "editor.renderWhitespace": "boundary",
  "editor.suggestSelection": "first",
  "editor.formatOnSave": true,
  "breadcrumbs.enabled": true,

  // Terminal
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.defaultProfile.windows": "PowerShell",

  // Extras (only if you use these extensions)
  "code-runner.runInTerminal": true,
  "code-runner.clearPreviousOutput": true,
  "color-highlight.matchWords": true
}
```

---

## 🛠️ Customising the theme

You can tweak any colour without forking the theme by overriding it in `settings.json`:

```jsonc
{
  "workbench.colorCustomizations": {
    "[Royal Theme]": {
      "editorCursor.foreground": "#ff9d00",
      "statusBar.background": "#21252b"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Royal Theme]": {
      "comments": { "fontStyle": "italic" }
    }
  }
}
```

Every UI key is listed in the [VS Code Theme Color reference](https://code.visualstudio.com/api/references/theme-color).

---

## 📁 Project structure

```
Royal-Theme/
├── themes/
│   └── Royal Theme-color-theme.json   # all UI colours + syntax token rules
├── images/                            # README screenshots and banner
├── icon.png                           # Marketplace icon
├── package.json                       # extension manifest
└── CHANGELOG.md
```

## 🤝 Contributing

Found a language that doesn't look right, or a UI element that's missed? Issues and pull requests are welcome.

1. Fork the repo and open it in VS Code.
2. Press `F5` to start an **Extension Development Host** with the theme loaded.
3. Edit `themes/Royal Theme-color-theme.json`. Changes apply live in the host window.
4. Use **Developer: Inspect Editor Tokens and Scopes** to find the scope name for any piece of code.
5. Open a pull request with a before/after screenshot.

---

## 🔗 Links

- 🛒 [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme)
- 💻 [GitHub repository](https://github.com/Alsharifs/Royal-Theme)
- 🌐 [Website: iSayed.com](https://www.iSayed.com)
- 🐦 [Twitter: @SayedAlsharifs](https://twitter.com/SayedAlsharifs)

<p align="center">
  <br>
  <b>Enjoy!</b> If Royal Theme brightens your editor, please ⭐ the repo and leave a rating on the Marketplace.<br><br>
  Made with ♡ by <b>Sayed AlshaRif</b> 🇪🇬
</p>
