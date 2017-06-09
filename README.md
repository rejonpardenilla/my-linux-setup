# My linux setup

This repo contains all the apps, user settings, styles and enviroment configs for developers in **Ubuntu 16.04**.

The purpose of this repo is to have a reference in case of any (other) chaos incident... you know, as a developers we tend to install things and run all kinds of strange commands someone in stack overflow tell us tu run in our terminals without caring too much about consequences.

> Pro tip: **DON'T** run the `sudo chmod -R 755 /usr/bin` command. :fire:

Anyway, if somehow you end up re-installing Ubuntu (again), I recommend use all this apps and settings (or not, it's just a bunch of personal preferences).

## :construction: This repo is in early stage :construction:

## Content

  - [System settings](#system)
  - [Apps](#apps)
  - [Terminal preferences](#terminal)
  <!-- - [Chrome extensions](#chrome) -->
  - [VScode preferences](#editor)
  <!--
  - [Rails enviroment]()
  - [Vue enviroment]()
  - [Laravel enviroment]()
  -->


## System
Go to `System Settings > <kind-of-setting>`

  ### Appeareance


  - Launcher icon size: **34**
  - Auto-hide the launcher: **on**
  - Enable workspaces: **true**

  ### Brightness & Lock
  
  - Dim screen to save power: **off**
  - Turn screen off when inactive for: **never**
  - Lock: **off**
  - require my password when waking from suspend: **false**

  ### Mouse & Touchpad

  - Natural scrolling: **true**

  ### Power

  - All: **do nothing**


## Apps

  - [Google Chrome](https://www.google.com/chrome/browser/desktop/index.html)
  - [Slack](https://slack.com/downloads/linux)
  - [Wire](https://wire.com/en/download/)
  - [Pick](https://kryogenix.org/code/pick/)
  - [Spotify](https://www.spotify.com/download/linux/)
  - [Autoset desktop background](https://github.com/rejonpardenilla/autoset-desktop-background)


## Terminal

  ### ~/.bashrc

  ```bash
  ##
  # A lot of code right here.
  # Pro tip: don't touch it.
  ##

  # Add ruby enviroment to the system path
  export PATH="$HOME/.rbenv/bin:$PATH"
  # and start it
  eval "$(rbenv init -)"

  # This is for dnsmasq
  export SOCKET_DIR=/var/www
  ```

  ### Terminal colors and font


## Editor

I use [Visual Studio Code](https://code.visualstudio.com/) for text editor.

  ### Extensions

  - Snazzy Operator
  - erb
  - rails
  - Ruby
  - ruby-linter
  - ruby-on-rails-snippets
  - Sublime Text Keymap
  - vscode-icons

  ### /settings.json
  You can find this file smashing `Ctrl + P` in your keyboard and then typing gently:
  
  `>user settings`

  ```json
  {
    "files.autoSave": "off",
    "workbench.colorTheme": "Snazzy Operator",
    "workbench.iconTheme": "vs-seti",
    "editor.fontFamily": "Monaco",
    "editor.tabSize": 2,
    "editor.fontSize": 13,
    "window.zoomLevel": 0,
    "files.associations": {
      "*.erb": "erb"
    }
  }
  ```


