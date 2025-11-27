# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS<img width="1280" height="505" alt="image" src="https://github.com/user-attachments/assets/da636c9d-a2da-4f08-af36-3afe4d4b9b48" />

## HIGH-PASS<img width="1280" height="520" alt="image" src="https://github.com/user-attachments/assets/b0225787-d9bf-4ae5-88c3-d65838e307f1" />

## BAND-PASS<img width="1591" height="485" alt="image" src="https://github.com/user-attachments/assets/8cf9bd06-315d-4229-aebc-66a7a4a6c37e" />


## MODEL GRAPH:
## LOW_PASS<img width="1280" height="536" alt="image" src="https://github.com/user-attachments/assets/d2449098-e926-4dba-bf86-f4b24229dcb0" />

## HIGH-PASS<img width="1280" height="517" alt="image" src="https://github.com/user-attachments/assets/3d923ef6-5bb9-4429-b2d9-cef20d4611a4" />

## BAND-PASS<img width="1499" height="650" alt="image" src="https://github.com/user-attachments/assets/2da68489-aa24-4285-9007-053688daa16f" />


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS<img width="1280" height="1090" alt="image" src="https://github.com/user-attachments/assets/84a09f4e-a9d3-49cd-846a-ceb9a0b6032a" />

## HIGH-PASS<img width="1115" height="1599" alt="image" src="https://github.com/user-attachments/assets/8141151b-6024-4d2d-beb5-99dfd4d46f2b" />

## BAND-PASS<img width="1387" height="837" alt="image" src="https://github.com/user-attachments/assets/5756d702-5915-430e-b921-526e064bb56b" />

## CALCULATIONS:
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## LOW_PASS
## HIGH-PASS
## BAND-PASS
## GRAPH:
## LOW_PASS<img width="918" height="1280" alt="image" src="https://github.com/user-attachments/assets/db64f056-b535-4e0c-840b-325465b4f3d2" />

## HIGH-PASS<img width="1280" height="789" alt="image" src="https://github.com/user-attachments/assets/addcc16d-32cf-41f7-befd-365cab7fe190" />

## BAND-PASS<img width="1280" height="982" alt="image" src="https://github.com/user-attachments/assets/685e8801-66a8-4cec-9e15-d61388b0ee35" />
<img width="1600" height="747" alt="image" src="https://github.com/user-attachments/assets/99411e65-1187-47fa-9120-c295b15efc5d" />

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

