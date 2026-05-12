# My Dotfiles

这是我的个人配置文件仓库，收集了我在各种工具和环境中使用的配置，涵盖终端、编辑器、Shell、WSL 和 macOS 工具等。

## 内容

| 目录 | 说明 |
|------|------|
| **ghostty** | Ghostty 终端模拟器配置 |
| **starship** | Starship 命令行提示符配置 |
| **vim** | Vim 编辑器配置 |
| **zsh** | Zsh Shell 配置 |
| **wslconfig** | WSL2 配置文件 |

## 使用方式

1. 克隆仓库：

   ```bash
   git clone git@github.com:chiperman/my-dotfiles.git
   ```

2. 按需将配置文件复制到对应位置，或软链过去：

   ```bash
   ln -s ~/my-dotfiles/ghostty/config ~/.config/ghostty/config
   ln -s ~/my-dotfiles/starship/starship.toml ~/.config/starship.toml
   ln -s ~/my-dotfiles/zsh/.zshrc ~/.zshrc
   ln -s ~/my-dotfiles/vim/.vimrc ~/.vimrc
   ```

3. 详细配置说明可参考我的 Notion: [WSL2 Setup](https://chiperman.notion.site/chiperman/WSL2-Setup-5301e01262a745fdb70660a370136daf)
