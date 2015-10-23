### My Configurations
----
| Chris Hough | Favorite Quotes |
| :---: | :--- |
| ![open-source-projects.jpeg](https://github.com/chrishough/myresume/raw/master/graphics/avatar/myphoto-320x320.png)<br/><br/>[Resume](https://github.com/chrishough/myresume/) | *"Evolution doesn’t linger on past failures, it’s always building upon what worked. So should you.”*<br/>― Jason Fried, REWORK<br/><br/>*“I have not failed. I've just found 10,000 ways that won't work.”*<br/>― Thomas A. Edison<br/><br/>*“First they ignore you, then they laugh at you, then they fight you, then you win.”*<br/>― Mahatma Gandhi

I have found every developer's workstation configuration to be highly variable and tailored to their exact desires.  Whatever makes the person tick right?  I tend to spend a chunk of time each month tuning my box for maximum efficiency, and just like the quantified self movement this is my guide tracking the updates.  In a nutshell this is how I [grok, trunk, and live](href="http://www.youtube.com/watch?v=Qi_AAqi0RZM) each and every day. I believe in being part cyborg actually and rarely unplug, however, that is a totally different story.

![open-source-projects.jpeg](https://github.com/chrishough/myconfigurations/raw/master/graphics/open-source-projects.jpeg)

### Assumptions
----
* The workstation is running the latest production release of [Apple OSX](http://www.apple.com/osx/).
* The latest release of [Xcode](https://developer.apple.com/xcode/) has been installed with the developer command line tools.
* [Homebrew](http://brew.sh/) has been successfully installed.
* Running ```brew doctor``` does not report any configuration issues.
* [Google Chrome](http://www.google.com/chrome) is your primary development browser.
* [rbenv](https://github.com/sstephenson/rbenv) is how you're running ruby locally, pre-installed.
* [ruby-build](https://github.com/sstephenson/ruby-build) installed via brew.

### Software
----

* [Atom](https://atom.io/)
* [iterm2](http://www.iterm2.com/#/section/home)
* [Zsh](http://www.zsh.org/) + [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* [Postgres App](http://postgresapp.com/), for development.
* [Autojump](https://github.com/joelthelion/autojump) ```brew install autojump``` memorizes your favorite locations and allows you to quickly navigate to a path from anywhere in your shell.
* [The Silver Searcher](https://github.com/ggreer/the_silver_searcher) ```brew install the_silver_searcher``` replaces ack and is by far the fastest search utility I have used.
* [Evernote](http://evernote.com/) for notes and local documentation.
* [Mou](http://mouapp.com/) for editing markdown files.
* [Paw](https://luckymarmot.com/paw) for API testing and construction.
* [Pathfinder](http://cocoatech.com/pathfinder/) for a finder on steroids.
* [Arq + S3](http://www.haystacksoftware.com/arq/) for encrypted cloud backup.
* [Cloak](https://www.getcloak.com/) for cloud based VPN.
* [Dash](http://kapeli.com/dash) for local documentation.
* [Divvy](https://mizage.com/divvy/) for osx window management.
* [Adobe Creative Cloud](http://www.adobe.com/) for designs, mainly AI and Photoshop.
* [Alfred](http://www.alfredapp.com/) workflows! Here are a helpful list of the [workflows I use](https://github.com/chrishough/myconfigurations/tree/master/software/alfredapp/community.md) and list of [workflows I built](https://github.com/chrishough/myconfigurations/tree/master/software/alfredapp/noconformity.md).
* [Keyboard Maestro](http://www.keyboardmaestro.com/main/) macros. [Find my setup here](https://github.com/chrishough/myconfigurations/tree/master/software/maestro/noconformity.md).
* [iStat Menus](http://bjango.com/mac/istatmenus/) for system performance monitoring.

### rbenv plugins
----
* [rbenv-default-gems](https://github.com/sstephenson/rbenv-default-gems): This rbenv plugin hooks into the rbenv install command to automatically install gems every time you install a new version of Ruby.
* [rbenv-gem-rehash](https://github.com/sstephenson/rbenv-gem-rehash): Never run rbenv rehash again. This rbenv plugin automatically runs rbenv rehash every time you install or uninstall a gem.
* [rbenv-vars](https://github.com/sstephenson/rbenv-vars): This is a plugin for rbenv that lets you set global and project-specific environment variables before spawning Ruby processes.
* [rbenv-binstubs](https://github.com/ianheggie/rbenv-binstubs): This plugin makes rbenv transparently aware of project-specific binstubs created by bundler. This means you don't have to type bundle exec ${command} ever again!

### Atom Packages
----
I use the [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) font for development.

Via `Package Control` these are my favorite packages:  

![atom-package-list](https://github.com/chrishough/myconfigurations/raw/master/graphics/atom/atom-package-list.png)

### My Shell Theme
----
![shell-theme-example](https://github.com/chrishough/myconfigurations/raw/master/graphics/shell-screenshots/shell-theme-example.png)

Download the [Base16 iTerm2](https://github.com/chriskempson/base16-iterm2) colors, and import them under the colors panel in iterm2 preferences. My theme uses ```base16-railscasts.dark``` which can be loaded in the presets.  You will need to set the contrast as shown to have a clearer definition of the font icons.

![shell-theme-iterm-colors-example](https://github.com/chrishough/myconfigurations/raw/master/graphics/shell-screenshots/shell-theme-iterm-colors-example.png)

Under the terminal tab, make sure to change the report terminal type to ```xterm-256color``` and your character encoding to ```Unicode (UTF-8)```.

![shell-theme-iterm-terminal-example](https://github.com/chrishough/myconfigurations/raw/master/graphics/shell-screenshots/shell-theme-iterm-terminal-example.png)

The background image I created can be found [here](https://github.com/chrishough/myconfigurations/raw/master/graphics/terminal-background.png).  Once attached as the background you will notice a red box around your shell window.  
![shell-theme-iterm-window-example](https://github.com/chrishough/myconfigurations/raw/master/graphics/shell-screenshots/shell-theme-iterm-window-example.png)

### My New Machine Checklist
----
0. files migrated, software installed, all software setups in place
1. setup xcode + command line tools
2. install homebrew, and update homebrew
3. brew install git
4. brew install autojump
5. brew install the_silver_searcher
6. brew install postgres
7. brew install nvm
8. brew install direnv
9. install postgresapp from postgresapp.com
10. copy ~/.gitconfig and ~/.ssh to new computer
11. verify git works by cloning git .myconfigurations
12. download and install iterm2, set auto check for updates
13. install .oh-my-zsh
14. brew install zsh
15. ```chsh -s /bin/zsh``` to set zsh as the default shell
16. in iterm2 change the default background to my terminal-background.jpg
17. download and install the inconsolata font
18. download and install atom
19. install atom plugins
20. setup atom theme, keymap.cson, and config.cson files
21. backup current settings file by running ruby settings/backup.rb
22. brew install rbenv ruby-build
23. make sure each dotfile exists, if it does not create it
24. symlink the current dotfiles to the git versions via ruby settings/symlinks.rb
25. setup my shell theme
26. install rbenv plugins
27. make sure to setup rbenv vars
28. run brew doctor to make sure there are no errors
29. install rbenv versions
30. install [java](http://support.apple.com/kb/DL1572)
31. cd into scripts and run ruby backup.rb
32. cd into scripts and run ruby symlinks.rb

...*Time to drink beer!*
