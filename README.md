# Zoom Participants Only View
* Instructions to allow the viewing of the participants list from the Zoom Web client on a Windows/Mac Google chrome browser.  
* There are some optional instructions to setup Spacedesk to use an IPad or phone as a secondary monitor (via WIFI), to allow the user to view the participants list on an Ipad/phone.

## Setup
### Zoom
* [Connecting using the zoom web client](https://gist.github.com/ahlkhoo/b0d12229f6343d5cf048e06e54dab4e6)

### Tampermonkey on a PC/Laptop with Google Chrome
* Tested to work on Google Chrome Version 100.0.4896.88 (Official Build) (64-bit).

#### Install Tampermonkey 
* Launch Google Chrome (make sure to update the latest version).
* Get [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en).  Follow the prompts.

#### Install Userscript
The userscript removes the video section of the Zoom web client and activates the participants list.  It also zooms in the browser by 200%, thereby increasing visibiliy of the names of the participants, and also if the participant raises his/her virtual hand.

* Get the [Tampermonkey - Zoom Participants only user script](https://gist.github.com/ahlkhoo/fcf9a3a07fb308e956bcc973df5bf076)
* Create a new script via the Tampermonkey menu.
* Copy the userscript in the gist above into the Tampermonkey userscript and save.

## Putting it all together
* Open a new Zoom web client.
* Key in your username (and password, if needed).

## Optional
Installing spacedesk on the PC and the spacedesk client on the Ipad/phone allows you to use the ipad/phone as an additional monitor, albeit connected via wifi.  You can then move the modified Zoom web client browser window to the IPad.  This is done as Tampermonkey does not have a version that runs on Google Chrome on IOS.

### Spacedesk
* [Installing Spacedesk tutorial](https://www.youtube.com/watch?v=5E-Jk_JD5dY)
* [Spacedesk download](https://www.spacedesk.net/#download)
* [Spacedesk Documentation](https://www.spacedesk.net/user-manual/)
