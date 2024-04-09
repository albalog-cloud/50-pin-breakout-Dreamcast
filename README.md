# 50-pin-breakout-Dreamcast

50 pin breakout board for Sega Dreamcast:

This PCBA is a breakout board that converts the VA0/VA1 style 50-pin BTB connector (as found on their motherboards) to 50 wire pin headers. This is the connecter that the GDEMU and similar devices use.

In theory, this device could get a VA2 revision Dreamcast working with a GDEMU, but I can't make any promises. 

The wires are to be soldered to the corresponding number on the breakout board. Then, the other end of the wires are to be soldered to the Dreamcast's motherboard itself. For example, “A9” on the breakout board will have a wire soldered to it, going into the spot on the Dreamcast's motherboard that you desire “A9” to be.

This project I release under free use/open source, so anyone is free to use or modify it. The zip file is a 
gerber that can be previewed in KiCAD, then exported so it can be edited to your liking in KiCAD.

The reason why I am deciding to release this is because I can't find the 50-pin BTB connector from anybody for a reasonable price, and some suppliers I have suspicions. The part is in the BOM, and it is “Molex 526020579” and it is easy to search up. It's the exact part that the VA0/VA1 motherboard uses. It appears to be a discontinued part (???), and so far I could only find one supplier that had any. This supplier I found suspect because of how many 526020579's they claimed to have at a rediculous asking price.

My files include the gerber zip, BOM and CPL for the breakout board.

I hope someone finds my PCB adventure useful, because I am facing a roadblock for the 50-pin BTB connector.
