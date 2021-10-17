+++
title = "TeX Setup"
+++

This describes the dependencies needed on a Debian-based system. (This was tested on Ubuntu 18.04, Ubuntu 20.04 and Debian 10)

#### Notes

When we say 'run a command', it means:

- Open a terminal with `Ctrl+Alt+T` (or via your menu)
- Type the command
- Press `Enter`
- Enter a password when prompted to install software

### 1. XeLateX

> The alternative to LaTeX we will be using, because of its support for UTF-8.

Run the command `sudo apt install texlive-xetex`.

To get all TeX packages, you should run `sudo apt install texlive-full` instead (warning: this might take some time)

### 2. FreeSerif font

> A font with good support for UTF-8

- Install the font manager: `sudo apt install font-manager`
- Download the FreeSerif font [here](https://www.fontspace.com/freeserif-font-f13277)
- Add the font using the font manager

### 3. Latexmk

> Used to drive the TeX compilation.

Run the command `sudo apt install latexmk`

### 4. Visual Studio Code

You can download and install VSCode [here](https://code.visualstudio.com/Download).
