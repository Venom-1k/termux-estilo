<a href="https://ibb.co/F4XZCr1"><img src="https://i.ibb.co/v4hyRFW/20220612-145920.jpg" alt="20220612-145920" border="0"></a>

# Termux Style

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

![gif](images/main.gif) <br />

> *Script simples para alterar esquemas de cores e fontes para o emulador de terminal Termux*


### Como instalar

Follow the steps below - 

```bash
# go to home dir - 
cd $HOME

# clone this repository - 
git clone https://github.com/adi1090x/termux-style

# change to termux-style dir -
cd termux-style

# to install it, run -
./install

# And Follow the steps, it'll be installed on your system.
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
    [*] By- Aditya Shakya // adi1090x

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

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/spiderman.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/adi1090x/termux-style/master/colors/gruvbox-dark.properties`) of the color-scheme.
<br />

### Previews

|Colorschemes|Fonts|
|--|--|
|![img](images/colors.gif)|![img](images/fonts.gif)|

|Import - URL|Import - Local|
|--|--|
|![img](images/url.gif)|![img](images/local.gif)|

|Install|Uninstall|
|--|--|
|![img](images/install.gif)|![img](images/uninstall.png)|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
