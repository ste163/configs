# configs
>Getting setup with my personal settings for Git Bash for Windows, Windows Terminal, VS Code, Visual Studio

## Setup
### Git Bash for Windows
#### git-prompt.sh
- Displays correct default prompt
- Paste ```git-prompt.sh``` file from [git-prompt.sh](/git-prompt.sh) to ```C:\Program Files\Git\etc\profile.d``` and overwrite ```git-prompt.sh``` in that directory (make a backup of the git-prompt.sh that's in there)

#### gitconfig
- Setups up all the correct aliases for using Git
- Paste ```gitconfig``` content from [gitconfig](/gitconfig) to bottom of ```gitconfig``` located at ```C:\Program Files\Git\etc```

#### bash.bashrc
- Setups aliases
- Paste from ```bash.bashrc``` at [bash.bashrc](/bash.bashrc) ```#Aliases``` section down into ```bash.bashrc``` located at ```C:\Program Files\Git\etc```

### Windows Terminal
- Displays correct Windows Terminal themes and menu options
- Paste ```settings.JSON``` from /settings.JSON(LINK) over locale ```settings.JSON``` (may bug-out if there is no Ubuntu installed. So it might be best to pick and choose what options are best to copy over)

### VS Code
#### Extensions to get
- Theme: One Dark Pro
- Bracket Pair Colorizer 2
- Code Spell Checker
- C#

### Visual Studio
- Theme: One Dark Pro
- Visual Studio Spell Checker