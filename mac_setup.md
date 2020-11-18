# Rob's Mac Setup

1. Clone this repo `git clone git@github.com:roschwartz79/myConfig.git`
    * If there are issues, setup an ssh key. [Instructions](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key)
2. System Preferences
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

3. Install the following:
    * [iterm2](https://iterm2.com/) 
        * Set theme to "Dark (High Contrast)"
        * Preferences (⌘,) -> Profiles -> Other Actions -> Import JSON Profiles
        * Select the Profile.json that is included in this repo
        * ⌘D then ⌘⇧D, then assign each window to the appropriate profile
        * ⌘⇧S to save a custom window arrangement, name as `Main Arrangement`
        * Preferences (⌘,) -> Keys
            * Click into the shortcut and use ⌘⇧w, set action to "Select Menu Item"
            * Look for "Window" category, then subcategory named "Restore Window Arrangement"
        * Additional information [here](https://blog.andrewray.me/how-to-create-custom-iterm2-window-arrangments/)
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
    
    
