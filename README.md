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
After restarting your PC, a Terminal window will prompt you to create a username and password.

## Update Debian
Inside Debian, run:
```sh
sudo apt update && sudo apt full-upgrade
```