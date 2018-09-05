# GIT

## Access Denied Error

Run the following:
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com" # this will create a unique key for your device to access the repo
```
When prompted to "Enter a file in which to save the key":
```
press Enter # this will accept the default file location
```
When prompted to "Enter passphrase":
```
press Enter twice # passphrases are not required
```
Go To File Location to View Key (.ssh)

Open Key With Notepad and Copy

Login to Gitlab > Settings > SSH Keys > new SSH Key #title the key something like "laptop" and paste the key in the text field

Click Save Keys

Now You Can Clone Repos Using the SSH Key instead of HTTPS!!
