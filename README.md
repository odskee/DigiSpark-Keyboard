# DigiSpark-Keyboard
A C++ Keyboard Library for the DigiSpark; provides much more options than the default such as backslash


# Credits
I found this while searching for a solution to a backslash probelm - when typing a double backslash in IDE it would produce a hash '#' - other symbols were incorrect.  Credits go to Obdev's AVRUSB code


# Notes
> Replace the DigiKeyboard.h in <user-home-directory>/ArduinoData/packages/digistump/hardware/avr/<version>/libraries/DigisparkKeyboard/ with this one.
  
> Backslash was achieved by using "DigiKeyboard.sendKeyStroke(KEY_INTL_BACKSLASH);" in code.
