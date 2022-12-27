#!/bin/bash

# Apt

sudo apt update
sudo apt upgrade -y
sudo apt install build-essential -y
sudo apt install flatpak -y 
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.mozilla.firefox -y 
flatpak install flathub org.mozilla.firefox -y 
sudo apt install youtube-dl -y
sudo apt install vanilla-gnome-desktop -y
sudo apt install gnome-software-plugin-flatpak -y
sudo add-apt-repository multiverse -y
sudo apt update -y
sudo apt install steam -y
sudo apt install gparted -y

# Flatpak

flatpak install flathub org.mozilla.firefox -y 
flatpak install flathub org.chromium.Chromium -y 
flatpak install flathub com.visualstudio.code -y
flatpak install flathub org.videolan.VLC -y
flatpak install flathub com.mattjakeman.ExtensionManager -y
flatpak run org.onlyoffice.desktopeditors -y
flatpak install flathub com.mojang.Minecraft -y
flatpak install flathub org.libreoffice.LibreOffice -y
flatpak install flathub com.github.micahflee.torbrowser-launcher -y
flatpak install flathub com.bitwarden.desktop -y
flatpak install flathub com.rtosta.zapzap -y
flatpak install flathub org.openshot.OpenShot -y
flatpak install flathub com.github.robertsanseries.ciano -y
flatpak install flathub com.jgraph.drawio.desktop -y
flatpak install flathub com.endlessm.photos -y
flatpak install flathub com.github.IsmaelMartinez.teams_for_linux -y
flatpak install flathub com.github.philip_scott.spice-up -y
flatpak install flathub com.github.childishgiant.mixer -y
flatpak install flathub com.raggesilver.BlackBox -y
flatpak install flathub app.ytmdesktop.ytmdesktop -y

# Snap


