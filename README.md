# VS Code Extensions and Settings

This file contains a list of all VS Code extensions I currently use, as well as the settings configuration for optimizing my development environment. It serves as a reference for future use and for sharing with collaborators.

## Extensions

1. **Auto Close Tag**  
   Automatically adds HTML/XML close tags.

2. **Auto Complete Tag**  
   Helps with closing and renaming paired tags.

3. **Auto Rename Tag**  
   Renames paired HTML/XML tags automatically.

4. **Better Comments**  
   Improves code commenting with annotations (e.g., TODO, FIXME).

5. **Code Spell Checker**  
   Checks spelling in source code to avoid typos.

6. **Console Ninja**  
   Displays `console.log` output and runtime errors next to your code for better debugging.

7. **CSS Peek**  
   Allows peeking into CSS ID/class definitions directly from HTML files.

8. **Dracula Theme Official**  
   A dark theme for VS Code, providing a comfortable environment for long coding sessions.

9. **ES7+ React/Redux/React-Native Snippets**  
   Provides React, React Native, and Redux snippets in JavaScript/TypeScript with ES7+ syntax.

10. **ESLint**  
    Integrates ESLint into VS Code for linting JavaScript code, ensuring clean and consistent code.

11. **GitHub Copilot**  
    AI-powered coding assistant, which helps with writing code faster and more efficiently.

12. **GitHub Copilot Chat**  
    Chat feature powered by GitHub Copilot for interactive coding assistance.

13. **GitLens**  
    Enhances Git integration within VS Code, providing insights into version control, code history, and authorship.

14. **HTML to JSX**  
    Converts HTML code to React JSX, streamlining the transition between HTML and React.

15. **Image Preview**  
    Displays image previews in the gutter and on hover, making it easy to view images without opening them.

16. **Import Cost**  
    Displays the size of imported packages, helping you to optimize imports and reduce bundle size.

17. **Live Server**  
    Launches a local development server with live reload, providing a quick way to preview changes.

18. **Material Icon Theme**  
    Provides Material Design icons for files and folders, improving the look and feel of the file explorer.

19. **Next.js React/ES7+/React-Native Snippets**  
    Snippets for Next.js, React, and Redux, making it faster to write React code.

20. **Path Autocomplete**  
    Provides path completion for files and folders, making it easier to navigate and import files.

21. **Path Intellisense**  
    Autocompletes file paths as you type, reducing manual errors when referencing files in the code.

22. **Power Mode**  
    Adds visual effects and animations to the editor, inspired by the "Code in the Dark" challenge.

23. **Prettier - Code Formatter**  
    Formats code using Prettier, ensuring code is always clean and consistent.

24. **Tailwind CSS Intellisense**  
    Provides intelligent tooling for Tailwind CSS, including class name completion and documentation.

25. **Tailwind Fold**  
    Improves readability by folding long Tailwind class attributes, making your code cleaner and easier to maintain.

26. **Turbo Console Log**  
    Automates the insertion of meaningful `console.log` messages, saving time on debugging.

---

## VS Code Settings (`settings.json`)

```json
{
  "editor.fontSize": 19,
  "editor.fontFamily": "Fira Code, Operator Mono",
  "editor.fontLigatures": true,
  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.tslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnType": true,
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnType": true,
    "editor.formatOnSave": true
  },
  "terminal.integrated.fontSize": 16,
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.fontFamily": "Fira Code, Operator Mono",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorCustomizations": {
    "terminal.background": "#282A36",
    "terminal.foreground": "#F8F8F2",
    "terminalCursor.background": "#50FA7B",
    "terminalCursor.foreground": "#50FA7B",
    "terminal.ansiBlack": "#21222C",
    "terminal.ansiBlue": "#6272A4",
    "terminal.ansiBrightBlack": "#6272A4",
    "terminal.ansiBrightBlue": "#8BE9FD",
    "terminal.ansiBrightCyan": "#8BE9FD",
    "terminal.ansiBrightGreen": "#50FA7B",
    "terminal.ansiBrightMagenta": "#FF79C6",
    "terminal.ansiBrightRed": "#FF5555",
    "terminal.ansiBrightWhite": "#F8F8F2",
    "terminal.ansiBrightYellow": "#F1FA8C",
    "terminal.ansiCyan": "#8BE9FD",
    "terminal.ansiGreen": "#50FA7B",
    "terminal.ansiMagenta": "#BD93F9",
    "terminal.ansiRed": "#FF5555",
    "terminal.ansiWhite": "#F8F8F2",
    "terminal.ansiYellow": "#F1FA8C"
  },
  "files.autoSave": "onFocusChange",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "files.exclude": {
    "**/node_modules": true
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.startupEditor": "none",
  "workbench.list.openMode": "singleClick",
  "tailwind-fold.autoFold": true,
  "tailwind-fold.foldStyle": "QUOTES",
  "tailwind-fold.showTailwindImage": false
}
