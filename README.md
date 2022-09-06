# macOS-dotfiles
Dotfiles for MacOS to mimic i3 on Linux

## Notes

Add execute permissions to`.yabairc`

```
chmod +x ~/.yabairc
brew services start yabai
brew services start skhd
brew services start spacebar
```

Use the ansible role [dotfiles-role](https://github.com/sergio-munoz/dotfiles/tree/main/dotfiles-role) to install your dotfiles automatically.
