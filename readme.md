# JDXI-manager Linux installation

http://jdxi-manager.linuxtech.net/linux.html     


On Ubuntu / Debian derived distros you can install the prerequisites with the following commands in a Terminal window:

'''sh
sudo apt-get update
sudo apt-get install perl-tk
sudo apt-get install libconfig-simple-perl
sudo apt-get install libgd-perl
sudo apt-get install libtime-hr-perl
sudo apt-get install libwww-perl
sudo apt-get install libasound2-dev
sudo apt-get install build-essential
cpan -fi MIDI::ALSA
'''

Please note: when running the last command (cpan -fi MIDI::ALSA) you will be prompted a few times, simply hit [Enter] each time to accept the default choices.
