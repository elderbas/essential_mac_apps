# essential_mac_apps


ICanHazShortcut
- Love this for binding custom CLI commands. 

Cli apps
BluetoothConnector
- great for connecting headphones

Create an .applescript for this and use with ICanHaz
```applescript
do shell script "open -a 'Mission Control'"
delay 0.5
tell application "System Events" to click (every button whose value of attribute "AXDescription" is "add desktop") of group 2 of group 1 of group 1 of process "Dock"
delay 0.5
tell application "System Events" to key code 53
```
to open a new workspace via keyboard shortcut


Spectacle (https://www.spectacleapp.com/)
- quickly snap windows into place on screen

Stay (https://cordlessdog.com/stay/)
- save and restore positions of your windows, even across multiple monitors
