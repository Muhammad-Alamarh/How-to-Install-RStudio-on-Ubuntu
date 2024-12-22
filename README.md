# How-to-Install-RStudio-on-Ubuntu
Below are the steps to install RStudio on Ubuntu using the .deb installer file:
1. Download the Installer File
Download the .deb installation file for RStudio from the official website. You can visit the following link to get the file:
[Download RStudio](https://download1.rstudio.org/electron/jammy/amd64/rstudio-2024.12.0-467-amd64.deb)
2. Install Required Dependencies
Before installing RStudio, ensure that R is installed on your system. You can install it using the following command in the terminal:
```bash
sudo apt update
sudo apt -y install r-base gdebi-core
```
4. We need to install the gdebi package if it's not already available. This tool simplifies the installation of .deb packages, like RStudio, by automatically resolving dependencies during the installation process. It also provides a user-friendly graphical interface for managing .deb packages.
```bash
sudo apt install gdebi
```
5. Now we can proceed with the direct installation of the file.
![Screenshot From 2024-12-22 14-06-23](https://github.com/user-attachments/assets/873d8718-d3be-477d-a621-ebcc5c1f9c8c)
![Screenshot From 2024-12-22 14-07-18](https://github.com/user-attachments/assets/331ff207-1f52-4eb7-a7ee-18b6d1222aa9)
![Screenshot From 2024-12-22 14-07-49](https://github.com/user-attachments/assets/c969013f-df4a-4d55-8801-4938aa5d3727)









