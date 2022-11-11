# PVS-69 Gen3 ECHO

## Changes from DELTA to ECHO

The PVS-69 ECHO has a few changes in functionality, size, and printabilty.

ECHO has improved water resistance with the addition of a retaining collar for the displays.

The bridge has been slimmed down and optimized for printing, now called Gen4 Bridge. The Gen4 Bridge has two variations, front-loading and back-loading. The back-loading version should help with wiring the internals of the bridge.

The internal battery connection for the Gen3 Bridge has been redesigned for a more reliable connection. O-ring lands in the tubes were removed in anticipation for a quick detach PCB contact system (still in progress). The tubes are optimized to be printed vertically with threads up. No supports should be needed!

## Bill of Materials

### This design requires the following printed components: 

1x [Dovetail](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Dovetail.stl)

1x Bridge Body. In this design, there are 3 Bridge options:
1. [Gen3 Bridge](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Gen3%20bridge%20body.stl) is the same bridge as older versions, with an internal battery compartment.
2. [Gen4 Bridge Back-Load](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Gen4%20bridge%20back-load%20body.stl) is a newer, sleeker bridge that does *not* have an internal battery compartment. The back-loading version allows the user to more easily build the internals of the bridge and then load it into the back (away from your face).
3. [Gen4 Bridge Front-Load](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Gen4%20bridge%20front-load%20body.stl) is the same as above, except it is accessed from the front (towards your face).

1x Bridge Backplate, which will depend on the Bridge body you choose

2x [Sensor Caps](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/RunCam%20sensor%20cap.stl)

2x TIPs (Tube Interface Pieces) - please note there are [+0°](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/%2B0%20TIP.stl) and [+2°](https://github.com/knack-69/PVS-69/tree/main/PVS-69%20versions/Gen3%20ECHO/STL) versions. 
    The +2° version gives a wider FOV

2x [Ambi Tubes](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Ambi%20tube%20-%20ECHO%20.stl)

1x [Battery Cap](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Battery%20cap.stl) (Only needed if using Gen3 Bridge)

2x [Collars](https://github.com/knack-69/PVS-69/blob/main/PVS-69%20versions/Gen3%20ECHO/STL/Collar.stl)


### This design requires the following physical components: (*This list is still under development*)

---

#### Gen3 Bridge (Internal and External Battery)

1x [3-Position Rotary Switch](https://amzn.to/3TspGUS).

11x [M5x8 Bolts](https://amzn.to/3EyraZz)

11x [M5x5.8 Heat-set Inserts](https://amzn.to/3E0fzRt)

2x [RunCam Night Eagle 3](https://amzn.to/3Epdyhh)

2x V760A-5 or V760A-3 displays. These can be found on Ebay or AliExpress, expect a month for shipping.

1x [300x8mm OD of Brass Tubing](https://amzn.to/3E3g5Oq) (you will only use 100mm to make 2x 45-46mm lengths)

1x [5.5x2.1mm DC Female Jack](https://amzn.to/3KLofNA)

1x [AA Spring Terminal](https://amzn.to/3EysOdH)

1x [Buck Converter](https://amzn.to/3KSzHHf) (if not using a [5V USB Power Bank](https://www.amazon.com/gp/product/B07QXV6N1B/), see [this writeup]() for more information)

2x [10x2mm Nitrile O-ring](https://amzn.to/37mEOko)

2x [13x3mm Nitrile O-ring](https://amzn.to/3KRAmsA)

5x [22x2mm Nitrile O-ring](https://amzn.to/3rrIp7N) (you can buy a [multipack](https://www.amazon.com/gp/product/B092MDGM110) that has all three sizes, thickness is not terribly important)

1X [2x8mm rare earth magnet](https://amzn.to/3Ostkga)

Approximately 24" of [20-24 AWG wire](https://amzn.to/3EoQ5yn)

3” section of 16AWG single strand wire (for internal battery positive connection)

---

#### Gen4 Bridge (External Battery Only)  

1x [Buck Converter](https://amzn.to/3KSzHHf) (if not using a 5V USB Power Bank, like [this one](https://www.amazon.com/gp/product/B07QXV6N1B/), see [this writeup]() for more information)

11x [M5x8 Bolts](https://amzn.to/3EyraZz)

11x [M5x5.8 Threaded Inserts](https://amzn.to/3E0fzRt)

1x [Push Button](https://amzn.to/3Txgdvg)

4x [Brass Washers](https://amzn.to/3WSWOI2)

2x [12mm Nitrile O-ring](https://amzn.to/3fV4qcD)

3X [22mm Nitrile O-ring](https://amzn.to/3V5NT4D)

2x [35mm Nitrile O-ring](https://amzn.to/3fVgjz8)

2x [45-46mm section of brass tubing](https://amzn.to/3E3g5Oq)

1x US nickel or other 19mm coin

Approximately 24" of [20-24 AWG wire](https://amzn.to/3EoQ5yn)
