# filtercalc
A simple one-page web app to calculate the capacitor and resistor values needed for an audio high-pass or low-pass filter. 

First order passive filters are easily created in audio circuits using capacitors and resistors of appropriate values placed properly in the circuit. 
Rather than opening calc.exe or asking an AI, you can use this application to enter a value for the "corner frequency" (where the level drop = -3 dB) for a filter, specifiying via a radio button whether you want a high pass or low-pass filter. The program will provide the values needed in some power-of-10 Farads and Ohms for resistors. The three digit code commonly used for capacitors such as "104" will also be provided, and resistors display not only the value in Ohms but list the color bands found on such resistors. 
The output also includes an SVG format audio frequency diagram, log scale audio frequency from zero to 24 kHz on the X-axis and decibels on the Y-Axis, range of at least -18 decibels displayed. showing the frequency response of the filter with a dot and label identifying the corner frequency. 
Also in the output, there is a simplified vector (SVG format) circuit diagram showing how the filter would be implemented. 

You do not need to install anything to use the filter calc. 
