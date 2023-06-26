# Pass-zenity
Simple GUI interface of pass linux with zenity gui

# Installation
* Clone this repository
```
git clone https://github.com/Anant-mishra1729/Pass-zenity.git
```
* Place all the files except README.md in `~/.local/bin`, create `~/.local/bin` directory if it doesn't exist
```
cd Pass-zenity && mv pass* ~/.local/bin/
```
* Add keyboard shortcuts for easy access

# About
#### pass-generate
Generates password for username
* If password is not provided random password is generated for that username.
* If username already exists the ui will ask for whether to overwrite the password or not.

#### pass-show
Gives a list preview of all usernames
* Usernames are searchable
* After selecting usernames, the password will be copied to clipboard for 45 seconds.

#### pass-remove
Removes a password 🙂
