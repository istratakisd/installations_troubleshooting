### This setup is used when installing a fresh debian 12

1. put user in sudoers: sudo usermod -aG sudo <username>
2. update Software
3. update from commandline
4. install flatpak from official site
5. complete uninstall libreoffice
    - `sudo apt update`
    - `sudo apt remove --purge libreoffice*`
    - `sudo apt clean`
    - `sudo apt autoremove`
6. complete uninstall firefox-esr
7. install from flathub
8. 
