# Pass-zenity
Simple GUI interface of `pass` linux command with zenity gui
![image](https://github.com/Anant-mishra1729/Pass-zenity/assets/84588156/8634cb3c-e8ab-4495-b40f-bb0851df50a3)
# Installation
* Clone this repository
```
git clone https://github.com/Anant-mishra1729/Pass-zenity.git
cd Pass-zenity
```
* Make all files executable
```
chmod u+x pass*
```
* Place all the files except README.md in `~/.local/bin`, create `~/.local/bin` directory if it doesn't exist
```
mv pass* ~/.local/bin/
```
* Add keyboard shortcuts for easy access
![image](https://github.com/Anant-mishra1729/Pass-zenity/assets/84588156/f5e843a6-d224-481b-a3b0-cc8fa84c7f93)
 

# About
### pass-plugin
To access all the 3 plugins (generate, show, remove)

### pass-generate
Generates password for username
* If password is not provided random password is generated for that username.
* If username already exists the ui will ask for whether to overwrite the password or not.
![image](https://github.com/Anant-mishra1729/Pass-zenity/assets/84588156/c1f7c16e-cdb2-451c-8138-9336039c12f6)


### pass-show
Gives a list preview of all usernames
* Usernames are searchable
* After selecting usernames, the password will be copied to clipboard for 45 seconds.
![image](https://github.com/Anant-mishra1729/Pass-zenity/assets/84588156/55d3d6e7-b2cc-4b0b-bb2f-df455bb84cbb)


### pass-remove (Removes a password 🙂)
![image](https://github.com/Anant-mishra1729/Pass-zenity/assets/84588156/47024eac-eeb3-4280-a350-9a66527b538a)

