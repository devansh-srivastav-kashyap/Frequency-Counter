# Frequency-Counter

Introduction-

This device measures the frequency of the low frequency signal. 

# Equipments Used- 

1- 7 Segment Display Common Cathode Red

2- CD4033 7 Segment Counter

3- OpAmp UA709

4- Resistors and Capacitors

5- Batteries

6- Proteus 8 Professional

# Working Principle- 

This device works on the basic defintion of the frequency. Frequency is defined as the number of cycles made in 1 second. We utilised this concept to find the frequency. Using the Opamps UA709 (Schmiddt Trigger), we convert the incoming sinusoidal signal into pulses. This converted pulse is given as the clock to the IC CD4033. This number of pulse will be counted. 

Now, it is required that the pulse is counted only for 1 sec, then only we will get the frequency of the signal. This can be done by applying a pulse to the Clock Inhibit of the CD4033 of the rightmost IC. While the applied pulse is down( for 1 sec), CD4033 will count and as Clock Inhibit pin is turned to high, the counting shall stop and we will get our frequency.

# Construction

For input, we are using the function generator. 
