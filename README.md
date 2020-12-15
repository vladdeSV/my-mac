# my-mac
Showcase of my workplace MacBook Pro (15-inch, Mid 2015)

![Paid][Paid] the software requires a payment for continued usage. These come with a free trial.\
![Upgrade][Upgrade] the software has a paid upgrade, but does not require a payment for continued usage.\
![Open-Source][Open-Source] the software is open-source.

[Paid]: /resource/paid.svg?v=2 "Paid software"
[Upgrade]: /resource/upgrade.svg?v=2 "Free with upgrade"
[Open-Source]: /resource/open-source.svg?v=2 "Open-source sofware"

## Software

### [Alfred](https://www.alfredapp.com/) ![Upgrade][Upgrade]
It's like Spotlight, but better. I use it mainly to switch applications and to do Google searches. The paid version has extra features, but I highly suggest getting it even if you don't want to pay for it.

### [iTerm2](https://iterm2.com/downloads/stable/latest)
It's a terminal emulator. When first deciding between emulators, what initially got me to stick with this was it multi-pane feature. This allows me to have two sessions next to eachother. After using it for 3+ years I've come to like its many features.

*Extra: See my [dotfiles](https://github.com/dotfiIes/vladdeSV)*

### [Bartender](https://www.macbartender.com/Demo/Bartender%203.zip) ![Paid][Paid]
Allows me to hide and semi-hide icons in the menu bar. Love it.

### [Day-O](https://shauninman.com/assets/downloads/Day-3.0.zip)
Custom clock and calendar. I use it for its customizability, which allows me to show a plethera of things regularly want to see regarding time.

I use this custom format:

    "eeee d MMMM ('w.'w) | yyyy-MM-dd | ZZZZ | HH:mm (:ss)"
    // "Thursday 13 August (w.33) | 2020-08-13 | GMT+02:00 | 15:24 (:43)"

### <img alt="" src="https://simpleicons.org/icons/sublimetext.svg" height="15">&nbsp;[Sublime Text](https://www.sublimetext.com/) ![Paid][Paid]
The text editor I've loved over the years for it's speed. It's fast. It has a wide range of features, but speed is the primary reason I use this. Other GUI editors compare slow to Sublime Text.

### [Sublime Merge](https://www.sublimemerge.com/) ![Paid][Paid]
Hands down, the best Git client I've used. I even prefer this over the terminal.

### [Transmit](https://panic.com/transmit/) ![Paid][Paid]
The best file tansfer thing out there. I use it to transfer files between my computer and server, between servers, to Dropbox, Google Drive, and whatever else it supports.

I've yet to find a Windows alternative that is as good as Transmit.

### [Rectangle](https://rectangleapp.com/) ![Open-Source][Open-Source]
Resizes any window to some predfined areas with keyboard shortcuts. I maximize (not fullscreen) windows all the time, and often I resize windows to half the screen space.

I previously used Magnet, but it has less features and costs money.

### [MouseDef](https://github.com/zenangst/MouseDef) ![Open-Source][Open-Source]
⚠ This software is still in alpha, and it has some bugs.

Allows me to drag and resize any window by hoovering the cursor anywhere on a window and holding either <kbd>⌘</kbd><kbd>⇧</kbd> or <kbd>⌘</kbd><kbd>fn</kbd>. I have a hard time seeing myself going back from this.

This got me so hooked I had to get the [same featureset on my Windows machine](https://github.com/vladdeSV/my-ahk-scripts/blob/master/Scripts/EasyWindowDrag.ahk).

### [PhpStorm](https://www.jetbrains.com/phpstorm/) ![Paid][Paid]
IDE for web development. I was originally not happy to switch from my other tools, because I thought PhpStorm was a bit clunky.

But holy crap is this tool powerful. I manage my PHP code, SSH connections, and database all through this tool. Love this. It saved my butt multiple times.

### <img alt="" src="https://simpleicons.org/icons/jetbrains.svg" height="15">&nbsp;[JetBrains Toolbox](https://www.jetbrains.com/toolbox/)
To manage JetBrains software, a good compliment when you have their other software.

### [ImageOptim](https://imageoptim.com/)
A really simple and powerful tool to optimize images. I just plonk any images into this tool and it non-destructively optimizes them. Also allows me to destructively opimize images. Neat tool.

ImageOptim follows the UNIX philosophy; "Do One Thing And Do It Well".

### <img alt="" src="https://simpleicons.org/icons/lastpass.svg" height="15">&nbsp;[LastPass](https://www.lastpass.com/) ![Upgrade][Upgrade]
Keeps my passwords. Makes my life much easier. I use the free version. Available as an extension to webbrowsers, and as an app for phones.

## Software specifically for work
Some of these tools I only have because of work.

### <img alt="" src="https://simpleicons.org/icons/dropbox.svg" height="15">&nbsp;[Dropbox](https://www.dropbox.com/downloading)
Store files in the cloud. Wow.

### <img alt="" src="https://simpleicons.org/icons/xcode.svg" height="15">&nbsp;Xcode
I manage our iOS app, so this is a must.

### <img alt="" src="https://simpleicons.org/icons/vagrant.svg" height="15">&nbsp;[Vagrant](https://www.vagrantup.com/) ![Open-Source][Open-Source]
Allows me to spin up a vitrual machine, with the entire config in a single file.

## Other Software
These things don't really make up for a showcase of tools I suggest you use, but they are part of my daily routine.

### <img alt="" src="https://simpleicons.org/icons/googlechrome.svg" height="15">&nbsp;[Google Chrome](https://www.google.com/chrome/)
My default browser for work.

### <img alt="" src="https://simpleicons.org/icons/spotify.svg" height="15">&nbsp;[Spotify](https://www.spotify.com/en/download/mac/) ![Upgrade][Upgrade]
I listen to a lot of music. The monthly subscription for Spotify Premium is a must for me.

### <img alt="" src="https://simpleicons.org/icons/visualstudiocode.svg" height="15">&nbsp;[Visual Studio Code](https://code.visualstudio.com/) ![Open-Source][Open-Source]
All-purpose editor. Very neat. Highly suggest you get.

## CLI

### [brew](https://brew.sh/) ![Open-Source][Open-Source]
I cannot understate how useful this tool is. It's like the AppStore for the command-line. Download, update, and remove software.

Some command-line tools I use often:
```
brew install \
  fish    # my shell
  git     # you are viewing this on `git` hub \
  exa     # much better `ls` alternative \
  wget    # download file from url. i prefer this over `curl` \
  ripgrep # faster grep alternative
```

Some defaults which I change
```sh
defaults write -g KeyRepeat -int 1 # set key repeat delay to fast, but not dummy fast
defaults write com.apple.finder FXEnableExtensionChangeWarning -bool false # disable changing extension warnings
```

## Inspiration
This list was inspired by Nikita Voloboev's [`nikitavoloboev/my-mac-os`](https://github.com/nikitavoloboev/my-mac-os).

## License
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) © [Vladimirs Nordholm](https://github.com/vladdeSV)

App icons provided via [Simple Icons](https://github.com/simple-icons/simple-icons)
