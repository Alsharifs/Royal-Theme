<p align="center">
  <img src="https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/banner.png" alt="Royal Theme Blue for Visual Studio Code" width="100%">
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme-blue"><img src="https://img.shields.io/visual-studio-marketplace/v/alsharifs.royal-theme-blue?style=for-the-badge&label=Marketplace&color=ffc600&labelColor=15232d&logo=visualstudiocode&logoColor=white" alt="Marketplace version"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme-blue"><img src="https://img.shields.io/visual-studio-marketplace/i/alsharifs.royal-theme-blue?style=for-the-badge&color=61afef&labelColor=15232d" alt="Installs"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme-blue&ssr=false#review-details"><img src="https://img.shields.io/visual-studio-marketplace/r/alsharifs.royal-theme-blue?style=for-the-badge&color=98c379&labelColor=15232d" alt="Rating"></a>
  <a href="https://github.com/Alsharifs/Royal-Theme/stargazers"><img src="https://img.shields.io/github/stars/Alsharifs/Royal-Theme?style=for-the-badge&color=c678dd&labelColor=15232d&logo=github" alt="GitHub stars"></a>
</p>

<p align="center">
  <b>A deep cobalt-blue dark theme for Visual Studio Code, crowned with royal gold.</b><br>
  The blue sibling of <a href="https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme">Royal Theme</a>, customised across <b>219 UI colours</b> and <b>259 syntax rules</b>.
</p>

---

## ✨ Highlights

- 🌊 **Deep cobalt workbench.** A `#193549` editor with layered navy panels (`#15232D` sidebar, `#122738` tabs and terminal) that feel calm and focused.
- 👑 **Royal gold accents.** The cursor, active tab, panel border, badges, git changes and suggestion highlights all glow in `#FFC600` gold against the blue.
- 🎨 **Extra-vivid syntax.** Atom One Dark's purple, blue, green and rose, plus Blue-only touches: gold control flow, mint-green declarations, lime method calls, sky-blue HTML tags and soft indigo comments.
- 🧩 **Language-aware highlighting.** Hand-tuned scopes for **JavaScript / TypeScript, Python, HTML, CSS / SCSS / Less, JSON, Java, C / C++, Rust, Go, Markdown, regex, diffs** and more.
- 🖥️ **Fully themed UI.** Activity bar, sidebar, tabs, breadcrumbs, panels, suggest and hover widgets, peek view, debug toolbar, charts and the status bar all match.
- 💻 **Integrated terminal palette.** ANSI colours tuned for the blue background, so CLI output stays readable.

---

## 📸 Screenshots

### JavaScript, with the integrated terminal
![Royal Theme Blue: JavaScript with the integrated terminal](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/screenshot-javascript.png)

### Python
![Royal Theme Blue: Python](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/screenshot-python.png)

### TypeScript, with IntelliSense suggestions
![Royal Theme Blue: TypeScript with the suggest widget](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/screenshot-typescript.png)

### HTML & CSS
![Royal Theme Blue: HTML and CSS](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/screenshot-html.png)

---

## 🎨 Colour palette

