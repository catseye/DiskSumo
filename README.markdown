DiskSumo
========

**DiskSumo** is a Commodore 64 BASIC program to dump an image of the
floppy disk in unit 8 (assumed to be a 1541 disk drive) over the RS-232
port via the XMODEM protocol.

The file downloaded on the other end of the connection is usable as-is
as a `.d64` disk image file.  Note, however, that it won't be able to
transfer anything sensible from disks which use copy-protection schemes.

This is the program I used to transfer my old C64 diskettes to my PC
(and in fact, I concocted it for that purpose) at some in the mid-aughts.
So it can be thanked, for example, for the existence of [Bubble Escape 2K][].

I implemented the XMODEM protocol based on a description of it on a
printout I had made of a posting on a Winnipeg BBS a decade and a half
earlier.  I no longer have the printout, but I believe the posting was on
_Eric the BBS_, and the poster was Bruce Walzer.

Since I transferred all the disks that I could (and since I no longer have
a physical Commodore 64, and since it is of little use on an emulator) I no
longer have a need for this program.

If you have a need for this program, then the first hurdle you will have
to overcome is getting it onto your Commodore 64 in the first place.  You
will probably need to type it in.

The name "DiskSumo" started life as a typo for "DiskDump".

[Bubble Escape 2K]: http://catseye.tc/projects/bubble-escape/
