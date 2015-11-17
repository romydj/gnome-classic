#gnome-classic

gnome-classic custom theme, dark color scheme, tested on openSUSE LEAP 42.1

![alt-text](https://github.com/romydj/gnome-classic/blob/master/opensuse.png)

###Installation

- Install gnome-shell-classic

  Goto (http://software.opensuse.org/package/gnome-shell-classic)

- Backup the original file !important

  `cp /usr/share/gnome-shell/theme/gnome-classic.css gnome-classic.css.bak`
  
  `cp /usr/share/gnome-shell/extensions/window-list@gnome-shell-extensions.gcampax.github.com/classic.css classic.css.bak`

- Download and Replace the original css file

  `cp src/gnome-classic-opensuse.css /usr/share/gnome-shell/theme/gnome-classic.css`
  
  `cp src/classic-opensuse.css /usr/share/gnome-shell/extensions/window-list@gnome-shell-extensions.gcampax.github.com/classic.css`

- Restart Gnome

  Press Alt+F2 type 'r' then close

- Rollback Action

  When gnome crashed, just rename originial backup css from terminal
