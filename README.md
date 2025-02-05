# Tuxborn Lite on Steam Deck

## Writing in progress, please come back soon for the completed guide...

### Description

A basic guide on getting a 'lite' version of Tuxborn working on Valve's Steam Deck, along with my advice, warnings, and random thoughts.

### Preamble 

So, you wanna run a gigantic modified Skyrim install on your Steam Deck. You wanna do it with one of the big, famous load orders like Tuxborn, but you don't have an actual gaming PC to run Wabbajack. You also might be something of a masochist with a lot of time on your hands. Well, you're in good company. I'm not a modding god, I'm just an average guy with a the aforementioned traits. This is some advice from an average guy to the average person, accessibly.

This guide covers my journey to getting a reduced/'lite' version of the Tuxborn load order running on my Deck.

Note: This guide is not perfect or exact. I will not cover every glitch I encountered, only the major/CTD ones. I may also get details or processes wrong and will assume you are capable of basic debugging or Google-fu.

Above all else, I assume that you are patient—this process is long and often frustrating. It will pay off in spades, but only if you can handle it.

## Why a Reduced/'Lite' Version?

Tuxborn is designed with the Steam Deck in mind, but there are some challenges:

1. Wabbajack Requires a Windows PC
   - Tuxborn normally requires a Windows PC to prepare the installation before transferring it to the Deck. However, Wabbajack does not support Linux. This guide circumvents that limitation—every step can be followed natively on the Deck without a PC.
     - Recommended Hardware:
       - USB-C Dongle – To connect a keyboard and mouse (MnK)
       - Mouse & Keyboard – I found a Razer mouse at Goodwill for $1.50 and a nice clicky keyboard for $6. Don't give Bezos more money; support your local thrift store.
         - You can do it without MnK (using the touchscreen and keyboard invocation), but it will be painfully clunky.

2. No Supermodel NPCs
   - Tuxborn is a great load order, but it includes mods like CBBE and Himbo, which I personally don’t care for. Removing these mods also eliminates several dozen required compatibility patches, making the list:
     - More manageable ✅
     - More stable ✅
     - Easier to debug ✅
     - Leading to my next point...

3. Tuxborn is Huge
   - Tuxborn has over 1,500 mods, which significantly increases load times. My lite version has ~570 mods. It takes my Deck about 2 minutes to spin up from Mod Organizer 2 (MO2). A full Tuxborn setup takes much longer. If you're playing on a short commute, waiting for Skyrim to load might not be ideal.
   - A shorter list means:
     - Faster load times 🚀
     - Fewer patches needed 🛠️
     - Easier debugging 🔍

## The Overview

1. Install Skyrim
   - Ensure you have a clean install—no mods, no tweaks, nothing.
2. Start Skyrim once
   - Launch the game once and get to the main menu to generate .ini and config files. Close Skyrim afterward.
3. Install Mod Organizer 2
   - Download and install the Rockerbacon version of MO2 for Linux. Follow their instructions exactly, I ain't gonna regurgitate them.
4. Configure MO2
   - Set it up with your Skyrim install. When it asks for a clean prefix, ignore this and use the default setup. Details below...
5. Download & Install Mods
   - No real explanation needed, but I'll give some advice down below.
6. Test test test
   - Test often, every 10 mod additions or so. Some people will start a character and explore for a minute, but even loading to main menu is often enough to encounter major CTDs.
7. Repeat 5 and 6 until satisfied
8. Calibrate
   - Get your settings right - edit inis and cfgs for increased performance and stability.
9. Do some 'baby' playthroughs
   - Start a character, but don't get attached. Play for about half an hour, and try traveling the world and check for major issues or CTDs.
     - If you encounter any problems, check your logs and debug the problem. Start a new baby each time.
     - Yes, this is tedious as hell, but it's better to encounter the problems here than on your main character 100+ hours in. 
     - Take some time to experiment with your new mods functions. Tinker with the in-game MCM to experiment and see what you like and dislike. Remember your settings for your main playthrough.
10. Enjoy the fruits of your labor
    - Todd Howard you've done it again. Now go brag to your friends about the monstrosity you got running on your deck.
   

## 1 - 2
   - Not gonna elaborate on these, should be self explanatory
## 3
   - Download and install the rockerbacon version of MO2. Follow the instructions exactly. Make sure to install dependencies like 7z and protontricks.
     - If it is your first time in MO2, follow the tutorial to learn how the interface works.
## 4
   - When launching MO2, select SkyrimSE, and follow the on screen prompts. When prompted to do a clean prefix, DON'T. If you followed the above steps, you will have a clean prefix. Something about this check is not working right. Take the 'risk' and skip.
## 5 
   - Straighforward. Follow a LO you see online, even mine, and install the mods one-by-one. Tips and tricks:
     - Order is important in that it will make it easier for you to follow where you are. Put the LO on the right half of your screen, and MO2 on the left. Highlight the next mod, copy paste into a google search for the nexus listing, read the description, download, then load in through M02
       - You can make this even faster by downloading the mods directly to the directory where MO2 is reading them.
       - I ultimately paid for one month of Nexus premium for the faster download speeds- some mods like LOTD are **Massive** and a huge amount of your time will be spent waiting for the download otherwise. 
 



⚠️ Disclaimer

This guide is a work in progress. Expect mistakes, missing steps, and potential troubleshooting required. If you're attempting this, backup your saves and be prepared for trial and error.

Stay tuned for updates! 🚀
