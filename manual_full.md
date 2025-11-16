# Game Manual -- Extracted Text (Batch 1)

## /CONTROLLERS/JOYSTICKS -- Vertical Axis Joystick

The vertical axis joystick outputs from 0--65,536 based upon its
physical position from its centre point. The output is on either the Y+
or Y- depending which side of the centre point the joystick is held
currently.

## /ELEMENT SETTINGS -- Page 1/4

-   Silicon (Si): 14
-   Iron (Fe): 26
-   Cobalt (Co): 27
-   Nickel (Ni): 28
-   Platinum (Pt): 78

## /ELEMENT SETTINGS -- Page 2/4

-   Zinc (Zn): 30
-   Calcium (Ca): 20
-   Silver (Ag): 47
-   Rhodium (Rh): 45
-   Gold (Au): 79

## /ELEMENT SETTINGS -- Page 3/4

-   Thorium (Th): 90
-   Aluminum (Al): 13
-   Copper (Cu): 29
-   Palladium (Pd): 46
-   Osmium (Os): 76

## /ELEMENT SETTINGS -- Page 4/4

-   Iridium (Ir): 77

## /CONTROLLERS/JOYSTICKS -- 2-Axis Joystick

The 2-axis joystick outputs from 0--65,536 based upon its current
physical position from its centre point.\
It will output the X+, X-, Y+, and Y- values separately.

## /CONTROLLERS/JOYSTICKS -- Reality Joystick Controller

The Reality Joystick Controller will allow you to use the XY axis of the
physical joystick/trackpad on your VR controller. Simply grab the orange
sphere with the controller you wish to use, then use the
joystick/trackpad on the same controller.

## /CONTROLLERS/JOYSTICKS -- 2-Axis Restricted Joystick

The 2-axis restricted joystick outputs from 0--65,536 based upon its
physical position from its centre point along only a single axis at a
time. The outputs are X+, X-, Y+, and Y-.

## /CONTROLLERS/SWITCHES -- 8-Bit Switch

The 8-bit switch outputs a binary number from 0--255 based on the switch
positions.

## /CONTROLLERS/JOYSTICKS -- Horizontal Axis Joystick

The horizontal axis joystick outputs from 0--65,536 based upon its
physical position from its centre point. The output is on either the Y+
or Y- depending which side of the centre point the joystick is held
currently.

# Game Manual -- Extracted Text (Batch 2)

## /CONTROLLERS/BUTTONS -- 3 Button Bank

The 3 button bank outputs a TRUE signal to the connected device when the
associated button is held down, otherwise it outputs FALSE.

## /CONTROLLERS/SLIDERS -- Slider

The slider outputs from 0--65,536 based upon its current physical
position along its length with 0 being its starting position.

## /CONTROLLERS/DIALS -- 100 Dial

The 100 dial will output the selected value as a percentage of the
16‑bit value range (0--65,535).

## /CONTROLLERS/SWITCHES -- 4‑Toggle Switch

The 4‑toggle switch outputs a boolean (TRUE/FALSE) value based upon the
individual switch position to the associated data output.

## /CONTROLLERS/SWITCHES -- 1‑Bit Switch

The 1‑bit switch outputs a 1 or a 0.

## /CONTROLLERS/SWITCHES -- Single Toggle

The single toggle switch outputs a boolean (TRUE/FALSE) value based upon
the switch ON/OFF position.

## /CONTROLLERS/SWITCHES -- 4‑Bit Switch

The 4‑bit switch outputs a binary number from 0--15 based on the switch
positions, with 1111 being its maximum value.

## /POWER DISTRIBUTION/ENERGY CELLS -- Small Energy Cell

The small energy cell stores power and discharges it via its output
power port.\
The data port outputs the charge amount as a percent.

## /CONTROLLERS/THROTTLES -- Throttle

The throttle outputs a value from 0--65,535 based upon its position
relative to its mid‑point.\
Forward from the mid‑point will output to the data output on the
X‑axis.\
Backward from the mid‑point will output to the data output on the
X‑axis.

# Game Manual -- Extracted Text (Batch 3)

## /DATA DISTRIBUTION/DATA SPLITTERS -- Binary Splitter

