# Krampus Minibadge Instructions

<img src="/images/multicolor_LEDs.jpg" width="400" />
<img src="/images/red_yellow_LEDs.jpg" width="400" />
<img src="/images/pcb_front.jpg" width="400" />
<img src="/images/pcb_back.jpg" width="400" />


## Components

- Main minibadge pcb
- Krampus add-on pcb
- 0.1uF Capacitor (0603)
- 22uF Capacitor (0603)
- 6- smd white LEDs (0603) - these are unmarked
- A mix of at least 10 (should have extras) red, yellow, green LEDs (0402) - these are marked with their associated color
- 3- 5.1 ohm resistors (0402) - these are marked green and you should have an extra
- 5.1k ohm resistor (0402) - marked red
- 5.1k ohm resistor (0603)
- UV LED (0805) - marked purple
- 5.1 ohm resistor (0603)
- TLC555 timer
- CD4017 decade counter
- 5- 2-pin male 2.54 headers
- 10k ohm potentiometer

## Assembly Instructions

Double check components against size, indicated color, and printed info on component (where available). I included extra of the 0402 components so don't use count to determine where they go. 

Start on back of main board:

- Solder the two ICs (TLC555 and CD4017) according to the orientation below. Note that there is a white line that marks the location of pin 1 for each of them.  

<img src="/images/ic_orientation.jpg" width="400" />

- Solder the (0603) 0.1 uF capacitor to C1 (marked orange, orientation doesn't matter)
- Solder the (0603) 22 uF capacitor to C2 (marked blue, orientation doesn't matter)
- Solder the (0402) 5.1k ohm resistor to R4 (marked red)
- Solder (0402) 5.1 ohm resistors to R1, R2 and R3 (marked green)
- Solder (0402) 68 ohm resistor to R5 (marked black)
- Solder (0603) white LEDs to D1, D2, D3, D4, D5, D6. These are the only LEDs that don't have a marked color. I recommend side mounting all of these LEDs (except D5) so the light is facing up. I recommend reverse mounting D5 so that the light is shining toward the board.

Move to the front: 

- The tree has red, green and yellow LEDs (0402, marked with associated color) that can be placed where you would like. I recommend starting with one color and place 3-4 of them about equal distance from each other around the tree. Then do the next color and the last. The cathodes of the LEDs are not clearly marked. They are oriented in the same direction so that the cathode is on the bottom side (closest to the bottom of the board). See image below - the red dot at the lower side of each LED is the cathode.

<img src="/images/front_led_orientation.png" width="400" />




