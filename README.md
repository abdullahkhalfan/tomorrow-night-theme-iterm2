# Tomorrow Night Theme for Iterm2

## Background

As a dark mode user, I struggled to find a theme for VS Code that would not only offer great readability but also be easy on my eyes even after hours of work. That was until I tried [Tomorrow Night](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-TomorrowKit). I loved it so much that I modified my iTerm2 theme to match its desaturated colors. So feel free to do the same!

## Set Terminal Colors in VS Code

Unfortunately, at the present time, the [Tomorrow Night](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-TomorrowKit) theme does not set any colors for the terminal in VS Code. So you may place these settings in your **settings.json** to also make it match:

```
"workbench.colorCustomizations": {
    "terminal.ansiBlack": "#000000",
    "terminal.ansiBlue": "#8abeb7",
    "terminal.ansiBrightBlack": "#969896",
    "terminal.ansiBrightBlue": "#8abeb7",
    "terminal.ansiBrightCyan": "#8abeb7",
    "terminal.ansiBrightGreen": "#b5bd68",
    "terminal.ansiBrightMagenta": "#b294bb",
    "terminal.ansiBrightRed": "#cc6666",
    "terminal.ansiBrightWhite": "#ffffff",
    "terminal.ansiBrightYellow": "#f0c674",
    "terminal.ansiCyan": "#8abeb7",
    "terminal.ansiGreen": "#b5bd68",
    "terminal.ansiMagenta": "#b294bb",
    "terminal.ansiRed": "#cc6666",
    "terminal.ansiWhite": "#c5c8c6",
    "terminal.ansiYellow": "#f0c674",
    "terminal.foreground": "#c5c8c6",
    "terminal.selectionBackground": "#373b41"
},
```
