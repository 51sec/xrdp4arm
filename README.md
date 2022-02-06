# xRDP4arm
Based on script from https://gist.github.com/jianping0754/869b3de0e79c738f368d38217aa233cf
This install.sh script will install xrdp, lxde, pulseaudio and create a remote rdp user for your Ubuntu 20.04 machine. It is compatible with ARM system.

# Running script to install desktop and xRDP with sound support on Ubuntu
wget https://cdn.jsdelivr.net/gh/51sec/xrdp4arm@main/install.sh && bash install.sh

If you already installed your desktop and xrdp with following similar commands:
- apt install xrdp -y
- apt install ubuntu-desktop

# Running scipt to add xRDP sound support
You can run this command to add sound support to your Ubuntu desktop:
wget https://cdn.jsdelivr.net/gh/51sec/xrdp4arm@main/install_xrdp_audio.sh && bash install_xrdp_audio.sh



