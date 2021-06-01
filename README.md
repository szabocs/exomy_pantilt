This repository contains all the files for the pantilt modification of the exomy rover (see https://esa-prl.github.io/ExoMy/ for more details) and the parts modified for mg996r servos.

The pantilt parts are a remix of  https://www.thingiverse.com/thing:1799905 so credit to Zalophus for his work. 
It was modified for Tower Pro MG90s servos and to allow the camera flat cable to be inserted through the base into the rover's mast and allow for the camera's movement.
The holes on base were modified to fit the mast. 
50cm raspberry pi camera cable and 2 MG90s servos are needed.

The pan tilt software allows for almost 180 degrees movement of the camera in the horizontal and vertical plane and has pan tilt controls for the camera in the web GUI.
Also the video feed is flipped when the camera moves above 90 degrees vertically (basically looking back) to keep the correct video orientation in the Web interface.

Additionally it is possible to control the camera via a PS2 game Controller using R1/R2 and L1/L2 buttons.
Possibly works also with Xbox One or other controllers but it was not tested for lack of appropriate hardware.

There is an issue that the MG90s servo in some cases vibrate, as a workaround the vibration can be stopped by grabbing the camera for a short time.
The cause is not clear for the moment.

This is work in progress.
