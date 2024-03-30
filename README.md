# Front_Panel

**Here an example of a design on Inkscape**

<img src='Pictures/281 Vectorised.png' width='200px'/>

**Here the result after laserCutting and coloring fonts with white paint**

<img src='Pictures/Version Yo.jpg' width='200px'/>


## Design


**FREECAD**

Freecad is a free 2D and 3D drawing software. : https://www.freecad.org/
It allowed me to draw the module's outer contour and fixing holes.

Then I insert it into Inkscape to add images and texts.
But, why don't I use Inkscape at the beginning for the module's outer contour and fixing holes ?

Quite simply because Freecad lets me set dimensional constraints.
The outside size can be defined very precisely, and the fixing holes can be placed at an exact distance from the edge.
And, even if I change the outside dimension, the position and size of the fixing holes will remain the same.

I made files with the current front panel sizes

You will find them in the 2D files folder.


**INKSCAPE**

Inkscape is a free 2D vectoriel drawing software. https://inkscape.org/
In Inkscape you can create a 2D vector design with easy and pretty image and text insertion with also some tool to align holes of defined diameters for knob, switch, jacks, leds ... 
You can play with fonts, pictures and much more... :)

Here one of my design, you'll find the .svg on 2D files folder

<img src='Pictures/4 VCA V5.png' width='200px'/>

There is also my generic page with all the necessary components (Jacks, Pots, switchs...)

You'll find them in .svg format the 2D files folder.



**KICAD**

Kicad is a free creating pcb software. https://www.kicad.org/
It is common to obtain front panels using this software.

I insert the file in Kicad, and define each drawing or writing on a layer of the PCB.

## FABRICATION

To obtain the next front panels you'll need a lasercutter. Like 3d printer you can find it in a fablab.


**Lasercut PMMA**

Pmma or plexiglas

<img src='Pictures/Version Yo.jpg' width='200px'/>


**Lasercut WOOD**

poplar plywood 3mm

<img src='Pictures/CP 3mm.jpg' width='200px'/>


**Lasergraving Dibond**

3mm dibond = Dibond® is an aluminum composite material (ACM). It is comprised of two pre-painted sheets of . 012″ (. 30mm) aluminum with a solid polyethylene core.

Most easy-to-find machines cannot engrave in aluminum.
But aluminum is painted, so engraving works in place of cutting.
However, you'll need to drill the holes with a drill press and cut the edge precisely.
But it's functional, and inexpensive, as sports clubs use this material for their advertising.
As their sponsors change, they no longer use the old panels...
On one side there's the advertising, on the other it's blank, ready to engrave, sometimes even with the protective layer still on :)

<img src='Pictures/Dibond.jpg' width='200px'/>


**Lasergraving Aluminium**

Most easy-to-find machines cannot engrave in aluminum.
But aluminum can be painted, so engraving works in place of cutting.
But, you do need to protect the paint, however, as it will peel off. One solution is to apply a layer of transparent plastic adhesive.

However, you'll need to drill the holes with a drill press and cut the edge precisely.

<img src='Pictures/Aluminium.jpg' width='200px'/>


**Etch PCB**

To obtain this quality of fabrication - Not the design :) - you'll need to send GERBER files to a PCB supplyer. 

<img src='Pictures/Pcb.jpg' width='200px'/>



**3d print**

It's also possible to 3d print the front panel. 
I use 3d panel only for blank panel

<img src='Pictures/3D Print.png' width='200px'/>

This website allows you to download and print eurorack parts. 

https://www.thingiverse.com/search?q=eurorack&page=1&type=things&sort=relevant

https://www.thingiverse.com/thing:1850240

https://img.thingiverse.com/cdn-cgi/image/fit=contain,quality=95/https://cdn.thingiverse.com/renders/f8/6b/c8/af/30/ea0b798dd1fd3b85183d70121756dcbc_display_large.jpg

## More resources on creating PCB front panel

ModWiggler forum :

* https://modwiggler.com/forum/viewtopic.php?t=282087&sid=c586f268479aaaf0befdb3511445877c#top

* https://modwiggler.com/forum/viewtopic.php?t=235049

* https://modwiggler.com/forum/viewtopic.php?t=180347&start=400

