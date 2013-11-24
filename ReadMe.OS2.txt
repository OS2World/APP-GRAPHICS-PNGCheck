   pngcheck-1.99.3 binary for OS/2

I compiled pngcheck.exe using Innotek GCC-3.2.2beta4 CSD1 and
Makefile.os2 contained in this package. I used the Z-compression
library build from Innotek's GCC page. Because of rapid changes
in the Innotek C-Libraries (thanks for the great work, Knut!) I 
chose to create a static but large executable file that I then
sent through lxLite...
The other files in this package are inherited from the original 
source ZIP file, that I got from 
   http://www.libpng.org/pub/png/apps/pngcheck.html

Because the original README does not really say what this program
does, I repeat the text from the above webpage:
   pngcheck verifies the integrity of PNG, JNG and MNG files (by
   checking the internal 32-bit CRCs or checksums) and optionally
   dumps almost all of the chunk-level information in the image in
   human-readable form. For example, it can be used to print the
   basic stats about an image (dimensions, bit depth, etc.); to
   list the color and transparency info in its palette; or to
   extract the embedded text annotations. All PNG and JNG chunks
   are supported, plus almost all MNG chunks (everything but PAST,
   DISC, tERm, DROP, DBYK, and ORDR). This is a command-line program
   with batch capabilities (e.g., ``pngcheck *.png'').

Peter Weilbacher <mozilla@Weilbacher.org>, 04Oct2004