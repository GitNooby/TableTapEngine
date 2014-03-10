TableTapEngine
==============

4th year design project made by Kevin, Keith, Max

See the demo here:
https://www.youtube.com/watch?v=P9VFogw5XrA

Google Code repository (this has even more stuff like the prototypes, documentation, and data collected and analysized with Matlab!): https://code.google.com/p/super-nb-project/source/checkout

Yes, the UI looks bad, but it works :).
It mostly looks bad because it was built with old XCode IB layout, now the storyboard stuff screwed up everything :(.
Yes, the code might look messy, but we did use a design pattern, you just don't see it ;)

Information:
This app allows the user to play musical notes by taping on a surface.

step 1: set the number of musical notes you want (default is 8)

step 2: set the number of calibration points per note (default is 1)

step 3: press the start button

step 4: once you see "waiting for tap" on screen, tap at a location on the table. For every note, you'll have to tap the number of times you had set for calibration points
(For example: if you selected 8 notes with 1 calibation point per note, then tap ONCE at EIGHT DIFFERENT locations)

step 5: once calibation is complete, you can tap at any of the selected locations and the app should play back the corresponding note