The binary splitter splits the signal from a small data cable to 8
boolean (TRUE/FALSE) values.\
The shift toggle will "split" the left 8 binary values instead of the
right 8 binary values of the 16‑bit binary value.

## /CONTROLLERS/BUTTONS -- Single Button

The single button outputs a TRUE signal when the button is held down,
otherwise it outputs FALSE.

## /DATA DISTRIBUTION/DATA SPLITTERS -- Vector Multiplex Splitter

The vector multiplex splitter splits the 32‑channel large data cable
input into 4 separate vector cable outputs.

## /DATA DISTRIBUTION/DATA SPLITTERS -- Multiplex Splitter

The multiplex splitter duplicates the signal from the input data port to
all the data output ports.

## /DATA DISTRIBUTION/CABLES -- Large Data Cable

The large data cable can carry up to 32 16‑bit values.\
This cable can be used to transport data between rooms.

## /DATA DISTRIBUTION/DATA SPLITTERS -- Single Channel Splitter

The single channel splitter takes a small data cable in and duplicates
its value to all the other outputs.

## /DATA DISTRIBUTION/CABLES -- Small Data Cable

The small data cable can carry a single 16‑bit value that can be updated
up to 50 times per second.\
These cables can be used to pass data between modules in a room.

## /DATA DISTRIBUTION/DATA SPLITTERS -- Flight Splitter

The flight splitter splits the signal from a large data cable to
multiple small cables (from channels 0--13).

## /DATA DISTRIBUTION/DATA SPLITTERS -- Channel Splitter

The channel splitter splits the signal from a large data cable to
multiple small cables.\
Channels 0--14 are reserved for flight controls but these can be
overridden.\
The shift toggle will "split" the last 16 channels instead of the first
16 channels.

# Game Manual -- Extracted Text (Batch 4)

## /DATA PROCESSING/MATH/SCOPED TRIGGERED

The triggered module takes a 16-bit input evaluated against *Start* and
*Stop* 16‑bit values.

If the *Start* signal is less than the *Stop* signal, the output will
only become TRUE if the *Input* signal is smaller than the *Start*
signal and then becomes larger than the *Start* signal.\
If the *Input* signal then becomes greater than the *Stop* signal, the
output becomes FALSE.

If the *Start* signal is greater than the *Stop* signal, the output will
only become TRUE if the *Input* signal becomes less than the *Start*
signal and then becomes greater than the *Start* signal.\
If the *Input* signal then becomes less than the *Stop* signal, the
output becomes FALSE.

## /DATA PROCESSING/MEMORY -- Raw Memory Bay

The raw memory bay can store up to 1024 16‑bit values of memory that can
be indexed from 0 to 1023.\
Select the index you want to write to with *W-Index* and the index you
want to read from with *O-Index*.

The *Input* will only be written to the drive in the selected *W-Index*
when the *Write* signal is TRUE.

## /POWER DISTRIBUTION/ENERGY CELLS -- Small Energy Cell

The small energy cell stores power and discharges it via its output
power port.\
The data port outputs the charge amount as a percent.

## /POWER DISTRIBUTION/CABLES -- Large Power Cables

Large power cables are used to provide power between rooms.\
These cables can handle large amounts of power (50 MJ/s).

## /POWER DISTRIBUTION/CABLES -- Small Power Cables

Small power cables are used to provide power to individual modules.\
These cables can only handle small amounts of power (1 MJ/s).

## /POWER DISTRIBUTION/POWER SPLITTERS -- Large Splitter

The large splitter takes in a large power cable and distributes its
power output to any other connected large power cables.

## /POWER DISTRIBUTION/POWER SPLITTERS -- Long Splitter

The long splitter takes in a large power cable and distributes its power
output to any other connected large power cables.\
There are also two small power cable outputs that can be used.

**Note:**\
The small power cables will only replicate their maximum charge of 1
MJ/s from the large cable input.

## /POWER DISTRIBUTION/POWER SPLITTERS -- Small Switched Splitter

The small switched splitter takes in a small power cable and distributes
its power output to any other connected small power cables.\
The power can be stopped from transferring to the connected cables using
the input dataport to disable the power throughput.

