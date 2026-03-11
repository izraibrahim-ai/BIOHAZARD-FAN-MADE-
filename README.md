# BIOHAZARD-FAN-MADE-
This is a resident evil game made for termux (not official capcom) a game similar to Resident Evil but a fan made version 
# Tutorial on how to install it in termux 
open termux 
# install the .zip file
pkg upgrade && pkg update -y
pkg install git -y
pkg install python3 -y
git clone https://github.com/izraibrahim-ai/BIOHAZARD-FAN-MADE-.git

# enter the directory
cd /sdcard/Download or cd /storage/Download

# copy file .zip
mv BIOHAZARD_ZERO.zip ~/
cd ~/
# install unzip 
pkg update && pkg upgrade -y
pkg install unzip -y

# unzip the file
unzip BIOHAZARD_ZERO.zip 
# play the game
cd BIOHAZARD_ZERO
python3 main.py
