# EXP.NO.1-EXPERIMENTAL-VERIFICATION-OF-VARIOUS-TYPES-OF-SAMPLING-TECHNIQUES
 

1.Experimental Verification Of Signal Sampling Using Various Types Such as 
    i) Natural Sampling
    ii) Flat Top Sampling

## AIM
 To perform experimental verification of various types of sampling such as natural sampling and flat top sampling.
## APPARATUS REQUIRED
Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V)   
## PROCEDURE

1. Connect the mains plug into the mains board. Keep the power switch in OFF position. 
2. Put the duty cycle selector switch in position 50%. 
3. Link 25Hz sine wave output to analog input. 
4. Turn on the trainer. 
5. Turning ON the trainer selects 250Hz sampling rate by default. 
6. Display 25Hz sine wave and sampled output on an oscilloscope. The display shows 25Hz 
    sine wave being sampled at 250Hz there are 10 samples for every cycle of the sine wave. 
7. Link the sample output to fourth order [second order + second order] low pass filter 
    display sample output and the output of filter an the oscilloscope. The display shows the 
    reconstructed original 25Hz sine wave. 
8. By successive presses of frequency selector switch change the sampling frequency 32 KHz, 
   16KHz,8KHz,4KHz,2KHz,1KHz,50KHz and back to 250Hz (sampling frequency is 1/10th 
   of the frequency indicated by the illuminated LED) observe how sample output changes 
   in each cases and how the lower sampling frequencies introduce distortion in to the filter 
   output waveform. This is due to the fact that the filter does not attenuate the unwanted 
   next frequency component significantly use of higher order filter would improve the 
   output waveform. 
9. So far, we have used sampling frequencies greater than twice the maximum input 
   frequency. To study Nyquist criteria, set sampling rate of 4 KHz, 50% duty cycle. 
10. Remove the link from 25Hz sine wave output to the modulating input. 
11. Connect the link from, 250Hz or 500Hz sinewave output to the modulating input and link 
   the sampled output to fourth order low pass filter [ 2nd order + 2nd order]. Display sample 
   output[p11] and the output of filter on the oscilloscope. The display shows the 
   reconstructed original 250Hz or 500Hz sine wave. 
12. Now decrease the sampling rate to 32 KHz and then to 500Hz. observe the distorted 
   waveform at filter’s output. This is due to the fact that we under sampled the input 
   waveform overlooking the Nyquist criteria and thus the output was distorted even though 
   the signal lie below the cut-off frequency of the filter. This also describes the phenomenon 
   of aliasing

## CIRCUIT DIAGRAM

Natural Sampling:

![image](https://github.com/user-attachments/assets/7a51fd6b-f7a8-4d53-b3e9-1ab4624cef72)

Flat-Top Sampling:

![image](https://github.com/user-attachments/assets/a374d812-5a1c-4e24-ae73-8616054857f6)


## MODEL GRAPH
Natural Sampling:

![image](https://github.com/user-attachments/assets/6fd2b770-7010-4ac2-b4ea-c00f6208e5af)

Flat-Top Sampling:

![image](https://github.com/user-attachments/assets/2303e720-33fe-4a4d-afc2-090a51d58be0)

## TABLE

![WhatsApp Image 2025-04-06 at 19 58 34_32c86cc2](https://github.com/user-attachments/assets/a8d5e211-0355-4553-ad2b-5b80afc29fa7)

## OUTPUT GRAPHS
Natural Sampling:

![WhatsApp Image 2025-04-06 at 20 14 08_5feddb4e](https://github.com/user-attachments/assets/3fce8121-71e4-4d5f-9ec5-44e33ac9618c)

Flat-Top Sampling:

![WhatsApp Image 2025-04-06 at 20 14 08_c4f4e5cf](https://github.com/user-attachments/assets/d8fd81ec-1522-4d71-b614-4b95bb247cc5)

## RESULT 
Thus the sapmpling and reconstruction of the given input signal is done using different types of sampling techniques.
