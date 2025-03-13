# Wein bridge oscillator
See https://en.wikipedia.org/wiki/Wien_bridge_oscillator for a description and a theory of operation.

My implementation modifies the classic design by replacing the light bulb for a photoresistor and two LEDs connected in opposite directions and driven by an op-amp as a buffer (noting this section is shielded from external light by the black felt). I've also added a magnitude adjustment by connecting the LEDs to adjustable voltage rails (equal and opposite referenced to 0V).
The frequency for now is rather random (it was determined by the components I had lying around) but I intend to set it to something more useful in the future
Other improvements could include reducing the parts count.


Oscillator schematic:

TODO insert schematic 

Breadboard implementation of the oscillator:

<img src="https://github.com/jl9724471/Wein-bridge-oscillator/blob/main/Wein%20bridge%20oscillator.jpg?raw=true" alt="Breadboard implementation of the oscillator" width="700"/>

Output spectrum of the oscillator:

<img src="https://github.com/jl9724471/Wein-bridge-oscillator/blob/main/Wein%20bridge%20oscillator%20spectrum.jpg?raw=true" alt="Breadboard implementation of the oscillator" width="700"/>

