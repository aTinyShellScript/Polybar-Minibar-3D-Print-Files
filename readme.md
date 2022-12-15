# A Tiny Mod

## Full BOM

The PolyBar and MiniBar use 99% the same BOM but the MiniBar uses 1 less microswitch and 1 less M5 heatset.

- Filament (200-250g or so)
- 1x Raspberry Pi Pico or Clone
    - WaveShare 2040-Plus recommended for USB-C (https://www.amazon.com/gp/product/B09LT4V2VS)
    - OG Pico https://www.amazon.com/dp/B08W3SH4TD
- 7x Cherry MX Keyboard Switches
    - https://www.amazon.com/dp/B07X3TH4DS
- 1x Arduino Joystick Module
    - https://www.amazon.com/gp/product/B014KQLE8Q
- 3x M5 HeatSet Insert
    - https://www.amazon.com/dp/B08T9W17CR
- 3x 6x6x4.5mm Momentary Switch
    - https://www.amazon.com/dp/B01N6GU7TA
- 3x M5x20mm Hex Head Bolts
    - https://www.amazon.com/dp/B01N6GU7TA
- 1x M5x30mm Hex Head Bolt
    - This is for my modded guitar bodies, to hold the outer frame on. It replaces one of the 20mms
- 2x Metal Ball Tile Sensors
    - https://www.amazon.com/dp/B00RGN0KY0

# Changes

## BOM Changes for PolyBar

- 1x M3 heatset
- 1x M3x8mm bolt

## File Changes

### Neck

#### Changes
- M5 heatset holes tightened up. Were too loose stock.
- Removed dovetail from the Neck Top and added an bit that overlaps Strum Case Top to hold everything tight once assembled. The top of the neck should be the last thing installed now.
- Added hole at the base of the neck for an M3 bolt to allow easy attaching to Strum Case Bottom.
- Lowered Fret_Switches_Board 1mm to work well with the keyboard switches I bought.
#### Combined

- Extension Case Top and Fret Case Top were combined into PB_Fret_Extension_Top_OnePiece.
- Extension Case Bottom and Fret Case Bottom were combined into PB_Fret_Extension_Bottom_OnePiece.

### Strum Case

#### Changes
- Strum Case Bottom had a hole added for an M3 heatset for attaching the Neck Bottom.
- Strum Case Bottom had holes added for usb-c extension cable mounting. https://www.amazon.com/dp/B08HS6X44P
- Strum Case Top had a void added where the Neck Top fits in to hold it in place.
- Strum Case Top had the face plate hole deepened by 1mm for reasons unknown.
- Face Plate thiccened by 1mm.
### Interior Bits

#### Changes
- Spot added to ButtonBoard to hot glue your tilt switches in place.
- Removed lip, added holes, and removed overhangs on Joystick_Board

### Frame

#### Changes
- Combined the two pieces into one piece
- Removed lip at front where it slotted into the neck.
- Added hole for M5 bolt to allow solid attachment to neck.
- Made a big ass slot to make it easier to attach your usb-c cable.

## Pico Wiring

TL;DR - Not done yet.

Get the guitar configurator here: https://github.com/sanjay900/guitar-configurator/releases

MAKE SURE YOU WIRE THE JOYSTICK X AND Y INTO PINS 31 and 32!!!

