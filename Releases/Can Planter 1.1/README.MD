

# Author
Sean Kim
@seanwooj
[Wooj Design](http://wooj.design)

# Version
1.1.1

#### Description
This is a small project I've been tinkering at on and off for a few months. Now that many are quarantined at home, it seems like a good time to help people get into indoor gardening.

This design utilizes a 28 ounce tomato can and Kratky hydroponics to allow for unpowered (non-circulating) hydroponics in the home.

Future versions should allow for configuration of the files to fit a variety of different containers.

This version of the can planter has some significant improvements over the first version.
It is:
* Easier to print
* Easier to germinate with seeds
* Compatible with various brands of coco coir plugs

#### 1. Tools and Materials
Below is a list of tools, parts and materials you should need to complete this project.

##### Materials:
* 3d Printing Filament (I prefer using PLA)
* Tomato can
* Hydroponic nutrient solution

##### Tools:
* 3d Printer

#### 2. Printing
##### 2.1 Print Settings
If you use PrusaSlicer (which I recommend, even if you don't have a Prusa printer), you can just open the `Can Planter 1.1 - Prusaslicer` file in the Gcode folder. This is the easiest way to get all of the settings that I use. **It'll look a little weird because there will be some random cylinders placed in the file, but those are just slicer modifiers, and won't be printed.**

The included STLs may be scaled incorrectly. They were designed in imperial units (lol, sorry), so you may need to scale them up `2540%` in your slicer.

* Material: PLA
* Print Temp: 200-215 C
* Bed Temp: 60 C
* Bed Prep: Wipe clean, apply a thick layer of Elmer’s glue stick. Kapton tape is recommended since this frame will really stick to the bed tight if you use the STL with the raft.
* Layer Height: .3mm (this assumes using a standard .4mm nozzle)
* Infill: 10%, Rectilinear Fill
* Orientation: The net cup should be printed with the rim facing upwards. The lid should be printed with the cup holder facing upwards.
* Supports: You should print the net cup with no supports. The lid should be printed with auto generated supports, but with no bridging supports (if speed is important to you)

#### 2. Hydroponics
[Kratky's paper on non-circulating hydroponics](https://www.ctahr.hawaii.edu/hawaii/downloads/Three_Non-circulating_Hydroponic_Methods_for_Growing_lettuce.pdf)
[A brief introduction to Kratky hydroponics](https://northernhomestead.com/the-kratky-hydroponics-way/)

It doesn't really matter what kind of nutrient solution you are using, as long as you're following the recommended guidelines for the product that you're using. I personally make use of [General Hydroponics Flora Series](https://generalhydroponics.com/floraseries), which I find to work really well.

This system uses a slightly modified Kratky; in standard Kratky, you don't refill your nutrients. You use a big container and by the time the nutrients run out, you've already harvested your crop. Because the cans are too small to keep a plant hydrated to maturity, you will periodically need to top up your nutrients. I tend to not be that precise with how I'm adding nutrients (I don't keep track of PH or PPM, for example) and it tends to work.

The important thing is that you don't overfill your can such that the top of the roots are covered with water. The key to Kratky is that the roots differentiate, some becoming more able to absorb gas, and some suited to water and nutrients. If you overfill your can, you'll "drown" the gas-absorbing roots and kill the plant.

#### 3. FAQ
This will be filled out as people ask questions :)


## Changelog
- 1.1.1 - Removed some extraneous models from the prusaslicer base file.
- 1.1 - Updated to include a stl model with the open bottom, as well as including the prusaslicer base file
