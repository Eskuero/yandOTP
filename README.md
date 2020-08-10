This is a small python wrapper I wrote around yad, gnupg and oathtool to automate the selection, decrypting, parsing and generation of a gpg encrypted backup that may come from your andOTP installation on your Android device using GTK dialogs.

This is useful if you would not rather use the GNOME Authenticator app, as it tries to store all the OTP seeds in the keyring, which is a bit tricky to unlock on the Pinephone.

# Installation
1. Copy the .desktop file from this repository to $HOME/.local/share/applications or to /usr/share/applications/
2. Copy the yandOTP python script to any directory that's included on your PATH
3. Install the dependencies depending on your distribution:

#### Debian
```
apt install oathtool gnupg yad python3
```
#### Arch Linux
```
pacman -S oath-toolkit gnupg yad python
```
## Screenshot

![How does it looks?](https://raw.githubusercontent.com/Eskuero/yandOTP/master/screenshot.png)

