# High_freq_Amp
An amplifier is an electronic device that can increase the power of a signal (a time varying voltage or current). Depending on its frequency of operation we have several types of amplifiers. As name suggests high frequency amplifiers are designed to operate at high frequencies. These have a vast variety of applications like telecommunication, high-speed electronic measurements, laser research and photonic research. When designing a high frequency amplifier, factors like bandwidth, low noise, high gain and noise immunity are extremely important. 

## outcomes
*  A high frequency amplifier which can drive a load impedance of 8W (head-phone). 
* It must be compatible with working 12V. 
* The design must be able to amplify a sine wave of 0.1V (peak-peak voltage). 
* The design must be work in the frequency range of 20 kHz – 100kHz (Bandwidth requirement) .

## Schematic Design
The schematic design of the device was in two stages pre amplifier stage and power amplifier stage. 

* The low amplitude of the input signal is insufficient for speaker action. The signal power and signal-to-noise ratio must then be increased . When amplitude are tiny the noise effect will be very strong. 

* The input sine wave’s amplitude should be increased first, with a
voltage amplifier used as a pre-Amplifying stage.
* When driving the output signal to a headset, a high power gain is
preferred. The pre-amplifier can only provide 50 mA of current,
which is not enough to operate the speaker.
* In order to produce a power amplification, we have therefore
chosen to use a class AB amplifier after the voltage amplifier.

![Screenshot 2023-08-28 230301](https://github.com/leonfdo/High_freq_Amp/assets/78163260/606622a3-9f3f-41ee-9170-45c7f30ae16a)


## PCB Design
The PCB layout is designed to accommodate high-frequency
applications while minimizing temperature increase.
* The angle between two adjacent current passing lines is taken at an obtuse angle to minimize interference.
* Two layers in the PCB are used to reduce high-frequency noise and ground the signal as rapidly as possible.
* The two transistors of TIP31C and TIP32C are power related, so they are placed in the four corners of the PCB board.
  
![Screenshot 2023-08-28 231729](https://github.com/leonfdo/High_freq_Amp/assets/78163260/3b054d89-89e2-4ecf-9f1d-de9836b342a8)



## Final Design


![Screenshot 2023-08-28 231805](https://github.com/leonfdo/High_freq_Amp/assets/78163260/d9c4085a-b2ee-4404-98a8-80c1c870e075)

