
The topology I have used is a single stage OTA followed by a pass transistor, which is a very popular in LDO design.
The gain I get is close to 39 dB.


Design Diary-- You might find those timestamps from the Screenshots of plots that I have attached.
I didn't notice time.
The challenge that I faced was to get proper Bandwidth.
My Circuit is for 0.1nF output capacitor but as I increase the Capacitor value to 1nF my phase margin is still higher than 45 degrees. That satisfies the design criteria.



Buckets Achieved

I have used only 8 transistors for this design(minimal complexity).
I have achieved the Unity Gain Bandwidth greater than 500kHz for both 0.1nF and 1nF capacitor.
My phase margin criteria is also achieved for 1nF capacitor.
Iq is 5 uA and Vdd is 5V which means my circuit has a quiescent power usage og 25uW(25 micro watt).



***p.s- I have provided 5 plots(ac\_bode for gain and 3dB bandwidth, transient\_response for stability and slew rate, montecarlo, Phase margin for stability for both cases\_1nF and 0.1nF capacitor) and schematic in the the Submission Link***

