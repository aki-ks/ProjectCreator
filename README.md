# Project Creator

This is a project by Ruben Hönle for automating the creation of projects with a associated GitHub Repository.

Only for Mac OS acutally.

# Instructions

To use this project, you have to install the GitHub CLI with the command _brew install gh_

Note: For this command you have to install Homebrew first.

For more information see: https://cli.github.com

# Setup GitHub CLI

_gh auth login_
Choose the Account type you want to login, normally this is _GitHub.com_
Then choose an authentication option, I would recommend to choose the _Login with web browser option_. Then just follow the given steps.

Warning: Don't close the tab of your Browser unless the setup is finished :)

After that choose your default git protocol (SSH or HTTPS). I choosed HTTPS, then the setup was finished.

# Setup

To run the Script with a individual command (I use _create_) from everywhere in the console you have to do following steps:
Step 1: _vim ~/.zshrc_
Step 2: _alias create=/Users/Ruben/Coding/Projects/ProjectCreator/create_
