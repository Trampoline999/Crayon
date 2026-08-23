# Crayon Theme

A modern, vibrant, and eye-comforting dark theme for Visual Studio Code.

---

## 📸 Screenshots

### JavaScript
![JavaScript Preview](screenshot/javascript.png)

### Java
![Java Preview](screenshot/java.png)

### React
![React Preview](screenshot/react.png)

### Python
![Python Preview](screenshot/python.png)

### C++
![C++ Preview](screenshot/c++.png)

---

## ✨ Recommended Settings

For the best visual experience matching the screenshots, add the following configuration to your VS Code `settings.json`:

```json
{
  "editor.fontSize": 13.5,
  "editor.lineHeight": 25,
  "editor.fontLigatures": true,
  "editor.fontFamily": "'MonoLisaCode', 'JetBrains Mono', 'Fira Code', 'Cascadia Code', Menlo, Consolas, monospace",
  "editor.fontWeight": "normal"
}
```

---

## 🚀 Usage / Installation

### Method 1: Local Development / Testing
1. Press `F5` in VS Code to launch an Extension Development Host window with this theme loaded.
2. Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows/Linux).
3. Type **Preferences: Color Theme** and select **Crayon**.

### Method 2: Install Locally in VS Code
Copy or symlink this folder to your VS Code extensions directory:
- **macOS / Linux**: `~/.vscode/extensions/crayon-theme`
- **Windows**: `%USERPROFILE%\.vscode\extensions\crayon-theme`

```bash
# Example on macOS:
cp -r "/Users/onkarchougule/Desktop/Dark Theme" ~/.vscode/extensions/crayon-theme
```
Restart VS Code, then select **Crayon** from your Color Themes list.

### Method 3: Package as VSIX
If you have `@vscode/vsce` installed:
```bash
npx @vscode/vsce package
```
Then install the generated `.vsix` file in VS Code (`Extensions` > `...` > `Install from VSIX...`).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).


