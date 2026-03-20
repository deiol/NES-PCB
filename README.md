# NES-PCB
Based on a request and discussion in this [r/NES thread](https://www.reddit.com/r/nes/comments/1rh8xvy/looking_for_replacement_powereject_boards/), I created a drop-in replacement for the Power/Reset PCB from the front-loader Nintendo Entertainment System.

[![Front image of NES-SW-01 board](/Images/NES-SW-compat_angled.png)](https://github.com/deiol/NES-PCB/tree/master/Images)

# PCB Differences
Taking a look at pictures online as well as NES consoles I had available, I realized there are at least two board revisions; NES-SW-01 and NES-SW-02 (if you've come across any other variants, please let me know). 

**NES-SW-01**
[![Front image of NES-SW-01 board](/Images/NES-SW-01_front.png)](https://github.com/deiol/NES-PCB/tree/master/Images)

**NES-SW-02**
[![Front image of NES-SW-02 board](/Images/NES-SW-02_front.png)](https://github.com/deiol/NES-PCB/tree/master/Images)

This design is based on the NES-SW-02 as it should be "backwards compatible" with the NES-SW-01.

Additionally, I used the same power switch footprint for the reset switch. This way you should be able to use either switch body type for the reset switch (although you'll want to use a momentary switch for reset, latching for power).

# Board Production
Board thickness is 1.6mm. [Gerber and drill files](https://github.com/deiol/NES-PCB/tree/master/Gerbers) are included in case they are helpful to anyone. They were created for production at JLCPCB following their gudiance on [generating Gerber and Drill files in KiCAD 9](https://jlcpcb.com/help/article/how-to-generate-gerber-and-drill-files-in-kicad-9). I only reference JLCPCB because I have used them in the past. You can of course have the board produced by a different manufacturer, some aspects of the board may need to be tweaked based on *their* requirements.

If you don't want to go through the trouble of getting boards manufactured, I may offer boards for sale. If/when I do, I will update this repo with a link.

# Disclaimer
I am not an electrical engineer, just a hobbyist. I couldn't find datasheets for any of the components, so the footprints were created from "scratch" using measurements taken with rulers and calipers. Similarly, the boards were measured with rulers and calipers and also compared against scans I took. Everything in this repo is offered as-is, use at your own risk.

**2026-03-19** - Currently the board design is untested, I plan on ordering some prototypes and will update this repo after I see how they turn out. I will try to make any adjustments to the files as needed.

