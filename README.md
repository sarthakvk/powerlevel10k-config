# powerlevel10k
### These are my configurations of powerlevel10k with oh my zsh and GNOME terminal
- **This is how my terminal looks**
<img src="terminal.png">

## Installation

1. Install zsh and setup as default shell
    - `sudo apt install zsh`
    - `chsh -s /bin/zsh`
    - for detailed instructions <a href="https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH">go here</a>
    - you also have to set your PATH from previous shell
        - copy export paths from previous shell config file and add it to **.zshrc** in your home directory
2. Install oh my zsh
    - oh my zsh can be installed <a href="https://github.com/ohmyzsh/ohmyzsh#basic-installation">from here</a>
  
3. Install powerlevel10k
    - follow oh my zsh installation instructions <a href="https://github.com/romkatv/powerlevel10k#installation">from here</a>

4. Download these fonts and install them
   
   - <a href="https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Regular.ttf">MesloLGS NF Regular.ttf</a>
   - <a href="https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold.ttf">MesloLGS NF Bold.ttf</a>
   - <a href="https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Italic.ttf">MesloLGS NF Italic.ttf</a>
   - <a href="https://github.com/romkatv/powerlevel10k-media/raw/master/MesloLGS%20NF%20Bold%20Italic.ttf">MesloLGS NF Bold Italic.ttf</a>
5. Set custom font in terminal
  - Open your __Terminal Preferences__ in *Profile Section* go to the *Text Tab* check the *Custom Font*
  - Select `MesloLGS NF Regular font`
6. Configure powerlevel10k
  - For your own costomizations
    - run `p10k configure` it will take care for the rest of steps
  - For my costomizations
    - clone this repo and replace **.zshrc** and **.p10k.zsh** from your home directory with these
7. Install colorls
    - run `sudo apt install colorls`
    - open **.zshrc** and add this at the end
        > `alias lc="colorls -sd"`
    - test this by typing `lc` in your terminal
        
7. Changing customizations
      - Edit the **.zshrc** and **.p10k.zsh** (*RISKY*)
      - run `p10k configure` (*SAFE*)
## How to ask for help
- The best way to ask for help is to open an issue.
