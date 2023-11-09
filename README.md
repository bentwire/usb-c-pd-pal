# usb-c-pd-pal
100W USB C PD Power path with on board switches and current sensing.  Can take input from USB-C, Barell, or wire terminal, and output to wire terminal or USB-C.

This design can do up to 100W PD.  The switches and connectors are all rated for 5A, the max voltage is 21V so it can't do the extended power ranges.

There is a separate power path for both the 5V only and High Power paths.  The board is wired to be capable of both sink and source modes.

If you wish to make this board act as a source you will need to provide 5V to the 5V power path at the very least.

TODO:
Code forthcoming.
Still need to finish the layout.
Some parts won't be generally available until next year...
