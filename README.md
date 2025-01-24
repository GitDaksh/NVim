# Neovim Configuration for 2024

Welcome to my Neovim configuration repository! This setup is designed to transform Neovim into a powerful, modern code editor tailored for web development and beyond. Inspired by the latest tools and plugins, this configuration is optimized for productivity, aesthetics, and functionality. Below is a concise overview of the setup and its features.

---

## 🚀 **Features**

This Neovim configuration includes:

- **Plugin Management**: Powered by `lazy.nvim`, a fast and efficient plugin manager.
- **File Explorer**: Enhanced with `nvim-tree.lua` for a modern file navigation experience.
- **Fuzzy Finder**: `telescope.nvim` for seamless file and text searching.
- **Syntax Highlighting**: `tree-sitter` for advanced syntax parsing and highlighting.
- **LSP Support**: Integrated with `mason.nvim` for easy installation of language servers.
- **Auto-Completion**: `nvim-cmp` with snippets, LSP integration, and VS Code-like icons.
- **Git Integration**: `gitsigns.nvim` and `lazygit.nvim` for version control within Neovim.
- **Formatting & Linting**: `conform.nvim` and `nvim-lint` for code formatting and linting.
- **UI Enhancements**: Beautiful status lines with `lualine.nvim`, tabs with `bufferline.nvim`, and a sleek dashboard with `alpha.nvim`.
- **Custom Keymaps**: Intuitive keybindings for navigation, splits, tabs, and more.
- **Session Management**: `auto-session.nvim` for restoring your workspace effortlessly.

---

## 🛠️ **Setup Instructions**

### **Prerequisites**
1. **Neovim**: Ensure you have Neovim (v0.9.5 or higher) installed.
2. **Homebrew**: For macOS/Linux, install dependencies like `ripgrep`, `node`, and `nerd fonts`.
3. **Git**: Required for plugin management and version control.

### **Installation**
1. Clone this repository into your Neovim config directory:
   ```bash
   git clone https://github.com/your-username/neovim-config.git ~/.config/nvim
   ```
2. Open Neovim:
   ```bash
   nvim
   ```
3. Wait for `lazy.nvim` to automatically install all plugins.

---

## 🧩 **Plugin Highlights**

### **Core Plugins**
- **`lazy.nvim`**: Plugin manager for lazy-loading and efficient setup.
- **`nvim-tree.lua`**: File explorer with icons and Git integration.
- **`telescope.nvim`**: Fuzzy finder for files, text, and more.
- **`tree-sitter`**: Advanced syntax highlighting and parsing.
- **`mason.nvim`**: Easy installation of LSP servers, linters, and formatters.
- **`nvim-cmp`**: Auto-completion with LSP, snippets, and VS Code-like icons.
- **`lualine.nvim`**: Customizable status line.
- **`bufferline.nvim`**: Enhanced tab management.

### **Git Integration**
- **`gitsigns.nvim`**: Git status in the gutter (added, modified, deleted lines).
- **`lazygit.nvim`**: Terminal UI for Git commands.

### **Formatting & Linting**
- **`conform.nvim`**: Auto-formatting with Prettier, Black, and more.
- **`nvim-lint`**: Linting with ESLint, Pylint, etc.

### **UI Enhancements**
- **`alpha.nvim`**: A sleek dashboard for Neovim.
- **`tokyonight.nvim`**: A beautiful color scheme.
- **`indent-blankline.nvim`**: Visual indentation guides.

---

## 🎨 **Custom Keymaps**

Here are some of the keybindings to supercharge your workflow:

| Keybinding          | Action                                   |
|---------------------|------------------------------------------|
| `<Leader>e`         | Toggle file explorer (`nvim-tree`)       |
| `<Leader>ff`        | Find files (`telescope`)                 |
| `<Leader>fg`        | Live grep (`telescope`)                  |
| `<Leader>fr`        | Recent files (`telescope`)               |
| `<Leader>fs`        | Search string in project (`telescope`)   |
| `<Leader>gs`        | Stage Git hunk (`gitsigns`)              |
| `<Leader>gu`        | Undo Git hunk (`gitsigns`)               |
| `<Leader>gd`        | Open Git diff (`gitsigns`)               |
| `<Leader>lg`        | Open lazygit (`lazygit.nvim`)            |
| `<Leader>ca`        | Code actions (LSP)                       |
| `<Leader>rn`        | Rename symbol (LSP)                      |
| `<Leader>gd`        | Go to definition (LSP)                   |
| `<Leader>gr`        | Go to references (LSP)                   |
| `<Leader>mp`        | Format file (`conform.nvim`)             |
| `<Leader>xx`        | Open trouble.nvim for diagnostics        |

---

## 🖥️ **File Structure**

The configuration is organized as follows:

```
~/.config/nvim/
├── init.lua              # Main entry point
├── lua/
│   ├── core/             # Core settings (options, keymaps)
│   ├── plugins/          # Plugin configurations
│   └── lsp/              # LSP configurations
└── README.md             # This file
```

---

## 🌟 **Why This Setup?**

This configuration is designed to:
- Be **highly customizable** for different workflows.
- Provide a **modern IDE-like experience** in Neovim.
- Optimize **performance** with lazy-loading plugins.
- Support **web development** and other programming languages.

---

## 📚 **Resources**
- [Neovim Documentation](https://neovim.io/doc/)
- [Lazy.nvim Documentation](https://github.com/folke/lazy.nvim)
- [Mason.nvim Documentation](https://github.com/williamboman/mason.nvim)
- [Telescope.nvim Documentation](https://github.com/nvim-telescope/telescope.nvim)

---

## 🙏 **Credits**
This configuration was inspired by the video: [How I Setup Neovim To Make It AMAZING In 2024 | Complete Guide](https://www.youtube.com/watch?v=6pAG3BHurdM). Special thanks to the creator for the detailed walkthrough.

---

Enjoy your new Neovim setup! If you have any questions or suggestions, feel free to open an issue or reach out. Happy coding! 🚀

---

**Made with ❤️ by [Daksh]**  
**GitHub**: [GitDaksh](https://github.com/GitDaksh) 
