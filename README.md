# configs
>Personal settings for Git Bash for Windows, Windows Terminal, VS Code, Visual Studio

## Setup
### Git Bash for Windows
#### git-prompt.sh
>Default Bash prompt
- Paste [git-prompt.sh](/git-prompt.sh) to ```C:\Program Files\Git\etc\profile.d``` and overwrite <br>
    ```git-prompt.sh``` in that directory (make a backup of the git-prompt.sh that's in there)

#### gitconfig
>Aliases for using Git
- Paste [gitconfig](/gitconfig) to bottom of ```gitconfig``` located at ```C:\Program Files\Git\etc```

#### bash.bashrc
>Aliases for non-Git related commands (and backup of .bashrc) 
- Paste [bash.bashrc](/bash.bashrc) ```#Aliases``` section to bottom of ```bash.bashrc``` located at <br>
    ```C:\Program Files\Git\etc```

### Windows Terminal
>Displays correct Windows Terminal themes and menu options
- If Git Bash flashes white when backspacing, go to ```C:\Program Files\Git\etc\inputrc``` and change <br>
    ```set bell-style visible``` to ```set bell-style none```
- Paste ```settings.JSON``` from [settings.json](/settings.JSON) over local ```settings.JSON```

### VS Code
#### Extensions to get
- Themes: One Dark Pro, Solarized Espresso Soda
- Bracket Pair Colorizer 2
- Code Spell Checker
- C#

### Visual Studio
- Theme: One Dark Pro
- Visual Studio Spell Checker
- .gitignore file. Run following code from any Git Bash window

    ```
    echo "dnignore() {
        curl -L -s 'https://raw.githubusercontent.com/github/gitignore/master/VisualStudio.gitignore' > .gitignore
    }" >> ~/.bashrc
    ```
    Running ```dnignore``` will generate a .gitignore specific to Visual Studio