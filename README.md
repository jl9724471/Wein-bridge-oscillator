# Wein bridge oscillator
See https://en.wikipedia.org/wiki/Wien_bridge_oscillator for a description and a theory of operation.

My implementation modifies the classic design by replacing the light bulb for a photoresistor and two LEDs connected in opposite directions and driven by an op-amp as a buffer (noting this section is shielded from external light by the black felt). I've also added a magnitude adjustment by connecting the LEDs to adjustable voltage rails (equal and opposite referenced to 0V).
The frequency for now is rather random (it was determined by the components I had lying around) but I intend to set it to something more useful in the future
Other improvements could include reducing the parts count.

TODO insert schematic 

Breadboard implementation of the oscillator:

<img src="https://github.com/user-attachments/assets/ff7d9275-d18b-4742-9ae0-bca2142eb578" alt="Breadboard implementation of the oscillator" rotate="180" width="700"/>

Output spectrum of the oscillator:

<img src="https://github.com/user-attachments/assets/509e98c0-9220-42a1-af1e-bb87e8e6b895" alt="Breadboard implementation of the oscillator" width="700"/>

