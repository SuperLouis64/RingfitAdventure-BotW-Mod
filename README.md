# Ringfit-BotW
Using a Ring Fit Adventure mod for The Legend of Zelda: Breath of the Wild! This allows the user to attempt to play BotW on the switch with IRL exercies. Run to move in-game, squat to use the menus! What can go wrong? If you end up using the mod for YouTube, Twitch, etc, all I ask is to be credited, don't be a jerk about it. Hit me up at <https://twitter.com/SuperLouis_64>

### Overall Design of the Mod

The idea is to try get some of the excerises from Ring Fit Adventure to work with the inputs of BotW, here is what the mod can do so far:
- The Joystick is locked behind jogging. Once the user jogs/runs in palce, they are allowed to move in-game
- Swinging the Ring-con/joycon activates the attack button.
- Squatting will open up the pause menu if you press the "+" button and squat at the same time
- The face buttons on both joycons will still work!

### Hardware Needed
This mod needs some hardware to get running. I have a full tutorial on my website if you need more information: <https://www.controllerbend.com/ringfitbotw.html>
- Titan Two Input Converter
- RingCon and Legstrap (not needed but helps)
- Titan Two Wireless Expansion Kit

### Software Needed
To interact with the Titan Two, you'll need to download Gtuner IV. "Gtuner IV is the main software for programming, updating and configuring the Titan Two device, featuring an complete IDE with integrated compiler for the GPC script language. Gtuner IV also provides user friendly interfaces for easy download, configure and use gamepacks or user made scripts. Based in a modern framework, Gtuner IV supports multi-platform, high resolution monitors and localization" - ConsoleTuner's site. 
- Download the software here: <https://www.consoletuner.com/titan-two-downloads/>
- Make sure to read over how the hardware/software works on the website. It'll save you a good amount of headaches.

### How to Set-up the Mod
I have an old video that shows a how to set-up the mod. It will be updated for the current mod on the <https://www.controllerbend.com/ringfitbotw.html> site once it's ready. YouTube Video: <https://www.youtube.com/watch?v=HYn3pWXMPF8>
1. Connect your Titan Two to your Switch via the OUTPUT port
2. Connect your Titan Two to your PC via the PROG port
3. Open up the Gtuner IV software
4. Load the RingFit_BotW.gpc file to the Gtuner IV GPC Script IDE
5. Connect your joycons to the Titan Two via the Device Configuration tab on the right side of the UI. (Use the "Wireless Bluetooth Pairing" button after activating the JoyCons Sync Button")
6. Turn on your Nintendo Switch and launch BotW
7. Press the Green "Test and debug" Arrow on Menu file
8. Workout to your heart's content!

### FAQ
- Q: Do I need the Wireless Expansion Kit?
- A: Yes, you can't connect to your Joycons without it

- Q: It seems a bit janky with running and squating, what's the issue?
- A: Check out the magic numbers, you'll have to change some digits in the ACCEL_1_Y) > -20.00 or get_val(ACCEL_1_Y) < -30.6) areas to get it to work for you. Also this isn't a complete 1:1 from Ring Fit adventure, just my attempt to replicate it as a single person. Remember, it probably took a team and a half years of work at Nintendo to do this. I'm just one person doing it for free.

- Q: I'm having issues settings things up, what am I doing wrong?
- A: Shoot me a message on twitter on <https://twitter.com/SuperLouis_64>, the Titan Two is hard to set up the fist time.

- Q: This is a bit expensive, is there a cheaper option?
- A: At the moment no. I'm working on an Arduino version that will hopefully make it way way cheaper but until then, this is the only method I know how to make this work! Sorry.
