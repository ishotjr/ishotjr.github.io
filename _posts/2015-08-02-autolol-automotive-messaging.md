---
layout: post
title: "AutoLOL Automotive Message System"
date:   2015-08-02 21:42:42
# categories: 
---

In 2002, I had a thought: wouldn't it be great if you could convey messages to other drivers with greater precision than the established turn signal and *gesture-based* conventions? This was the era of texting on dumbphones, before emoji or social media apps or any of the other ways that we can now more expressively convey our feelings than with raw text. Thus, I had the idea for a simple system (whose road legality I have yet to investigate) whereby emoticons could easily be displayed to other drivers to convey apology, thankfulness, or...whatever the situation required. Back then I had absolutely no hardware skills, having focused my schooling and professional career on bits rather than atoms - so it's incredibly validating to be able to knock out a quick PoC in a few hours today, using materials on hand and a few lines of code, instead of such ideas remaining dreams... :D

I combined [@jprodgers's](https://github.com/jprodgers) [LoL Shield](https://github.com/jprodgers/LoLshield) with the inexpensive and hackable (e.g. ability to opt out of the pin 13 LED [in order to prevent ghosting](http://jimmieprodgers.com/kits/lolshield/diavolino/)) [Evil Mad Scientist Diavolino](http://www.evilmadscientist.com/2010/diavolino/) and strapped a 4xAAA (NiMH, in order to avoid additional voltage regulation) battery holder to the back, resulting in a self-contained, portable solution that can easily be attached to my car's rear wind deflector for a few days of [visibility testing](https://github.com/ishotjr/AutoLOL/blob/f630edecfde55df5a65879cd4650959a6ea885a4/AutoLOL.ino#L24) (the bright white LEDs are easily visible from a distance, even in direct sunlight)... :)

![AutoLOL v0.1](/img/AutoLOL/AutoLOL-0.1.gif "Honk if you can read this - thanks!:)")