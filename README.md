# WSL (Virtual Machine)
This is an instruction on how to enable WSL2.

## Enable WSL2
If you're using **Windows 11**, WSL2 is already installed. You just need to enable it.

## Install Ubuntu
Run the following command to install Ubuntu.
```sh
wsl --install
```

## Create a Username and Password
After installing Ubuntu, the Terminal window will prompt you to create a username and password. Create one named `bos` or any username that you prefer.

## Update Ubuntu
Inside Ubuntu, run:
```sh
sudo apt update && sudo apt full-upgrade
```