# python3-minidsp
MiniDSP 2x4HD driver in Python. Derived from [upstream fork](https://github.com/markubiak/python3-minidsp) with changed API.

I also removed the DIRAC stuff, becaue I don't have it and can't test it.

Changes from Mark's code:
- my picky api / syntax changes
- changed how to talk to HID; open/close connection on each command
- removed debug transport stub
- removed DIRAC stuff
- removed config and gain settings from command line utility to make it less likely that I damage my speakers ;-)

Mark's code was doing more of a "monitoring" of the device, I just want to send commands/get updates somewhat reliably.

