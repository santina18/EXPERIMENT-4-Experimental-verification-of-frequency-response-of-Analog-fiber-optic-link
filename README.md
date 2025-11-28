# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---


## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM
![WhatsApp Image 2025-11-28 at 8 58 20 AM](https://github.com/user-attachments/assets/49050940-7984-4d46-b772-82b742bc6f07)


---



## TABULATION  
**Transmission through Analog Link**
| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
|----------------|------------------------------|--------------|------------|
|    50 Hz	     |            138v	            |     0.644	   |   1.938    |
|    3.33 Hz	  |            150v	            |     0.700    |   1.549    |
|    9.86 Hz	  |            148v	            |     0.691	   |   1.605    |
|    10.2 kHz	  |            148v	            |     0.691	   |   1.605    |
|    13 kHz	     |            148v	            |     0.68	   |   1.674    |
|    16 kHz	     |            148v	            |     0.672    |   1.726    |    
|    33 kHz	     |            148v	            |     0.684	   |   1.844    |
|    3 MHz	     |            136v  	         |     0.028	   |   1.528    |

---

## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 8 58 34 AM](https://github.com/user-attachments/assets/f5128619-ae2f-4422-a900-3f0b22c6aaca)


---
## output graph
!![WhatsApp Image 2025-11-28 at 10 51 25_aa6431f8](https://github.com/user-attachments/assets/f3774f10-202d-4298-9e13-15d255d10c07)


## RESULT

Thus, the relationship between input and received output signal from 660nm fibre optic cable using analog link is analyzed
