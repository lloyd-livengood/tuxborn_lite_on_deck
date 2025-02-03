# tuxborn_lite_on_deck


Writing in progress, please come back soon for completed guide....

DESCRIPTION: A basic guide on getting a 'lite' version of Tuxborn working on Valve's Steam deck, along with my advice, warnings, and random thoughts.

PREAMBLE: So, you wanna run a gigantic modified Skyrim install on your Steam deck. You wanna do it with one of the big, famous LOs like Tuxborn, but you don't have an actual gaming PC to run Wabbajack off of. You also might be something of a masochist with a lot of time on your hands. Well you're in good company. This guide will cover my journey to getting a reduced/'lite' version of the tuxborn LO running on my deck. 

First, note that this guide is not perfect/exact. I will not be covering every glitch I encountered, only the major/CTD ones. I may also get details or processes wrong, and am going to assume that you are capable of basic debugging or google-fu. 

Above all else, I assume that you are *patient*; this process is long, and often frustrating. It will pay off in spades, but only if you got the snuff. 

So some of you will be asking:

Why reduced/'lite'? Isn't tuxborn tailor made with deck in mind?
  Yes it is, however there are some hiccups: 
    1) It requires a PC on which do do all of the work. 
      You ultimately migrate everything onto your deck, but Wabbajack does not have linux capability.
      I did this guide on my own to circumvent this- every step can be followed natively on the deck
      without a PC. You will however want the following:
        -USB-C dongle- to connect MnK
        -Mnk: I found a razor mouse at Goodwill for 1.50$, and a very nice clicky-clacky for 6$. 
        Don't give Bezos any more money, patronize your local thrift instead. You *can* do it without MnK 
        (with the touch screen and keyboard invocations), but it will be agonizingly clunky.
    2) You don't want every NPC in the game to look like a super model
      Tuxborn is a great LO, however it has a lot of mods that have personally little appeal to me- 
      CBBE and Himbo namely. My list does not include these mods, among others.
        Additionally, these mods also require a lot of compatibility patches to run- removing these
        haves several dozen mods off the list, making it much more managable. 
        I replaced them with some much more simple and accessible replacements. 
    3) Tuxborn seems... like really big.
      The game takes increasingly long to spin up the more mods/plugins you run...
      My reduced LO takes my deck about 2 minutes to fully spin up from MO2, and it comes in at about 570 mods. 
      A full tuxborn LO has north of 1500 mods. It runs great *once* spun up, but this is clunky.
      Playing deck on the bus could be tricky if the game isn't done spinning up by the time your ride is over.
      Shorter list is more stable, faster to load, requires fewer patches, and easier to debug/diagnose problems in.
    

First, let's start off with a high-level overview:
  1) Install Skyrim: must have a clean install- no ifs, ands, or buts.
  2) Start Skyrim and get to the menu to initialize inis and configs. Close once done. 
  3) Mod Organizer 2: download and install the rockerbacon version of MO2 for Linux.
  4) Configure M02 with your Skyrim Install: it will ask you for a clean prefix, ignore this and use as-is.
  5) Download and Install Mods: should need no explanation.
  6) 
