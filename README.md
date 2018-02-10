# Forked from https://github.com/Tustin/pkg-merge
A linux portage for Linux (gnome/nautilus)

# pkg-merge
Merges .PKG parts into one PKG file. Used for PS4 PKG files that come split into 4gb parts from the PlayStation Store.


## Compiling from source
Install Go on your system: https://golang.org/dl/

Setup your Go environment: https://skife.org/golang/2013/03/24/go_dev_env.html

Pull in this repo to your Go workspace

Navigate to folder using your terminal/command prompt

Run 'go run main.go' to execute, or run 'go build' to generate a binary to execute


## Using
Create a folder and put all your pkgs inside this folder

Run the program using the following command:

`pkg-merge -dir "myDir"` (replace myDir with your folder name)

The program will merge all the pkg parts into the root pkg file (the one with _0 at the end of the name)

# Installation

sudo cp /usr/bin /your/path/pkg-merge
sudo chmod 751 /usr/bin/pkg-merge

## TO DO
Nautilus Script
detect and rename PKGs
Delete or not PKGs parts
