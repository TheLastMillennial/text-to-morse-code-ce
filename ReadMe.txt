Text to Morse Code (with screen flash)
v 3.47
By: TheLastMillennial

Thank you for downloading this program! Please note that this requires CE OS 5.2 or above to run.

Install:
1. Open TI-Connect CE
2. Connect calculator to computer
3. Go to the Calculator Explorer tab
4. Click on the icon with the arrow pointing out of the computer
5. Send all 3 .8xp files to your calculator 
Never done this before? Here is a complete tutorial on how to send any file to your calculator: 
https://www.youtube.com/watch?v=gwctk-E0XXc
Having issues? Here is a troubleshooting video that helps fix most errors:
https://youtu.be/-TweNnHuFCQ

How to convert text to Morse:
1. Run the program TXTMORSE
2. Select 'CONVERT TEXT TO MORSE'
3. Enter the string of Alphanumeric characters (spaces and periods are valid, any other character will be ignored)
4. Press [Enter]
5. Wait for it to convert
6. Enter the corresponding numbers to the option you want (1,2, or 3) then press [Enter]
7. Profit, the result will be stored in Str0

How to load a string of Morse:
*How to Load Str0:
1. Run the program TXTMORSE
2. Select 'LOAD MORSE'
3. Enter the corresponding numbers to the option you want. (nums 1,2, or 3)

*How to make your own Morse:
1. Clear the home screen
2. Press [Alpha]>[+]
3. Enter a . (period) for a dot, or a - (minus operative (not the negative sign)) for a dash
4. Press [sto->]
5. Press [vars]>[7]>[0]
6. Press [Enter]
7. Run the program TXTMORSE
8. Select 'LOAD MORSE'
9. Enter the corresponding numbers to the option you want. (nums 1,2, or 3)

To Uninstall:
1. Press [2nd]>[+]>[2]>[7]
2. Scroll down and delete (with [del]) TXTMORSE , SETLCD , and GETLCD 
(note a few of my other program may require SETLCD and GETLCD)

Change Log:
v 3.00
Initial release

v 3.10
Fixed bug where the program would error out if it encountered a 'W'
Fixed bug where the screen flash wouldn't loop
Also added countdown with instruction how to quit loop (clear)

v 3.20
Swapped the light changing program from prgmDARKNESS to prgmSETLCD
Included brightness saving feature so when you quit, your original brightness is set.

v 3.47
Adjusted flash length to be the offical Morse code length
Added support for white space and periods
Tweaked 'Converted' screen so it's more reader-friendly

Notable people:
Mainly _iPhoenix_ who highly optimized my code!
MateoC who greatly helped me with my C code!
And everyone on Cemetech who supported me through development!


Questions, concerns, land mines, or bugs?
Contact me here: https://www.cemetech.net/forum/viewtopic.php?t=14138