# TD_mutiSlider
A simple and easy to use multislider tool with limit/scale, default value, labeled channels and touchOSC template
You have a touchOSC file to build an easy remote controler

There is two input, one for preset list, other for values, scaled 0 to 1, labeled S1 to S10
There is one output for values with scales and labels according to table.

Use the inside table or link an external table with the settings:
- name for name of parameter (only letters, numbers, underscore)
- min, max and default values - digits for number of decimal numbers displayed
- int for rounding (0 no rounding, 1 ceiling, 2 floor, 3 round)

In the parameters window:
- Reset to return values to default and send labels to OSC
- inPort for the incoming OSC port
- outPort for the outgoing OSC port
- ipSend for IP number of the receiver
You can reset each value to default right-clicking on each slider

With touchOSC, you can reset each slider to its default value pressing the red button on the right
