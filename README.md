# Touche Pro
Touche Pro, a MSX Basic Game.

New remastered version by antor44, based on Esgrima by Antonio Millan (Abandonware).

Touche Pro is a free MSX Basic game, developed with default Basic without inserting machine code.

How to play: Two players game controlled with keyboard and joystick 1. You must touch the opposite 5 times, avoiding outs (max 3).

Play online (includes Net Play for remote play):
https://webmsx.org/?MACHINE=MSX2E&ROM=https://github.com/antor44/TouchePro/raw/main/touche.rom


Repository for downloads: https://github.com/antor44/TouchePro


Requirements:

-MSX 1/2/2+ Europe or USA BIOS

-Or OpenMSX emulator with Basic ROM

-Or WebMSX:  https://webmsx.org/


For MSX turbo R Europe or USA BIOS add this Basic line:

5 DEFUSR=39+PEEK(-2385)+PEEK(-2384)*256:IFUSR(0)THENLINE>0COPY0&H80F6OR384ALLYOURBASEAREBELONGTOUS!
