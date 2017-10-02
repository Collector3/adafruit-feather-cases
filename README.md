# Feather Cases

Compact cases for (most of) Adafruit's Feather series

Cases in feather-esp8266-esp32/ are compatible with the following Feather boards:

Adafruit Feather HUZZAH with ESP8266 WiFi: https://www.adafruit.com/product/2821

Adafruit HUZZAH32 – ESP32 Feather Board: https://www.adafruit.com/product/3405

For other boards, the feather-0.7-rear-spacing/ cases might work (0.7" center-to-center spacing on rear pins),
but rear pin spacing can often differ between Feather boards. Check the schematics on learn.adafruit.com for your board.

## Feather ESP8266

### Top Cover

Select one of the following (with an .stl extension):

***cover-feather-slotted***: Case cover with slots cut in the top for wire. The end slots can be used for fishing in wiring that has already been attached/soldered during prototyping.

***cover-feather-top-closed***: Fully covered/closed top.

***cover-feather-slotted-top-hold***: If your machine doesn't print the bottom cases' pins quite right, snap off the top portion and use this cover (it presses against the USB port and PCB antenna, so preferably use this as a last option).

### Bottom Case

Select one of the following (with an .stl extension):

***feather-esp8266-bottom-closed***: Case with no cutouts for headers.

***feather-esp8266-bottom-slotted***: Case with cutouts on the bottom for headers.

## Feather ESP32

The ESP32 shares top covers with the ESP8266, so pick any of the ones above and add a bottom case.

### Top Cover

Select a cover from the ESP8266 section above.

### Bottom Case

***esp32-feather-bottom***: This case has the rear pins cut in 'half' so that they fit, since the ESP32 Feather module covers part of the rear holes. Some rework may be needed post-print depending on filament/printer tolerances (or just snap them off and try the top-hold cover).

***esp32-feather-bottom-slotted***: An ESP32 case with slots for headers going out the bottom.

## Other Feathers

Feather boards that are not in the ESP series are supported by the `feather-0.7-rear-spacing` series. These cases may or may not work with all feather boards, so please check the dimensions of your board before printing.

To know if a board works with these designs, check that the center-to-center spacing between the pins on the rear are 0.7".
