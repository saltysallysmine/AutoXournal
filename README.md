# AutoXournal

This small script allows you to manage your Xournal++ from command line. In particular, it can open Xournal++ and name the file with the current date and chosen directory name. **Oh yes, and best of all: it automatically stores the sources in a separate folder, exporting them to PDF.** No further questions asked!

## Installation
Let's install this wonderful thing. Clone repository and give rights to the script: 
```bash
git clone git@github.com:saltysallysmine/AutoXournal.git
cd AutoXournal
chmod +x axo
```
After that make shortcut to execute _axo_ in your terminal emulator. I am using _oh-my-zsh_, so, I need to go to `~/.zshrc` (i.e. execute the `nano ~/.zshrc`) and put there the next code:
```bash
alias axo="/home/path/to/AutoXournal/axo"
```
That is all, now you can set up this programme.

## Configuration
Go to your lectures directory by `cd` from the command line and make there file `.dirname`:
```bash
cd Lectures # or another name of your directory
nano .dirname
# or vim .dirname if you don't worry of using this scary thing
```
Put there the name for your files. For example, `ExploringFluffyClouds`. Now you just need to type `axo` (or another alias for _axo_), draw a fluffy cloud in notepad, save the file and exit. After this, the exported file should be displayed. Now your directory should look like this:
```
└── Lectures
    ├── .dirname
    ├── 2023-02-09-ExploringFluffyClouds.pdf
    └── XOPPs
        └── 2023-02-09-ExploringFluffyClouds.xopp
```
## Usage
After installation and configuration you can just `cd` to your notes directory and execute `axo`.

---

That's it. Have a good cloud :-)

## Moreover
Вы можете прочитать этот файл на русском языке, он [расположен здесь](https://github.com/saltysallysmine/AutoXournal/blob/main/ruREADME.md) или прямо. This file in Russian is [located there](https://github.com/saltysallysmine/AutoXournal/blob/main/ruREADME.md).

