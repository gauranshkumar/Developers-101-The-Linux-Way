
# Developers 101: The Linux Way

This is the resource page for the Workshop. Hope you had a fun time learning and I can't wait to see you use **Linux**

## Resources

Here are some Resources to get you set-up for the Linux-Journey

- Video Reference:

  - [Install Ubuntu on VirtualBox](https://www.youtube.com/watch?v=S26CKNo4Tgs)
  - [Dual Boot Ubuntu alongside Windows](https://www.youtube.com/watch?v=u5QyjHIYwTQ)

- Wikis:

  - [Install Ubuntu Desktop](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
  - [Linuxmint Installation Guide](https://linuxmint-installation-guide.readthedocs.io/en/latest/)

- Recommended Distributions to try for Beginners:
  - [Ubuntu](https://ubuntu.com/#download)
  - [Linux Mint](https://linuxmint.com/download.php)
  - [Zorin OS](https://zorinos.com/download/)
  - [Elementary OS](https://elementary.io/) (If you don't wnat to pay just choose Cutome Price and put 0, but if you can pay then please help them.)

## Basic Commands/Tools

#### Directory

| Commands                    | Description                      |
| --------------------------- | -------------------------------- |
| `ls`                        | List Items of Directory          |
| `pwd`                       | Prints present working Directory |
| `cd`                        | Change Directory                 |
| `mkdir <name-of-directory>` | Creates an empty Directory       |
| `rmdir <name-of-directory>` | removes an empty Directory       |

#### Files

| Commands                                    | Description                                      |
| ------------------------------------------- | ------------------------------------------------ |
| `touch <name-of-file>`                      | Creates an empty file of any type                |
| `cp <source-address> <destination_address>` | Copies file/directory from source to destination |
| `mv <source-address> <destination_address>` | Moves file/directory from source to destination  |
| `cat <filename>`                            | Prints contents of file to `STDOUT`              |
| `less <filename>`                           | Shows contents of file in readable format        |

#### Help

| Commands           | Description                                                                  |
| ------------------ | ---------------------------------------------------------------------------- |
| `man <pkg-name>`   | Shows the Man Page for the Package if available.                             |
| `<command> --help` | --help is a general flag which gives help for almost all commands & packages |
| `df`               | Information about storage on disk                                            |
| `lsblk`            | Lists all the Linux Directories with their disk space used                   |
| `lsusb`            | Lists all devices attached to computer                                       |
| `top`              | Live system monitor                                                          |

#### Editors

Majourly used text editors are:

- [Nano](https://www.nano-editor.org/)
- [VIM](https://www.vim.org/)
- [Emacs](https://www.gnu.org/software/emacs/)

#### Utilities

| Commands               | Description                                                    |
| ---------------------- | -------------------------------------------------------------- |
| `tar [options] <path>` | Used to create/open Tarballs and compress/decompress them.     |
| `zip <path>`           | Zip a folder in a ZIP File                                     |
| `unzip <path>`         | Unzip a ZIP file                                               |
| `wget [options] <url>` | A utility for getting various stuffs from Web                  |
| `curl [options] <url>` | Downloads Webpages/Files from Web                              |
| `grep`                 | Searches for string in file/STDOUT                             |
| `awk <instruction>`    | Very powerful tool for text manipulation using `awk` language. |
| `ping <url>`           | Pings the given url                                            |
| `fzf`                  | Fuzzy Finer used to perform Fuzzy Search anywhere             |
| `whoami`               | Prints name of current user                                    |
| `date`                 | Shows current system date & time                               |
| `calender`             | Prints the calender                                            |
| `passwd`               | Changes password of current user                               |
| `sudo su`              | Opens Root User Prompt                                         |

and so on.....

#### Fun Utilities

| Commands   | Description                        |
| ---------- | ---------------------------------- |
| `lolcat`   | Ranbows Output to STDOUT           |
| `htop`     | Better and Colorful version of Top |
| `neofetch` | All you system info in Fancy way.  |
| `cowsay`   | ASCII Arts with your text.         |

#### Package Management

- Using **APT**:
  | Commands | Description |
  |-----------------------------------|------------------------------------------------|
  | `apt-get install package-name(s)` | Installs the package(s) with dependency |
  | `apt-get remove package-name(s)` | Remove the package(s) but not dependency |
  | `apt-get autoremove` | Remove unused dependency |
  | `apt-get update` | Update Package List |
  | `apt-get upgrade` | Upgrade Packages if newer version is available |
  | `apt search <search-string>` | |
- Using **dpkg**:
  | Commands | Description |
  |--------------------------------|---------------------------------|
  | `dpkg -i <package-name>` | Install a .deb file |
  | `dpkg -r <package-name>` | Remove a .deb file |
  | `dpkg --list <search-pattern>` | List installed Packages |
  | `dpkg -s <package-name>` | Check if a package is installed |

#### File Permissions
| Permission | Short Representation | Numeric Value |
|------------|----------------------|---------------|
| `READ`     | `r`                  | `4`           |
| `WRITE`    | `w`                  | `2`           |
| `EXECUTE`  | `x`                  | `1`           |


## Tools for Productivity

- **Bash Scipting:** Bash Scripting is a great way to automate various task and use the full potential of the Linux. [Bash from scratch: learn enough bash to write your own scripts](https://dev.to/ahmedmusallam/bash-from-scratch-learn-enough-bash-to-write-your-own-scripts-189f) is a great Blogpost to get you started with it.
- **Alias:** Aliases uses alias command to create shortcuts for long command and these can be life saviour sometimes this is how you declare them `alias <name-of-alias>=<complete-command>`
- **Environment variables:** Environment variables are a great tools for devs to hide secrets and to create a Env variable in linux we use `export <key>=<value>`.
- **History:** History is a great tool specially for Dev's as it shows all the commands you ran earlier and to use this just type `history` and you are good to go. You can also search through history via `Ctrl+R` keyboard shortcut.
- **Searching:** Searching is insane in Linux, we have various tools to search like `locate`, `find`, `fzf`, `whereis` etc. Each have their special uses but all aids in searching.

## VIM

  Vim is really a swiss knife for Devs though it takes alot of efforts to learn, but once mastered you are more productive than ever before.
  To get started with vim you can check these:

- `vimtutor` command
- [Beginning Vim (and using Vim in other text editors)](https://dev.to/devalo/beginning-vim-and-using-vim-in-other-text-editors-36cm)
- For learning with fun be sure to check this [Vim Adventures](https://vim-adventures.com/)

## GIT

Git is a must to have and great tool for developer's. It's a complete Universe in itself.

But don't worry I have Got your back, try these amazing explanations to get started:

- [Git and GitHub: The Basics](https://dev.to/lofiandcode/git-and-github-the-basics-5chg)
- [Git in 10 Mins](https://www.youtube.com/watch?v=OQLiJwFZ4Ag)

## Resources for Help

- [Stack Overflow](https://unix.stackexchange.com/)
- [Ask Ubuntu](https://askubuntu.com/)
- [Arch Wiki](https://wiki.archlinux.org/)
- Documentation of the Apps/Packages
- Github Issues/Gists

## Authors

- [@gauranshkumar](https://www.github.com/gauranshkumar)
