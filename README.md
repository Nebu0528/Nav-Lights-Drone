# Nav-Lights-UWARG
Navigation Lights for UWARG made by Neel B and Kevin S
 
## Final Choices:

### LED Strip Reference

https://www.digikey.ca/en/products/detail/inspired-led-llc/12V-SB-RGB-5M/9091794  

Features: RGB, Surface Mount, 12V Forward Voltage

### LEDS

https://www.digikey.ca/en/products/detail/kingbright/APL3015QBC-D-F01/2263570
Features: RGB, Discrete, VDD Range (+3.3V ~ +5.5V)

### Resistors (Note: out of stock)

https://www.digikey.ca/en/products/detail/stackpole-electronics-inc/CSR0603JKR100/6270656

Features: 100 Ohm Resistors, Tolerance 0.1%

## Calculations:

### Resistors: 

Power Supply Voltage Range: 5V

Forward Voltage: 3.3V

Desired LED Current: 15mA

Resistance= (Power Supply V - Forward Voltage)/Desired LED Current

R=(5V-3.3V)/(15mA)=113.34 Ohms

With 100 Ohm Resistor: I=(5V-3.3V)/100= 17mA   Max mA=20mA

## Job File (With Screenshots)

![image](https://user-images.githubusercontent.com/85001440/159175922-9f18d7e2-988d-4cd5-ada4-5e1600070830.png)

## PCB (2D):

### Top Layer:
![image](https://user-images.githubusercontent.com/85001440/159175950-423e1fc3-7800-4a0f-b13a-d9bd05292570.png)

### Bottom Layer:
![image](https://user-images.githubusercontent.com/85001440/159175970-d4339e92-7825-4b96-b130-32eefc610570.png)

## PCB (3D):
![image](https://user-images.githubusercontent.com/85001440/159175985-50cc3a86-394a-4c63-b559-7105551ff1f8.png)

## Gerber File Preview:
![image](https://user-images.githubusercontent.com/85001440/159175996-08a99a3f-c960-421f-99ae-4a86ead8b558.png)

## Timeline:

March 13 2022, researching components needed for the led strip

March 15 2022, agreed to use option 2, calculated LED resistance and found smd resistors. Finalized part selection for the project, awaiting response from EE Leads.

March 19 2022, had meeting with EE team lead and finalized schematic

March 20 2022, small revisions and generated gerber files for production

## More Details are on the Confluence Page
https://uwarg-docs.atlassian.net/wiki/spaces/EL/pages/2036858971/Navigation+Lights
