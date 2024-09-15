# HEC1802
A redesigned 8 bit computer from the late seventies running CHIP-8.

Originally designed by Hugh Anderson and Graeme Teesdale it was published in kit form for the Australian publication Electronic Today International (ETI), called "A Learner's Microcomputer" issues May - November 1981.

The kit back then comprised of as CDP1802 as CPU, 1 Kb rom (0000 - 03ff) and upto 3 Kb of ram (0400 - 0fff) , a MC6821 for input on a hexadecimal keypad and a CDP1864 for the PAL Color Video, Sound and Clock.
Since the rarity of the CDP1864, this project is designed around the CDP1861 Pixie, CDP1862 Color, and CDP1863 Programmable frequency chips, whch is essenstially the CDP1864 combined but not without slight differences.
  1. The 1861 is NTSC.
  2. The 1861 has a smaller video resolution of 64 x 32 and not the 64 x 48 offered with the 1864.
  3. An increase of logic chips to "glue" the three discrete CDP chips.

This project comprises of 2 versions of the computer, full blown color using the 1862 (1.07) and a B/W version without the 1862 (1.06).


The software binaries are a collection from Jim Modrouvanos and Marcel van Tongeren and batch converted to Intel Hex and Wav by python scripts.



