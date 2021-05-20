# speedometer
Building a bike speedometer using an rpi

## Goal
Want to build a bike mounted speedometer using an rpi (maybe 0 or a pico?).

### Computing mph
From RPM, and circumference of the bike, we can compute the distance travelled per minute, and from there compute mph.

### Getting RPM
Place magnets on the rim/spokes of the wheel, then use a hall effect sensor to measure when the magnets pass the top of the frame (ty James for telling me about the Hall Effect)
### Displaying MPH
Wire the rpi to a lcd display, which just displays the number.


## Parts List
Parts I already have:
- Breadboard
- Cables (M/M and F/M)
- Power Bank
Parts I need to get:
- Arduino (Nano seems to be the best choice)
- Hall efect sensor
- Magnets
- LC display
- Resistor (not sure if needed)
