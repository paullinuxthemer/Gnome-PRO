# Gnome-PRO
a GTK2,and GTK3 file for the Gnome-desktop


![s](https://cn.pling.com/img/2/d/5/c/2d48932d5173f4fe1a6a975237c11aca1f00.jpg)

A clear and easy-on-the-eyes theme that is meant for those who use the Gnome-desktop professionally on a daily basis. The focus in this theme is compatibility: GTK-2 applications and GTK-3 applications look virtually the same. Libre-office, Scribus, Evolution, Geary, Planner, GnuCash, LaTeXila, Geany, the Gimp, Inkscape,...

Chrome, firefox, Web and Opera have no issues with this theme.

About the looks, you will notice some Elementary-theme, Arc-theme and Gnome-OSX.

The NEW VERSION Gnome-PRO is Gnome 3.28 ready, with crispier fonts, new hover-effects and new check- and radio-items, and the use of gradient-colors (even on GTK2-menu's), and reduced clutter on the headerbar (simple headerbar buttons) makes this new version a more serene, comfortable layout for your daily jobs.

### Requirements

First, This theme only works in the gnome-desktop, with GTK 3.20 -GTK 3.28, and also in Ubuntu 18.04+

Next, buttons should be on the right side. If they are not: here is the terminal-code:

gsettings set org.gnome.desktop.wm.preferences button-layout ":minimize,maximize,close"

In Gnome 3.26+, the Tweak-tool makes it easier to change the button-position. The above commands are then no longer necessary.

When, as such, theming does not look the way it should be: make sure you have installed the necessary theme-"engines":
Make sure the GTK2-engines-pixbuff are installed:

sudo apt-get install gtk2-engines-pixbuf is the terminal command in Ubuntu.

Furthermore:

- The gnome-themes-standard package,
- The murrine engine. This has different names depending on your distro.
gtk-engine-murrine (Arch Linux)
gtk2-engines-murrine (Debian, Ubuntu, elementary OS)
gtk-murrine-engine (Fedora)
gtk2-engine-murrine (openSUSE)
gtk-engines-murrine (Gentoo)

### How to install:

Download the theme.

Just copy the extracted file to a '.themes'-folder you make in your home directory.
Then use Tweak-tool to select the GTK-theme. For systemwide use (or if you use SNAP-packages) make sure the theme resides in USR/SHARE/THEMES/

LOG OUT AND BACK IN for changes to take full effect !
