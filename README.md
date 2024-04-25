# Tailoring macOS for my use: Personalized Commands and Tips

1. Set [TextEdit](https://support.apple.com/en-in/guide/textedit/welcome/mac) app to open a blank page by default instead of the file selection window. Quit the TextEdit app, restart it after this command:

```
defaults write com.apple.TextEdit NSShowAppCentricOpenPanelInsteadOfUntitledFile -bool false
```