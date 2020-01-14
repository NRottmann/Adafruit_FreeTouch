# Adafruit_FreeTouch

A QTouch-compatible library for Arduino. Define the touch controller as

'''
Adafruit_FreeTouch qt = Adafruit_FreeTouch(25, OVERSAMPLE_4, RESISTOR_0, FREQ_MODE_NONE, 0xFFFF),
'''

and read data with

'''
int result = qt.measure(); 
'''

