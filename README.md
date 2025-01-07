# 🛠 VS Code Settings

Personal VS Code setup and configuration notes.

## 🎨 Font Setup

Using JetBrains Mono:

1. Download from [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
2. Install locations:
   - Mac: `/Library/Fonts/`
   - Windows: `C:\Windows\Fonts\`
   - Linux: `~/.local/share/fonts/`

## ⚡️ Common Settings

```json
{
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontSize": 14,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "files.autoSave": "afterDelay",
  "terminal.integrated.fontSize": 14
}
```

## 🔧 Troubleshooting

- Font not showing → Restart VS Code
- Extension conflicts → Start with `--disable-extensions`

## 📝 Notes

- `.vscode/settings.json` - Project-specific settings
- `.vscode/extensions.json` - Recommended extensions
