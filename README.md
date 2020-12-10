# configs
>Personal settings for Git Bash for Windows, Windows Terminal, VS Code, Visual Studio

## Setup
### Git Bash for Windows
#### git-prompt.sh
- Default Bash prompt
- Paste ```git-prompt.sh``` file from [git-prompt.sh](/git-prompt.sh) to ```C:\Program Files\Git\etc\profile.d``` and overwrite <br>
    ```git-prompt.sh``` in that directory (make a backup of the git-prompt.sh that's in there)

#### gitconfig
- Aliases for using Git
- Paste ```gitconfig``` content from [gitconfig](/gitconfig) to bottom of ```gitconfig``` located at ```C:\Program Files\Git\etc```

#### bash.bashrc
- Aliases for non-Git related commands (and backup of .bashrc) 
- Paste from ```bash.bashrc``` at [bash.bashrc](/bash.bashrc) ```#Aliases``` section down into ```bash.bashrc``` located at <br>
    ```C:\Program Files\Git\etc```

### Windows Terminal
- Displays correct Windows Terminal themes and menu options
- If Git Bash flashes white when backspacing, go to ```C:\Program Files\Git\etc\inputrc``` and change <br>
    ```set bell-style visible``` to ```set bell-style none```
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