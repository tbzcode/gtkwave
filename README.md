# gtkwave
GTKWave is a fully featured GTK+ based wave viewer for Unix and Windows which reads LXT, LXT2, VZT, FST, and GHW files as well as standard Verilog VCD/EVCD files and allows their viewing.

## Original gtkwave V/S this forked project

**Common for gtk2 and gtk3** 
* Added 14 new trace colors. Now total 21 colors are available to choose.

**gtkwave3-gtk3**  
* Removed MAC-style "single button vertical" memubar. GTKWave window will have Windows-style horizontal menu bar.
* Make line width configurable from rc file (rc variable: use_fat_lines). Enter line width in resolution of 0.1  
Example:  
&ensp;&ensp;```use_fat_lines 1.5```  
&ensp;&ensp;```use_fat_lines 2.0```  
&ensp;&ensp;```use_fat_lines off #For line width = Default (1.0)```
* Fixed blurry fat line issue to make both thin and fat line sharp.
 
## Binary distribution
Binary files for *Windows* are available in [**Releases**](https://github.com/tbzcode/gtkwave/releases) section.
