# https://github.com/Homebrew/homebrew-bundle

# homebrew taps
tap 'homebrew/bundle'
tap 'homebrew/core'
tap 'go-delve/delve'
tap 'kryptco/tap'

# Heroku CLI
#tap 'heroku/brew'
#brew 'heroku'

# Python - used by mackup and watchman
brew 'python'

# Updated ruby (https://jekyllrb.com/docs/installation/macos/)
brew 'ruby'

# apps
brew 'bash-completion'
brew 'git'
brew 'hugo'
brew 'mackup'
# brew 'n'
brew 'jq'
brew 'gpm'
brew 'shellcheck'
brew 'ssh-copy-id'
brew 'tree'
brew 'vault'
brew 'openssl'
brew 'wget'
brew 'grep'
brew 'wrk'
brew 'upx'
brew 'telnet'
brew 'asciinema'
brew 'broot'
brew 'sqlite'

# Deno
# brew 'deno'

# AWS Serverless CLI (https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install-mac.html)
tap 'aws/tap'
# brew 'aws-sam-cli'

# netlify
tap 'netlify/netlifyctl'
brew 'netlifyctl'

# hygen templates  https://github.com/jondot/hygen
tap 'jondot/tap'
brew  'hygen'

# ZSH Stuff
brew 'zsh'
brew 'zsh-completions'

# Install GNU core utilities (those that come with macOS are outdated)
brew 'coreutils'

# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
brew 'findutils'

# Other GNU utils
brew 'gnu-sed'#, args: ['with-default-names']
brew 'gnu-tar'#, args: ['with-default-names']
brew 'gnu-which'#, args: ['with-default-names']

# Go Stuff
brew 'go'
brew 'kubectl'
brew 'kubernetes-helm'

# React
# brew 'yarn'
# Watchman is a tool by Facebook for watching changes in the filesystem.
brew 'watchman'

# secure ssh
brew 'kryptco/tap/kr'

# dependencies
brew 'gdbm'
brew 'pcre'
brew 'libidn'

# Pilosa Console https://www.pilosa.com
# tap 'pilosa/homebrew-pilosa'
# brew 'pilosa-console'

#
# install casks
# 

tap 'homebrew/cask'
cask_args appdir: '/Applications', require_sha: true

# -------------------------
cask 'visual-studio-code'
cask 'github'
cask 'google-chrome'
cask 'firefox'
cask 'google-cloud-sdk'
cask 'kitematic'
cask 'iterm2'
cask 'hyper'
cask 'keepingyouawake'
cask 'ngrok'
cask 'spectacle'
cask 'spotify'

# inkscape
# cask 'xquartz'
# cask 'inkscape'

# API tool
cask 'insomnia'

# Note taking
cask 'obsidian'

# broadcasting
cask 'zoom'
cask 'obs'
cask 'vlc'
# cask 'vb-cable'  

# Barrier KVM https://github.com/debauchee/barrier
# cask 'barrier'

# --- Other ---
# cask 'slack'
# cask 'cheatsheet'
# cask 'filezilla'
# cask 'handbrake'
# cask 'keybase'
# cask 'telegram'
# cask 'sketch'

# minikube uses virtualbox so it must be first
# cask 'virtualbox' 
# cask 'minikube'

# SQL tools
# cask 'popsql'
tap 'benbjohnson/litestream'
brew 'litestream'
cask 'tableplus'

# https://github.com/buo/homebrew-cask-upgrade
# brew-cask-upgrade is a command-line tool for upgrading every 
# outdated app installed by Homebrew Cask.
tap 'buo/cask-upgrade'

# install fonts
tap 'homebrew/cask-fonts'
# --------------------------
# cask 'font-hack'
cask 'font-hasklig'
# cask 'font-monoid'
cask 'font-source-code-pro'
# cask 'font-iosevka'
cask 'font-input'
cask 'font-jetbrains-mono'

# install app store apps
# https://github.com/mas-cli/mas
# -------------------------
brew 'mas'
# -------------------------
mas 'Microsoft Remote Desktop', id: 1295203466
# mas 'Xcode', id: 497799835
mas 'Slack', id: 803453959
mas 'Evernote', id: 406056744
mas 'Todoist', id: 585829637
mas 'LastPass', id: 926036361

# ---  Office 365  ---
mas 'Microsoft Excel', id: 462058435 
mas 'Microsoft PowerPoint', id: 462062816 
mas 'Microsoft Outlook', id: 985367838 
mas 'Microsoft OneNote', id: 784801555 
mas 'Microsoft Word', id: 462054704 
mas 'OneDrive', id: 823766827 
mas 'Microsoft To-Do', id: 1274495053


# --- native apps 2019 ---
# mas 'GarageBand', id: 682658836
# mas 'iMovie', id: 408981434
# mas 'Pages', id: 409201541
# mas 'Keynote', id: 409183694
# mas 'Numbers', id: 409203825

# --- Other ---
# mas 'Clear', id: 504544917
# mas 'Skitch', id: 425955336
# mas 'Bitcoin Expert', id: 1237809495
# mas 'Twitter', id: 409789998
# mas 'iPhoto', id: 408981381
# mas 'TurboTax 2015', id: 1061844571
# mas 'LastPass', id: 926036361
# mas 'Aperture', id: 408981426
# mas "Blackmagic Disk Speed Test", id: 425264550
# mas "CARROT Weather", id: 993487541
# mas "CCMenu", id: 603117688
# mas "DrCleaner", id: 921458519
# mas "Frame.io", id: 992958444
# mas "Magnet", id: 441258766
# mas "QuickBooks", id: 640830064
# mas "WiFi Explorer", id: 494803304
# mas "WiFi Signal", id: 525912054


# ***  Examples ***
# tap 'telemachus/brew', 'https://telemachus@bitbucket.org/telemachus/brew.git'
# brew 'imagemagick'
# brew 'mysql', restart_service: true, conflicts_with: ['homebrew/versions/mysql56']
# brew 'emacs', args: ['with-cocoa', 'with-gnutls']
# cask 'google-chrome'
# cask 'java' unless system '/usr/libexec/java_home --failfast'
# cask 'firefox', args: { appdir: '~/my-apps/Applications' }


# Homebrew Services
# Integrates Homebrew formulae with macOS' launchctl manager.
# -------------------------

# Start the MySQL service at login with:
# brew services start mysql

# Start the Dnsmasq service at boot with:
# sudo brew services start dnsmasq

# Start all available services with:
# brew services start --all