![Royal Theme Blue colour palette](https://raw.githubusercontent.com/Alsharifs/Royal-Theme/main/royal-theme-blue/images/palette.png)

| Role | Colour | Used for |
| --- | --- | --- |
| Accent | ![#FFC600](https://img.shields.io/badge/-%23FFC600-ffc600?style=flat-square) | Cursor, active tab and panel borders, badges, highlights |
| Editor background | ![#193549](https://img.shields.io/badge/-%23193549-193549?style=flat-square) | Editor, active tab |
| Sidebar background | ![#15232D](https://img.shields.io/badge/-%2315232D-15232d?style=flat-square) | Explorer, title bar, status bar, widgets |
| Tabs & terminal | ![#122738](https://img.shields.io/badge/-%23122738-122738?style=flat-square) | Activity bar, tab strip, terminal |
| Keywords | ![#C678DD](https://img.shields.io/badge/-%23C678DD-c678dd?style=flat-square) | `import`, `class`, `export`, `interface` |
| Declarations | ![#0AE9A6](https://img.shields.io/badge/-%230AE9A6-0ae9a6?style=flat-square) | `const`, `constructor` |
| Control flow | ![#FFBB00](https://img.shields.io/badge/-%23FFBB00-ffbb00?style=flat-square) | `if`, `for`, `return`, `await` |
| Method calls | ![#C4CE41](https://img.shields.io/badge/-%23C4CE41-c4ce41?style=flat-square) | `.addEventListener()`, `.clear()` |
| Strings | ![#98C379](https://img.shields.io/badge/-%2398C379-98c379?style=flat-square) | String literals |
| Types & constants | ![#E5C07B](https://img.shields.io/badge/-%23E5C07B-e5c07b?style=flat-square) | Class names, types, `this`, constants |
| Variables | ![#E06C75](https://img.shields.io/badge/-%23E06C75-e06c75?style=flat-square) | Variables, private fields, object keys |
| HTML tags | ![#81B7DB](https://img.shields.io/badge/-%2381B7DB-81b7db?style=flat-square) | `<section>`, `<head>`, `<body>` |
| Comments | ![#6270A0](https://img.shields.io/badge/-%236270A0-6270a0?style=flat-square) | Line, block and HTML comments |
| Numbers | ![#D3BDA3](https://img.shields.io/badge/-%23D3BDA3-d3bda3?style=flat-square) | Numeric literals |

<details>
<summary>Full colour base used to build the theme</summary>

```
#DA52ECD7  pink
#0AE9A6DA  new green
#3FC3CFB9  new blue
#81B7DB    soft blue
#C4CE41D3  soft yellow
#D19A66    soft brown
#E06C75    soft rose
#FFBB00    gold for conditions
#DBF5E4CC  semi-white for normal variables
#98C379    very soft green for quotes
#E5C07B    new yellow
#C9710C    dark brown
#3BCF47    light green
#2C88D3    light blue
#FBFF16BD  light yellow
#F02121FA  red, only for invalid code
#6270A0    comments
#DBB88D    operators
#D3BDA3    numbers
#FEC4D2    new colour 1
#9FEDD4    new colour 2
```
</details>

---

## 🚀 Installation

**From VS Code**

1. Open the **Extensions** view (`Ctrl+Shift+X` / `Cmd+Shift+X`).
2. Search for **Royal Theme blue** and click **Install**.
3. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme** and pick **Royal Theme blue**.

**From the command line**

```bash
code --install-extension alsharifs.royal-theme-blue
```

**From the Marketplace**

Install it from the [Visual Studio Marketplace page](https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme-blue).

**Activate it in `settings.json`**

```jsonc
{
  "workbench.colorTheme": "Royal Theme blue"
}
```

---

## ⚙️ Recommended settings

These are the settings used in the screenshots. Add any of them to your `settings.json` (**Preferences: Open User Settings (JSON)**):

```jsonc
{
  "workbench.colorTheme": "Royal Theme blue",
  "workbench.iconTheme": "vscode-icons",

  // Editor
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.cursorBlinking": "expand",
  "editor.renderWhitespace": "boundary",
  "editor.suggestSelection": "first",
  "editor.formatOnSave": true,
  "editor.minimap.enabled": false,
  "breadcrumbs.enabled": true,

  // Built-in bracket pair colours that suit the theme
  "editor.bracketPairColorization.enabled": true,
  "workbench.colorCustomizations": {
    "[Royal Theme blue]": {
      "editorBracketHighlight.foreground1": "#FFD700",
      "editorBracketHighlight.foreground2": "#DA70D6",
      "editorBracketHighlight.foreground3": "#87CEFA"
    }
  },

  // Prettier as the default formatter
  "[javascript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[jsonc]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[html]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },

  // Terminal
  "terminal.integrated.cursorBlinking": true
}
```

> The gold / orchid / sky-blue bracket colours replace the older *Bracket Pair Colorizer* extension settings. VS Code now colours brackets natively.

---

## 🛠️ Customising the theme

You can tweak any colour without forking the theme by overriding it in `settings.json`:

```jsonc
{
  "workbench.colorCustomizations": {
    "[Royal Theme blue]": {
      "editor.background": "#1b3a50",
      "editorCursor.foreground": "#ff9d00"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Royal Theme blue]": {
      "comments": { "fontStyle": "italic" }
    }
  }
}
```

Every UI key is listed in the [VS Code Theme Color reference](https://code.visualstudio.com/api/references/theme-color).

---

## 🤝 Contributing

Issues and pull requests are welcome in the [Royal-Theme repository](https://github.com/Alsharifs/Royal-Theme). The Blue variant lives in the [`royal-theme-blue/`](https://github.com/Alsharifs/Royal-Theme/tree/main/royal-theme-blue) folder.

1. Open the `royal-theme-blue` folder in VS Code and press `F5` to launch an **Extension Development Host**.
2. Edit `themes/Royal Theme Blue-color-theme.json`. Changes apply live.
3. Use **Developer: Inspect Editor Tokens and Scopes** to find the scope of any piece of code.
4. Open a pull request with a before/after screenshot.

---

## 👑 Also by me

Prefer the classic look? Try **[Royal Theme](https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme)**, the gold-accented Atom One Dark original.

## 🔗 Links

- 🛒 [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=alsharifs.royal-theme-blue)
- 💻 [GitHub repository](https://github.com/Alsharifs/Royal-Theme/tree/main/royal-theme-blue)
- 🌐 [Website: iSayed.com](https://www.iSayed.com)
- 🐦 [Twitter: @SayedAlsharifs](https://twitter.com/SayedAlsharifs)

<p align="center">
  <br>
  <b>Enjoy!</b> If Royal Theme Blue brightens your editor, please ⭐ the repo and leave a rating on the Marketplace.<br><br>
  Copyright © <a href="https://www.iSayed.com">Sayed AlshaRif</a> 🇪🇬
</p>
