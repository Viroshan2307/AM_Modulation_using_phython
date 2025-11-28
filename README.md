# AM_Modulation_using_phython


Aim


To implement and analyze amplitude modulation (AM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Modulation can be defined as the process by which the characteristics of carrier wave are varied in accordance with the modulating wave (signal). Modulation is performed in a transmitter by a circuit called a modulator. Need for modulation is as follows: • Avoid mixing of signals • Reduction in antenna height • long distance communication • Multiplexing • Improve the quality of reception • Ease of radiation. Amplitude Modulation is the process of changing the amplitude of a relatively high frequency carrier signal in proportion with the instantaneous value of the modulating signal. The output waveform contains all the frequencies that make up the AM signal and is used to transport the information through the system. Therefore the shape of the modulated wave is called the AM envelope. With no modulating signal the output waveform is simply the carrier signal. Coefficient of modulation is a term used to describe the amount of amplitude change present in an AM waveform. There are three degrees of modulation available based on value of modulation index.

Under modulation : m<1, Em < Ec
Critical modulation: m-1, Em = Ec
Over modulation: m>1, Em > Ec
Note: Keep all the switch faults in off position

Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate AM Signal: Apply the AM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program
<img width="710" height="529" alt="Screenshot 2025-11-28 161017" src="https://github.com/user-attachments/assets/d999490e-06d0-4d7e-8d5a-f1e37df75e3c" />


Output Waveform

<img width="830" height="593" alt="Screenshot 2025-11-28 161023" src="https://github.com/user-attachments/assets/78a0f387-e40c-4fc7-b2f2-025a5b5fb4b4" />



Tabular Column
![WhatsApp Image 2025-11-28 at 16 12 32_2a6ffdc2](https://github.com/user-attachments/assets/66ec2cae-4133-4a07-82f8-d4986b411178)


Calculation


ma (Theory) = am/ac = 6.7/13.4=0.5
ma(Practical) = (Emax-Emin)/(Emax+Emin) =13/27.2=0.477



Result


Thus the amplitude modulation and demodulation is experimentally done and the output is verified.