## /POWER DISTRIBUTION/POWER SPLITTERS -- Small Splitter

The small splitter takes in a small power cable and distributes its
power output to any other connected small power cables.

## /POWER DISTRIBUTION/ENERGY CELLS -- Large Energy Cell

The large energy cell stores power and discharges it via its output
power port.\
The data port outputs the charge amount as a percent.

# Game Manual – Extracted Text (Batch 5)

## /POWER DISTRIBUTION/POWER SPLITTERS – Large Switched Splitter
The large switched splitter takes in a large power cable and distributes its power output to any other connected large power cables.

The power can be stopped from transferring to the connected cables using the input dataport to disable the power throughput.

## /DATA DISTRIBUTION/DATA MERGERS – Binary Merger
The binary merger allows you to merge multiple boolean (TRUE/FALSE) values into a single 16-bit value that can be used in a small cable.

The shift function allows you to “shift” the binary value 8 places to the left.

**Example:**  
With the shift function ON:  
0000000011111111 (255)  
becomes  
1111111100000000 (65,280)

## /DATA DISTRIBUTION/DATA MERGERS – Channel Merger
The channel merger will take up to 16 small data cable values and merge them for use in a single large cable.

**Note:**  
When merging and splitting the first 14 channels, 0–13 are reserved for flight controls but these can be overridden.

The shift toggle will “merge” the last 16 channels instead of the first 16 channels.

## /DATA DISTRIBUTION/DATA MERGERS – Multiplex Merger
The multiplex merger allows you to consolidate data from multiple large cables into a single large cable output.

The signal from each input will be combined using a *binary OR* operation.

**Example:**  
Cable 1 Signal: 0000000011111111  
Cable 2 Signal: 1111111100000000  
**Output:** 1111111111111111

## /DATA DISTRIBUTION/DATA SPLITTERS – Vector Multiplex Splitter
The vector multiplex splitter splits the 32‑channel large data cable input into 4 separate vector cable outputs.

## /DATA DISTRIBUTION/DATA MERGERS – Vector Merger
The vector merger combines 8 input signal cables into a vector output.

This module can be used to construct custom vectors as each of the positive and negative inputs for X, Y, Z, W are clearly labeled.

## /DATA DISTRIBUTION/DATA MERGERS – Vector Multiplex Merger
The vector multiplex merger combines 4 vector input cables into one 32‑channel large multiplex cable.

## /DATA DISTRIBUTION/DATA SPLITTERS – Vector Signal Splitter
The vector signal splitter splits the 4‑axis vector input into 8 separate signals.

Two signals are output for each X, Y, Z, W axis — one for negative values and the other for positive values.

## /DATA DISTRIBUTION/DATA CONDUITS – Large Conduit
The large conduit is for large data cables.  
It allows large data cables to be extended beyond their maximum length.

## /DATA DISTRIBUTION/DATA CONDUITS – Tall Conduit
The tall conduit allows small data cables to be extended beyond their maximum reach vertically.

# Game Manual – Extracted Text (Batch 6)

## /DATA DISTRIBUTION/DATA CONDUITS – Wide Conduit
The wide conduit allows small data cables to be extended beyond their maximum reach horizontally.

## /DATA MONITORS/DISPLAYS – Binary Light Display
The binary light display has 16 lights that are turned on or off based on the boolean (TRUE/FALSE) state of each of the separate bits of the 16-bit input signal.

## /DATA MONITORS/DISPLAYS – Status Light
The status light will activate when the input signal is TRUE.

## /DATA MONITORS/DISPLAYS – Counter Display
In the default *Count True* mode, the counter display will increase the value displayed by one for each time the value changes from FALSE to TRUE.

**Note:**  
Any binary value not 0000000000000000 will be read as TRUE.

In the *Count Any* mode, the counter display will increase the value displayed by one for each time the value changes.

## /DATA MONITORS/DISPLAYS – Linear Light Display
The linear light display takes a 16-bit binary value and displays it as a percentage of lights lit on an LED grid of 40 lights.

The value of 0 represents all lights off, and 65,535 represents all 40 lights on.
