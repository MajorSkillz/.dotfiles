# dotfiles and setup for linux and mac

## Essentials for proxy
    sudo nano /etc/apt/apt.conf
    #add below two lines
    Acquire::http::No-Cache true;
    Acquire::http::Pipeline-Depth 0;

## Basic Needs ,Geany, Terminator, Git, Maven
    sudo apt-get install git curl maven vim vlc python3-pip terminator geany

## IDE's
    sudo apt-get install snapd && sudo apt-get install snap
    sudo snap set core proxy.http=http://172.16.2.30:8080
    sudo snap set core proxy.https=http://172.16.2.30:8080
    sudo snap install clion --classic
    sudo snap install intellij-idea-ultimate --classic
    sudo snap install android-studio --classic


## Vim
    git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
    curl 'https://raw.githubusercontent.com/rishabhdeepsingh/.dotfiles/master/.vimrc' -o ~/.vimrc

## Bashrc
    curl 'https://raw.githubusercontent.com/rishabhdeepsingh/.dotfiles/master/.bashrc' -o ~/.bashrc

### Git prompt
    git clone https://github.com/magicmonty/bash-git-prompt.git ~/.bash-git-prompt --depth=1

### [X ARch White](https://gitlab.com/LinxGem33/X-Arc-White/tags/v1.4.7)

------

## JAVA [Download](https://www.oracle.com/technetwork/java/javase/downloads/index.html)  [Install Help](https://www.javahelps.com/2017/09/install-oracle-jdk-9-on-linux.html)