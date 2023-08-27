# CPU

### CPU die shots, microscopy, recognition, images, research; CPU archeology; CPU aesthetics; silicon chips; history

## Unknown CPU or other? chip - should be from 1994-1996?

27.8.2023

**WANTED!**

Do you recognize this CPU? Call me if you have any information. :) Higher quality images of the suspect to come!

![image](https://github.com/Twenkid/CPU/assets/23367640/53c7aeb9-fb11-4739-ba6a-2ff56a44acaa)

This is own work. The sample should be from the mid 1990s, it seems maybe about 0.6 microns+- feature size. The die size is about 180 mm2 or ~ 14 x 12.8 +-. I can't find a chip with similar size, the known Pentium are different.

I tried to count the connectors in order to classify the socket, they are ambiguous but they seem that they could be ~ 237-238 for a 486 socket or something else similar, but chip doesn't look like any 486 I've seen. Pentium is 321 etc.

I can't recognize it as any Pentium or Pentium Overdrive from whatever I've seen (P5 is different, reddish and bigger; P54C is smaller and more golden etc.). It's not K5 (they are rectangular and shiny), not any 486 I know (Cyrix are square, they have two typical rectangles; AMD Am486 or 586 also have other patterns and are not so big)/

I guessed it could be some more rare Cyrix 5x86, but it's not (there's one 144 mm2). It doesn't look like a Cyrix 6x86, nor AMD 5x86, nor NexGen 5x86 which was unlikely as it was too rare, nor Winchip (at least the ones I've seen). 

The PowerPCs from the time are different as well (601, 603, 604).

Have't recognized it as other known CPUs and the chip is too big.

Could it be some special 486 and the 8-square pattern to be an advanced type of cache (the 2 square type split?).

Or could it be a DSP chip, due to these multiple units? Also these rare (unseen) for CPU diagonals/triangular pattern of connection?

Oh, yes! Just as I was writing the post*, I found it!

It seems it's a Texas Instruments DSP processor, TMS320C30

A die shot by Birdman:

![image](https://github.com/Twenkid/CPU/assets/23367640/aff3a69d-7c68-407e-baf5-da4a6193fe59)

https://www.cpu-world.com/forum/viewtopic.php?p=186280

https://www.cpu-world.com/forum/viewtopic.php?p=187412&sid=D40VDjkRxRaqWE0C.PxTDNd8FPnRKGnwHL4iJi.3kV1OttQ.FmVzvGrK7VKIG3vY#187412
PostPosted: Fri Feb 28, 2014 4:12 am    Post subject: Second TI DSP special	Reply with quote
Aberco sent me more TI DSP dies, so here are die shots of some of them:

## Texas Instruments TMS320C30 DSP

:)

Final search path after a lot of research and revisits of CPUs:

I thought of an unlikely possibility of a very early 486, thus a bigger die, but the features would probably look differently at 1 um.
Anyway I searched:

486 DX cpu die
https://www.google.com/search?q=486+DX+cpu+die&sca_esv=560532532&sxsrf=AB5stBhqLnUedY7pu9-ZKQPmGP93owHNNg%3A1693166747350&ei=m6zrZJOAFeKpxc8P-pOq2A8&ved=0ahUKEwjTuZXU0f2AAxXiVPEDHfqJCvsQ4dUDCBA&uact=5&oq=486+DX+cpu+die&gs_lp=Egxnd3Mtd2l6LXNlcnAiDjQ4NiBEWCBjcHUgZGllMgUQABiiBEj7GVCvB1iTF3ADeACQAQCYAYMBoAHNA6oBAzEuM7gBA8gBAPgBAcICCxAAGIoFGIYDGLADwgIKECEYoAEYwwQYCuIDBBgBIEGIBgGQBgQ&sclient=gws-wiz-serp

I revisit a page which I've visited:

The Ultimate AMD 486 Die & Packaging Guide

X86.FR
https://x86.fr › the-ultimate-amd-486-die-packaging-g...
486 DX cpu die from x86.fr
350nm / 16KB – The latest and most advanced 486 die from AMD, a shrink down to 350 nm. While being almost the same 486 core as before, it now integrates 16 KB ...

Also I queried a 150 MHz 486 (I remember AMD had one, maybe that was they 5x85 however, also 180 MHz; anyway)

https://x86.fr/the-ultimate-amd-486-die-packaging-guide/
Am486 150 die shot
https://www.google.com/search?q=Am486+150+die+shot&oq=Am486+150+die+shot&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQABiiBDIHCAIQABiiBNIBCDQwNDhqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8#imgrc=wYt05L4KhyGNRM&imgdii=Yri1MDzkznAkHM
View topic - My first attempts to take die shots

I realized that I could ask on the cpu-world forum, I noticed one interesting topic in the top results:

CPU-World
https://www.cpu-world.com › forum › viewtopic
Am486 150 die shot from www.cpu-world.com
Jun 7, 2013 — Anyway, I tested taking die shots by simply keeping the camera on ... AMD Am486 DX4 (Enhanced version with 8 KiB write-back cache, 500 nm):
15 posts
 
After a bit of scrolling there were DSP chips, I realized that it could be so. 
 
Thanks to the photographer!

* First I was about the ask on StackExchange Electronics, but usually the answers there are nasty, LOL so I skipped.
cpu-world seems a better place
* My picture is taken with a Scanner at 1200 dpi :) (Canon Pixma MP240)
