# Acrylic case
 * tools
   * Syringes for applying acrylic cement
     https://www.amazon.com/gp/product/B01NBSWJ5R/ref=oh_aui_detailpage_o06_s00?ie=UTF8&psc=1
   * scorer
     https://www.amazon.com/gp/product/B003UHUZ5U/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1
   * hole saw
     https://www.amazon.com/gp/product/B0009WY67W/ref=oh_aui_detailpage_o09_s00?ie=UTF8&psc=1
   * mandrel
     https://www.amazon.com/gp/product/B007QV3DLE/ref=oh_aui_detailpage_o00_s01?ie=UTF8&psc=1
   * step drill bit
     https://www.amazon.com/gp/product/B0177PN6SI/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1
 * materials
   * acrylic cement
     https://www.amazon.com/gp/product/B005ZH31W2/ref=oh_aui_detailpage_o04_s02?ie=UTF8&psc=1
   * acrylic sheet (12x12x1/8)
     https://www.mcmaster.com/#8505K741
   * acrylic sheet (12x24x1/8 inch)
     https://www.mcmaster.com/#8505K742

## Idea:

The left-hand side panel is attached to the structure permanently with
some screws; use the step drill bits to add holes for access to the
USB port and to mount the power switch.

A bottom plate might be wise to protect the electronics while moving
around.

The rest of the structure is kind-of-optional. I basically made a 20x30x~5cm
enclosure, using the cement to glue the edges. The hole saw is just big
enough for the lidar unit to fit through the case.


# Structure
  * tools
    * hacksaw
      https://www.amazon.com/gp/product/B009CMV9D4/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1
    * hex nut driver
      https://www.amazon.com/gp/product/B00G2DNXV2/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1
  * materials
    * hex nuts (suggest getting 200)
      https://www.amazon.com/gp/product/B000NBIH92/ref=od_aui_detailpages00?ie=UTF8&psc=1 
    * t-slot nuts (suggest getting 50)
      https://www.amazon.com/gp/product/B016OJNLJ2/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * round headed 6mm M3 bolts
      https://www.amazon.com/gp/product/B06XJ299S1/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * square headed 6mm M3 bolts
      https://www.amazon.com/gp/product/B00G2DNW3G/ref=oh_aui_search_detailpage?ie=UTF8&psc=1

    * MakerBeam corner cubes
      https://www.amazon.com/gp/product/B00OWGOMG6/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * 10cm MakerBeam
      https://www.amazon.com/gp/product/B00G2DNSSK/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * 15cm MakerBeam
      https://www.amazon.com/gp/product/B00G2DNT4I/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1
    * 20cm MakerBeam
      https://www.amazon.com/gp/product/B01LYO8FAE/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * 30cm Makerbeam
      https://www.amazon.com/gp/product/B00G2DNU4M/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * MakerBeam T brackets
      https://www.amazon.com/gp/product/B00OI6ZBQA/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * MakerBeam 90 degree brackets
      https://www.amazon.com/gp/product/B00G2DNV0U/ref=oh_aui_search_detailpage?ie=UTF8&psc=1
    * motor bracket (get 4)
      https://www.amazon.com/gp/product/B00TK0X03U/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1
    * motor: eccentric shaft; ~300PM (get 4)
      https://www.amazon.com/gp/product/B01KTXS79S/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1
    * mecanum wheels (one set)
      https://www.amazon.com/gp/product/B01EDL760S/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1
    * shaft hub (one set)
      https://www.amazon.com/gp/product/B06XPH9B3P/ref=oh_aui_detailpage_o06_s00?ie=UTF8&psc=1


## Idea:

A lot of the design was informed by the mecanum wheels, aka The Single Most Expensive
Item on this parts list. You may be able to get cheaper ones on e.g. ebay.

The Mecanum wheels come in pairs: 2 left-hand side and 2 right-hand side, based
on how the casters are oriented. The correct way to mount them is so that, when
viewed from above, the casters for each wheel point towards the center of gravity
of the robot (forming an X).

The Mecanum wheels let you move sideways by turning the wheels in opposing directions.
For that to work, the wheels need to be in a *square* configuration.

In my case, that meant:

Use two 30cm makerbeams for the length; use two 20xm for the width. Use the 90 degree
brackets to make a 22cm (20 + 1 + 1) wide by 30cm long rectangle. Attach the motor
mount directly to the bottom of this at the very corners (using 3 out of the 4 mounting
holes on the motor brackets). Attach the motors to the brackets with the shaft near
the bottom (using the eccentric gear box to give you a bit more ground clearance).

