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
