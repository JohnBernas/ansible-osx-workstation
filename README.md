ansible-osx-workstation
====================

for setting up my work machine.


## Installation under El Capitan (OS X 10.11)

### 1. Install XCode

[![Xcode - Apple](http://r.mzstatic.com/images/web/linkmaker/badge_macappstore-lrg.gif)](https://itunes.apple.com/us/app/xcode/id497799835?mt=12&uo=4)

Don't forget to start up Xcode once it's installed so that you can agree to the terms&mdash;many commands won't work until the terms have been agreed to.

### 2. Install Command Line Tools

    xcode-select --install

### 3. Clone this project

    git clone git@github.com:JohnBernas/ansible-osx-workstation.git
    cd ansible-osx-workstation

### 4. Install Ansible

    sudo easy_install pip
    sudo pip install ansible

### 5. Install Homebrew (todo: do this automatically in the future)

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

### 6. Run the thing!

    ansible-playbook main.yml
    (ansible-playbook main.yml --ask-sudo-pass)
