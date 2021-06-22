# Victor's configuration

## Install homebrew

First and foremost, install `brew`. Find the instructions here: https://brew.sh/

## Applications to download

### The following apps can be downloaded with brew

- [Chrome](https://www.google.com/chrome/)
- [Jiggler](https://www.sticksoftware.com/software/Jiggler.html). Prevents Mac from locking.
- [Spectacle](https://www.spectacleapp.com/). Helps with window management through keyboard shortcuts.
- [Dozer](https://github.com/Mortennn/Dozer). Helps hide useless menu bar icons.
- [Visual studio code](https://code.visualstudio.com/download). Code development.
- [Azure data studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-2017). SQL development (MSSQL and PostgreSQL)
- [RescueTime](https://www.rescuetime.com/download_mac)
- [Docker](https://docs.docker.com/docker-for-mac/install/)
- [Loom](https://www.loom.com/download)
- [Zoom](https://zoom.us/download)
- [Postman](https://www.postman.com/downloads/)
- [Tandem](https://tandem.chat/welcome/download)
- [Acrobat Reader DC](https://get.adobe.com/reader/otherversions/)
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install). Used to manage GCP resources.

Install all of the above with the following command:

```sh
brew install --cask google-chrome jiggler spectacle dozer visual-studio-code azure-data-studio rescuetime docker loom zoom postman tandem adobe-acrobat-reader google-cloud-sdk
```

Other apps to install that do not use `--cask`:

- [Git](https://git-scm.com/). Source Code control.
- [nvm](https://github.com/nvm-sh/nvm). "Node Version Manager"
- [pyenv](https://github.com/pyenv/pyenv). "Simple Python Version Management"
- [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv#installing-with-homebrew-for-macos-users). Allows usage of virtual envs with a python version of your choice.

```sh
brew install git nvm pyenv pyenv-virtualenv
```

Other apps to download, but cannot be downloaded with `brew`:

- [SoundBooster](https://froyosoft.com/soundbooster.php). Increases MacbookPro's default max volume. Note - this may mess with your macbook pro's default sounds behavior.
- [Remote Mouse](https://www.remotemouse.net/). Helps control your computer with your phone.
- [Fig](https://fig.io/?ref=hn). Gives visual-studio-like auto-complete on your terminal.
- [Monosnap](https://monosnap.com/download/mac)
- Camtasia

## Log in to Gmail Accounts

Next, open Chrome and log in with all of the gmail accounts.

## Set up the development environment

#### Install Oh my zshrc

Find installation instructions here: https://github.com/ohmyzsh/ohmyzsh#basic-installation

#### Load home directory settings

Copy the contents of the follwing files to the corresponding files in your home directory:

```sh
.gitconfig
.zshrc
.bash_profile
```

#### Replace the terminal color scheme.

1. Save the contents of the `argonaut.terminal` file to your computer. 
2. Import the `argonaut.terminal` file into the terminal by going to `Preferences`.
3. At the bottom of the list of terminal themes, click on the gear icon and then on the import option.

#### Load the visual studio code extensions

- Download the 'Settings Sync' extension from the Visual Studio Code marketplace
- Press `cmd + shift + p` and type `Sync`
- Choose the `Sync: Download Settings` option
- Here is the link to the most up-to-date gist
> https://gist.github.com/viiqswim/ed482ae64cdb8fc50b947c9e321a2692