Attach the wheel hubs to the mecanum wheels; attach the hubs directly to the shaft.
The shaft will have some slop, so leave some space between the hub and the motor so
that they don't touch when you put weight on the wheels.

That gives you a rectangle with wheels; I added some vertical space below that basic
frame to hold the electronics and the battery.

The vertical space consists of a separate 17cm (== 15 + 1 + 1) long by 22cm
(== 20 + 1 + 1) wide makerbeam rectangle that hangs about 2cm below the main frame.
This 'height' puts the bottom of that rectangle at about the same ground clearance
as the motors and the axles. It is lined up with the forward two motor brackets.

To get the four 2cm pieces, I sawed the ends off two 10cm makerbeams. The corner
cubes make it really easy to attach the ends of three beams in one place.
Hacksawing through aluminium is not too bad, though you may want to have some
120-grit sandpaper around to smooth the edges.


# Electronics
  * tools
    * LiPo battery charger
      https://www.amazon.com/gp/product/B01FHDIINU/ref=oh_aui_detailpage_o08_s00?ie=UTF8&psc=1
    * terminal crimping tool
      https://www.amazon.com/gp/product/B019ARWWFY/ref=oh_aui_detailpage_o04_s00?ie=UTF8&psc=1
  * Materials
     * Arduino Mega
       https://www.amazon.com/gp/product/B01H4ZLZLQ/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1
     * BlueTooth LE breakout
       https://www.amazon.com/gp/product/B01HN72K14/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1
     * I2C multiplexer
       https://www.adafruit.com/product/2717
     * Arduino Motor Shield (either)
       https://www.amazon.com/gp/product/B01K3YPSAE/ref=oh_aui_detailpage_o02_s02?ie=UTF8&psc=1
       https://www.amazon.com/gp/product/B00813HBBO/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1
     * Neato XV SeriesLIDAR unit (should be ~$90)
       search on ebay; e.g
       https://www.ebay.com/itm/Neato-XV-Series-LIDAR-Sensor-Module-Xv-11-Xv-12-Xv-15-Xv-21-Xv-signature-/302492654897?hash=item466df79d31
     * VL6180X distance sensor + level shifting
       search ebay, e.g.
       https://www.ebay.com/itm/GY6180-VL6180X-Time-of-Flight-Distance-Sensor-Carrier-With-Voltage-Regulator-GL/112493465402?epid=1048615103&hash=item1a31220f3a:g:RkkAAOSwMedZdXTx
     * N-channel Mosfet 
     * NeoPixel ring
       https://www.amazon.com/gp/product/B01F7YRBEQ/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1
     * LiPo Battery
       https://www.amazon.com/gp/product/B0072AEY5I/ref=oh_aui_detailpage_o09_s00?ie=UTF8&psc=1
     * Male XT60 connector (I got this at a local RC/hobby shop)
     * 22 gauge solid core wire
       https://www.amazon.com/gp/product/B00B4ZRPEY/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1
     * 2.54mm pitch JST connector materials
       https://www.amazon.com/gp/product/B01M5FIDT9/ref=oh_aui_detailpage_o05_s00?ie=UTF8&psc=1
     * ribbon cable
       https://www.amazon.com/gp/product/B007R9SQQM/ref=oh_aui_detailpage_o06_s00?ie=UTF8&psc=1
     * prototype board
       https://www.amazon.com/gp/product/B01M7R5YIB/ref=oh_aui_detailpage_o05_s00?ie=UTF8&psc=1
     * switching voltage regulator
       https://www.adafruit.com/product/1385
     * N-channel MOSFET (suggest getting a few; they can break)
       https://www.adafruit.com/product/355
     * all the capacitors [you may not need them]
       https://www.amazon.com/gp/product/B007SVHFXO/ref=oh_aui_detailpage_o08_s01?ie=UTF8&psc=1
     * all the resistors [you definitely need them]
       https://www.amazon.com/Joe-Knows-Electronics-Value-Resistor/dp/B003UC4FSS/ref=sr_1_1?s=industrial&ie=UTF8&qid=1512255299&sr=1-1&keywords=joe+knows
     * diode
       https://www.adafruit.com/product/755
     * power switch
       https://www.adafruit.com/product/917

## Idea:

### Power + motors

