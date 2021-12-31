# Touche Pro
Touche Pro, a MSX Basic Game.

New remastered version by antor44, based on Esgrima by Antonio Millan - Abandonware

Meteor a free MSX Basic game, developed with default Basic, no assembly. 

How to play: Two players game, controlled with joysticks. You must touch the opposite 3 times, avoiding outs.


Repository for downloads:
https://github.com/antor44/meteor

Requirements:
-MSX 1/2/2+ Europe or USA BIOS

For MSX turbo R Europe or USA BIOS add this Basic line:

5 DEFUSR=39+PEEK(-2385)+PEEK(-2384)*256:IFUSR(0)THENLINE>0COPY0&H80F6OR384ALLYOURBASEAREBELONGTOUS!
