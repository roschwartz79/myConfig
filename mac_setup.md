# Rob's Mac Setup

1. System Preferences
    * Mouse
        * Scroll direction: *Natural*
        * Secondary Click: *Right side*
        * Smart Zoom: *Double Tap 1 finger*
    * Displays
        * Configure for monitors
        * Currently configured for 1 and 2 monitors
    * Dock
        * No magnification
        * Uncheck automatically hide and show dock

2. Install the following:
    * [iterm2](https://iterm2.com/) 
    * [JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/)
    * [Homebrew](https://brew.sh/)
        * `brew update`
        * `brew install git` and setup [git](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
        * `brew install jq`
        * `brew installl kafkacat`
        * `brew cask install rectangle`
    * [Python 3](https://www.python.org/downloads/)
        * `sudo pip3 install --upgrade pip`
    * [sdkman](https://sdkman.io/)
        * Install the latest versions of
            * Gradle 
            * Maven
            * Java
    * [ohmyzsh](https://ohmyz.sh/)
    * [Powerlevel10k](https://github.com/romkatv/powerlevel10k)
        * use `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k`
        * Then, `p10k configure`, this will create the `~/.p10k.zsh` file based on preferences chosen!
    * [Docker](https://hub.docker.com/editions/community/docker-ce-desktop-mac/)
    * [Insomnia](https://insomnia.rest/download/)
    
    
