# Pat-Menu
Pat Menu is an easy to use menu system for Pat Winlink. It is designed to make it easier to get all of the needed componets loaded and ready to make a connection using Pat.
It will also aid in finding ARDOP stations to connect to and shut down the modems once you wrap up.

This is still considered BETA code. Things may or may not work for you. It has only been tested with the signalink and wolphilink sound card but should work with any USB sound card that uses VOX to trigger the radio.

# Known Bugs BEWARE!!
If multiple stations are available when trying to add a packet station to your alias list, selecting any of the stations will corrupt the pat config file. https://github.com/km4ack/patmenu/issues/23

# Videos
[![IMAGE ALT TEXT](http://img.youtube.com/vi/xXJsJKgU-mc/0.jpg)](http://www.youtube.com/watch?v=xXJsJKgU-mc "Pat Menu Overview")

[![IMAGE ALT TEXT](http://img.youtube.com/vi/unal5dCKGXk/0.jpg)](http://www.youtube.com/watch?v=unal5dCKGXk "Pat Menu Install & Configure")

# Issues
Please report any bugs/issues with the menu https://github.com/km4ack/Pat-Menu/issues

# Install
    git clone https://github.com/km4ack/patmenu.git $HOME/patmenu && bash $HOME/patmenu/setup
    
Be sure to update the config file before launching the menu for the first time.

Once setup is finished, start the menu using the new icon on the desktop. Double click and then choose "Execute in Terminal"
