# iTerm2


## config

```bash
# 设置 preferences 目录
defaults write com.googlecode.iterm2 PrefsCustomFolder -string "~/.dotfiles/iTerm/settings"

# 设置 iTerm2 使用用户指定的 preferences 目录
defaults write com.googlecode.iterm2 LoadPrefsFromCustomFolder -bool true
```

## 导出config

`Commond + ,` 打开preferences窗口 , 点击 `preferences` 页
勾选 `load preferences from a custom folder or URL` , 选择目录
