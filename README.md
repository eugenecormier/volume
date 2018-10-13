This is my volume script. This turns the volume up/down or toggles mute and updates my AwesomeWM volume icon in my wibar. This was obviously coded with my current window manager in mind, AwesomeWM. Simply bind the hotkeys to this script.


Invocation
---------------
Turn it up: volume +

Turn it down: volume -

Toggle mute: volume m


Setup
---------------
Before running review the code and change the variables at the head of the file

'volumecommand' I wouldn't change this if I were you

'steps' is how many levels you want between min and max volume


Dependancies
---------------
This script requires the command 'amixer' to work (from alsa-utils)
