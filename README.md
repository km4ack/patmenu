# Pat-Menu
Experimental code to create an easy to use menu system for Pat Winlink. This is designed to make it easier to get all of the needed componets loaded and ready to make a connection using Pat.
It will also aid in finding ARDOP stations to connect to and shut down Pat and related components once you wrap up.

This is still considered ALPHA code. Things may or may not work for you. It has only been tested with the signalink and wolphilink sound card but should work with any USB sound card that uses VOX to trigger the radio.

# INSTALLATION

move to your download directory

cd ~/Downloads

download the patsetup file

wget https://raw.githubusercontent.com/km4ack/Pat-Menu/master/patsetup

make setup file exec

sudo chmod +x patsetup

run the setup file

./patsetup

Once setup is finished, start the menu with

patmenu
