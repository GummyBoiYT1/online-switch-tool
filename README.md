Notice: this has been barely tested, if you're willing to run this with your PC and modded switch please hit me up on discord: gummyboiyt

I'd love to test and play with you


# online switch tool
Ever wanted to play smash or other switch games natively with your friends over the internet
But they don't have online? a switch? only a shitty PC?
This tool is for you!

Convert parsec / controller /keyboard input from your PC straight to your homebrewed Nintendo Switch.

REQUIRED:

| Modded Switch with custom firmware

| sys-hidplus installed in said switch

| Python, and all modules in requirements (install pip install pygame pillow sounddevice numpy opencv-python mss pygetwindow)

| Or if theres an .exe just run main

| A switch game that supports 4 or more players

OPTIONAL:

| A way to stream your switch stream to your friends, so players can see your game via parsec

| SysDVR is great for this (with required patches)

INSTRUCTIONS:

| Go to your Internet settings in your switch. Write down where it says 'IP Address'

| Run main.py from your terminal (or exe if you have it)

| Port forward UDP 9000 9001 and 9002
| Add how many players you would like to run with the options

| click connect.

| in a few seconds all the controllers will connect to your switch.

| set your friends controllers to the virtual switch controllers

| Fair Warning: the client will share your entire desktop. Check the box if you dont want that to happen.

| Enjoy!

NOTICABLE PROBLEMS:

| If your wi-fi isnt all that good, your guests will have input lag. Thats it.

| 5+ controllers gets unstable. frequent disconnects and sometimes breaks sys-hidplus and you will have to restart your nintendo switch.

| Closing the app without clicking 'Disconnect' will not remove all the controllers. Use the disconnect button when stopping your play session.


Keyboard mappings (customizable):

WASD - move

j - A Button

k - B Button

u - X Button

i - Y Button

q - Minus Button

e - Plus Button

Arrow keys - DPAD

l - L Button

r = R Button

o = ZL Button

p = ZR Button
