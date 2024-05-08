**`LAST Updated`** : `May 2024'

> Unmaintained : Due to Termux not working properly on new Android versions and also Termux not getting maintained properly.

---

# Termux Style

<p align="left">
  <img src="https://img.shields.io/github/license/Mrtelegrambot/Termux-Style?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/Mrtelegrambot/Termux-Style?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/Mrtelegrambot/Termux-Style?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/Mrtelegrambot/Termux-Style?color=violet&style=for-the-badge">
</p>

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

![gif](images/main.mp4) <br />

> **`termux-style` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone adi1090x/termux-style` if you want to use the GitHub CLI)- 
git clone https://github.com/Mrtelegrambot/Termux-Style

# Change to termux-style dir -
cd Termux-Style

# To install it, run -
./install.sh

# And follow the steps, it'll be installed on your system.
```

### Run

Run `termux-style` & select the right option -

```bash
$ termux-style

    ┌──────────────────────────────────────────────────┐
    │░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░░░░█▀▀░▀█▀░█░█░█░░░█▀▀░░│
    │░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░▄▄▄░▀▀█░░█░░░█░░█░░░█▀▀░░│
    │░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░░░░▀▀▀░░▀░░░▀░░▀▀▀░▀▀▀░░│
    └──────────────────────────────────────────────────┘
    [*] By- Sathish Kumar// Mrtelegrambot 

    [C] Colors (89)
    [F] Fonts (20)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 90 popular color-schemes.
+ 20 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/Mrtelegrambot/Termux-Style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/Mrtelegrambot/Termux-Style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />

### Previews

|Install|Uninstall|
|--|--|
|![img](images/install.gif)|![img]|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
- 
