# WSL (Virtual Machine)
This is an instruction on how to enable WSL2.

## Enable WSL2
If you're using **Windows 11**, WSL2 is already installed. You just need to enable it.

## Install Debian
Run the following command to install Debian.
```sh
wsl --install -d Debian
```

## Create a Username and Password
After installing Debian, the Terminal window will prompt you to create a username and password. Create one named `bos` or any username that you prefer.

## Update Debian
Inside Debian, run:
```sh
sudo apt update && sudo apt full-upgrade
```