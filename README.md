# Pivoltage
## Lipo voltage measurement for Raspberry Pi

This code is specifically designed to be used with a Raspberry Pi Zero W, a Pimoroni LipoShim, and a MCP3002 ADC IC.

It was designed for use with an Omnipy rig [[https://github.com/winemug/omnipy/]], but can be used for any similar setup.

Please see the batt_check_3.ppt for hardware connection details - you'll want a MCP3002 in a traditional PDIP package, a Lipo Shim and a Pi Zero (W).

Please see the batt_check_4_nontest for the code. Call the function getbatt() to get the current battery level in % rounded to 5% (configurable).

_Dan Evans. 29 April 2019._
