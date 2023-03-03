# Install iTerm2

To install, run:

    brew install --cask iterm2

## Install Git
If you don't have it installed, install git as well:

    brew install git

## Install Oh My Zsh
Run this to install Oh My Zsh:

    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

### Install PowerLevel10K Theme for Oh My Zsh
Run this to install PowerLevel10K:

    git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

Now that it's installed, open the "~/.zshrc" file with your preferred editor (i'm using nano) and change the value of "ZSH_THEME" as shown below:

    ZSH_THEME="powerlevel10k/powerlevel10k"

To reflect this change directly on your terminal, restart it or run this command:

    source ~/.zshrc

### Install Meslo Nerd Font
Install the font by pressing "y" and then quit iTerm2.

### Configure PowerLevel10K
Restart iTerm2. You should now be seeing the PowerLevel10K configuration process. If you don't, run the following:

    p10k configure

Follow the instructions for the PowerLevel10K configuration to make your terminal look as desired.

### Change iTerm2 Colors to My Custom Theme
Open iTerm2
Download my color profile by running the following command (will be added to Downloads folder):

    curl https://raw.githubusercontent.com/erwinbierens/macOS-environment/main/iTerm2/coolnight.itermcolors --output ~/Downloads/coolnight.itermcolors

Open iTerm2 preferences
Go to Profiles > Colors
Import the downloaded color profile (coolnight)
Select the color profile (coolnight)