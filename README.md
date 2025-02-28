# Draconic-ComputerCraft-Program
Computercraft menu for the reactor on Draconic Evolution mod

Setup 3x3 monitor.
Computer needs to be directly touching Reactor Stabilizer and the output Flux gate

Monitor and Input flux gate needs to be connected via wired modem if not the program would not work.

![Base Profile Screenshot 2021 05 15 - 16 03 07 46](https://user-images.githubusercontent.com/62036454/118366137-62f75e80-b597-11eb-9d23-d814ce544513.png)

The screenshot above shows how the computer must be for the program to work. Doesn't matter where the flux gate or the reactor stabilizer is positioned longs is physically touching the computer. The program automatically detects which side is the flux gate and reactor are touching on the computer.

![Base Profile Screenshot 2021 05 15 - 16 03 19 94](https://user-images.githubusercontent.com/62036454/118366149-6ab70300-b597-11eb-8e45-36ac90727b28.png)

The screenshot above shows how the input flux gate is connected to the computer. Its using wired modem to connect to the main computer. The computer automatically changes rf/t input that goes in the reactor to get field strength to 50% longs there power going in it should be able to keep it there. If the computer can't keep the reactor over 15% the computer will shut the reactor down and produce a warning on the screen to tell the user why it was shutdown.

![Base Profile Screenshot 2021 05 15 - 16 02 59 50](https://user-images.githubusercontent.com/62036454/118366126-5a9f2380-b597-11eb-8741-ba985d542155.png)

The screenshot above is the monitor. Tells the user all the stats plus some buttons to control the reactor with. Soon I'll update this to make you able to manually set the input flux gate yourself but right now it does this automatically to get 50% field strength.

Pastebin Code:
Keep this as startup so if there any updates to the program it automatically updates the files and runs the program

>pastebin get kEyUTRqM startup

Credit to acidjazz for f API and some of the code to make this work.
