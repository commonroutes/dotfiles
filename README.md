# dotfiles
various dotfile configs for i3wm &amp; xfce

i3 screenshot:
![screenshot of i3 desktop](https://i.imgur.com/UALXqJy.png)

**e**ssentials:
- [arc-dark](https://github.com/horst3180/Arc-theme) GTK theme
- [numix-icon-theme-circle](https://github.com/numixproject/numix-icon-theme-circle) icon theme
- [futura bt](https://www.fontshop.com/families/futura-bt) font, best free alternative is [ubuntu](http://font.ubuntu.com/)
- [font awesome](http://fontawesome.io/) for workspace icons
- [feh](https://feh.finalrewind.org/) to apply wallpaper
- [compton](https://github.com/chjj/compton) window compositor

**t**he /home directory files should be placed in your respective home user folder (e.g. `/home/username/`)<br>
- there is a crude install script to force-copy all configs to the correct locations
- (only tested locally on Ubuntu 16.04.3)
- to run the script, clone this repo and make it executable:

`git clone https://github.com/commonroutes/dotfiles`<br>
`cd dotfiles`<br>
`chmod +x install.sh`<br>
`./install.sh`

**t**hese configs will assume the arc-dark theme and many third-party applications<br>
- comb through and make changes according to your preferences and/or applications<br>

**t**he compton config is currently a copy/paste job from [duncanlock](http://duncanlock.net/blog/2013/06/07/how-to-switch-to-compton-for-beautiful-tear-free-compositing-in-xfce/)<br>
- comments will eventually be tidied up, but the core configs will likely remain the same
