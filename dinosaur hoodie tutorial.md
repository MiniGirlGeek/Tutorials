#Creating a Dinosaur Hoodie

#What you'll need
1. A hoodie
2. An Adafruit Gemma
3. Access to a 3D printer
4. White NinjaFlex
5. A needle
6. **_optional_** A needle threader (useful if you've not done much sewing before)
7. Some conductive thread
  * Silver based conductive thread is easier to work with (it's less springy) but will eventually oxidise.
  * Stainless steel conductive thread is harder to work with but will last for longer.
7. Normal thread
7. Crocodile clips _(for testing)_
7. 8 x Adafruit RGB NeoPixels
8. A battery
9. A MicroUSB B Cable

#3D Printing
You can either attempt to draw your own spine, or you can use [our design](https://github.com/MiniGirlGeek/Tutorials/blob/master/resources/dinosaur_spike.stl). Once you've got a .stl file ready you can start printing.

[spine photo]

Each spine can take between 30mins - 1hr 30mins to print depending on your printer and settings.

Once you've started you can start the sewing, and start another spine printing as and when possible.

#Sewing Practice
If you haven't done much sewing before, it would be useful to have some practice. Otherwize skip to the [next section](#the-circuit).

This is the eye of a needle:

![the eye of a needle](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-01.png)


This is where you'll insert your thread.

1. Measure out a length of thread that is double the distance between the tip of your hand and your elbow.

1. If you're using a needle threader, you'll need to insert the threader through the eye of the needle first.
  
  ![a graphic of a needle threader through the eye of a needle](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-02.png)

2. Next push your thread through the eye of the needle threader.
  
  ![a graphic of a thread being threaded through needle threader](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-03.png)

3. Now pull the needle threader out from the needles eye, and you should have a successfully threaded needle.
  
  ![a graphic of a thread being threaded through needle threader](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-04.png)

4. Pull the two ends of the thread together.
  
  ![a graphic of a thread being threaded through needle threader](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-05.png)

5. Now tie a knot at the end of the threads, using both of the threads. Try and get it as close to the end of the threads as you can by pulling the knot towards the end as you tighten it.
  
  ![a graphic of a two threads being knotted together](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-06.png)

6. Insert your needle on the underneath of your material, this ensures that the knot cannot be seen from the front, and pull your thread through until the knot is tight next to the material.

  ![a graphic of a needle being pulled though a piece of material](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-07.png)

7. To create a running stitch go back down into the material ≈ 5mm further along, and then bring the needle back up a further ≈ 5mm along. Continue this until you have the length of stiches that you need. Try to keep your thread as taught as possible to create tight stiches which are less likely to come undone.
  
  ![a graphic of some stiches in a material](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-08.png)

8. Now fill in the gaps using the same holes you came in and out of before.
  
  ![a graphic of some stiches in a material](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-09.png)

9. Return your needle to the reverse and tie another knot in your thread. Keeping the needle threaded whilst you do this can make it easier, as you can use the needle to make the knot. If there's some thread left you can either cut it off or, to make it extra secure, you can weave it into the stitches on the bottom trapping the loose threads.

Practise this as many times as you like until you feel you've got the hang of it.


#The Circuit
We're going to be  using the conductive thread to create a circuit that connects the Gemma each of the neopixels. This is the ideal orientation they should be in relative to each other.

![an adafruit gemma and neopixel in the correct orientation](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-10.png)

This is what the full circuit will look like, each of the neopixels are in the same position as the one above.

![the circuit layout](https://github.com/MiniGirlGeek/Tutorials/blob/master/dino_images/needle_instructions-11.png)

But first we need to check that the Gemma and the NeoPixels are working.