The old-school v1 motor shield uses a bunch of pins on the arduino instead of something like I2C; it
can drive all four motors in both directions at different speeds. I haven't run out of pins yet,
and we'll be using the I2C bus heavily for sensor data. I might try the I2C version at a later date
if I start running low on pins.

The motor shield takes power directly from the LIPO battery (with the power switch in between
to interrupt the positive terminal). *REMOVE* the jumper that lets you power the Arduino itself
from the motor board. Connect the buck convertor input to the battery directly, and connect
its output to the Vin pins on the Arduino.

There's a couple of reasons for this:

1) The regulator in the buck converter lets you draw more current through the Arduino +
   peripherals than the built-in regulator in the arduino. Note that the Arduino will be
   powering the LIDAR laser, LIDAR motor, the LEDS, and the bluetooh breakout, and the
   LiPo battery maxes out at just under 15V when fully charged. The built-in regulator
   heats up propotional to the amount of current and the voltage difference, so it'll
   work great right until it catches fire.

2) The switching regulator ought to be much more efficient than the linear regulator
   in the Arduino.

```
                            (+)[converter in][converter out](+)
                             |                               |
    [battery](+)--[switch]--(+)[motor shield]               (5V)[Arduino]
             (-)------------(-)**remove jumper**            (Gnd)                  
                             |                               |    
                            (-)[converter in][converter out](-)
```

### Bluetooth

The Bluetooth breakout board comes with a decent set of pinout instructions at
AdaFruit. I soldered the breakout onto a prototype board and connected the
prototype board to the Arduino using a 6-wide ribbon cable (with a JST connector
for the prototype board to make stuff easier to disconnect if needed).

### LEDs

I superglued a JST connector to a piece of acrylic, which I then mounted to some
of the structure. Super useful for helping debug things. Note that the NeoPixel
rings use a pretty timing-sensitive protocol (no separate clock wire like I2C), so
changing the pixels often will mess with your ability to receive LIDAR data. It might
not be unreasonable to find some different 'individually addressable' set of LEDs
that doesn't rely on a 2-wire protocol.

Finally, note that this is just 12 LEDs, which is why we can power them directly off
of the Arduino's power rail. Attaching more LEDs might take a bit more though, since
it probably isn't a good idea to draw much more current through the traces on the
Arduino.


### Lidar

The LIDAR unit takes a bit of work. It communicates with the Arduino over a serial
connection at 115k baud. It pushes a lot of data, and the Arduino has exactly one (1)
byte of buffer, so you lose packets of LIDAR data every time you block interrupts for
longer than ~1100 CPU clock cycles at 16 Mhz. In addition to handling the sensor data
(360 16-bit ints per rotation), you'll need to actively control the speed at which
the motor spins that thing around.

I used the diagram here to wire up the LIDAR:
https://github.com/bombilee/NXV11/blob/master/ArduinoMegaAdapter/ArduinoMega%20XV-11%20LDS%20Adapter%20Schematic.png

I put this together on one of the pieces of PCB prototype boards; one of the resistors,
one N-channel MOSFET, and one diode are there to let you safely drive the motor off of
a single PWM pin. I connected the data (serial port) stuff to the serial 3 pins on the
Arduino. This is a good reason to use the MEGA: it supports up to 3 serial interfaces,
so you can still debug via USB while receiving data from the LIDAR unit.

The JST connector on the LIDAR is smaller than the 2.54mm pitch ones we're using
elsewhere, so you may need to bend some pins to be at the right distance.

Structure: the LIDAR is oddly shaped, so the 4 screw holes don't line up to a rectangle.
I worked around this by rotating the unit (the motor is a bit off to the side) and
mounting it with 3 screws rather than 4. I used 3 more hacksawed pieces of makerbeam
to get the right offset relative to the bottom of the robot.

### VL6180X sensors

I got 8 of these, to match the number I could use with one I2C multiplexer. The VL6180
is kind of annoying: even though it supports I2C, there is no way to permanently change
the I2C address of each chip. Instead, you would need to power on each chip individually,
then change its address, then power on the next one, etc. More typical I2C hardware
lets you set the address using e.g. jumpers.

We're using the I2C multiplexer to solve this. The downside is that it requires 4 leads
(power, ground, I2C data, I2C clock) from the multiplexer to each sensor, so it's a bit
messy. I used lots of 4-wide ribbon cables and JST connectors for this.

we mounted these sensors as low as possible on the structure, with 3 in front, 2 on each
side, and one in the back.
