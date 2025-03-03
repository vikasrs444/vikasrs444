Experiment-1
Question : Given that POWER, P=100µ W; Perform DC Analysis, Transient Analysis and AC Analysis for the Given Circuit Designs and also check what happens when the width is increased or decreased of each mosfet;
Design-1 :

![image](https://github.com/user-attachments/assets/d96f953a-1b8e-43b9-b1a2-3dccc8726749)
Using the Formula for Power,
P=V*I
We will get the Values of Id as,

Id= 5.56 * 10^-5 A
we have to get the output current, Id for the given circuits by adjusting the values of L & W( Length and Width of the Channel of the MOSFET)
Length and Width of the Channel used to obtain the given Current is shown in the figure below;
![image](https://github.com/user-attachments/assets/efa916aa-343e-4b43-86ff-5a3273410926)
1)DC ANALYSIS:

Procedure for Performing DC Analysis: we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation
![image](https://github.com/user-attachments/assets/34a1ad97-7147-4fbd-9c0d-6fa6d97a26ad)
The Figure below shows the Values obtained from the DC Analysis :
![image](https://github.com/user-attachments/assets/a6069cdd-24de-4286-bfed-6a2b8a7e9407)
2)Transient Analysis:

Procedure for Performing Transient Analysis: we have to select the Transient Analysis in the Edit Simulation Command, Give the stop time as 1ms and Run the Simulation.
![image](https://github.com/user-attachments/assets/1a57004a-cc54-4041-9638-a378232e9172)
The Graphs below shows the Transient Response of the Given Design;
![image](https://github.com/user-attachments/assets/ef2ae668-e625-4452-961c-cd87a2e91886)
![image](https://github.com/user-attachments/assets/1d682ead-e4ec-4677-8679-0452f283aae5)
3)AC Analysis:

Procedure for Performing AC Analysis: we have to select the AC Analysis in the Edit Simulation Command, Give the values as shown in the figure beowl and Run th Simulation.
![image](https://github.com/user-attachments/assets/7a1ba95b-10d2-409d-86cd-d24a15a54146)
The Graph below shows the AC Analysis of the Given Design;
![image](https://github.com/user-attachments/assets/10643ee3-9ee4-46af-b99a-6bde7c563a54)
RESULT( Design-1):
1)DC Analysis:

The calculated drain current (Id) matches the expected value based on power and voltage, Id = 5.56*10^-5 A.
By adjusting the MOSFET’s channel dimensions (L & W) where L=180nm and W= 203nm, The current requirement was succesfully achecived.
The circuit behaves as expected under DC conditions.
2)Transient Analysis:

The transient response graph shows how the circuit behaves over time.
The response is smooth, with no unexpected delays or distortions.
The circuit reacts well to changes, confirming its stability.
3)AC Analysis:

The AC response graph confirms that the circuit remains stable at different frequencies.
The gain(2 dB) and phase shift(which is nearly 180deg) align with theoretical expectations.
The circuit maintains its performance across the tested frequency range.
INFERENCE( Design-1):
The experiment confirms that by properly selecting the MOSFET dimensions, we can control the drain current effectively.
Impact of Width Adjustments:
M1 has a influence on Id, meaning its width affects the output current.
The circuit performs well in all three analyses—DC, transient, and AC—demonstrating its reliability.
Overall, the design works as intended, following theoretical predictions and proving its practical feasibility.





Design-2
![image](https://github.com/user-attachments/assets/edde54de-7e3a-45d8-bf13-a5949facd63f)
Using the Formula for Power,

P=V*I/n

We will get the Values of Id as,

Id= 5.56 * 10^-5 A

we have to get the output current, Id for the given circuits by adjusting the values of L & W of both the MOSFETS M1 & M2 ( Length and Width of the Channel of the MOSFET)

DC SWEEP Analysis: This analysis is done for obataing the value of Vin in Saturation range;

we have to select the DC SWEEP in the Edit Simulation Command, Give the values as shown in the figure below and Run th Simulation.
![image](https://github.com/user-attachments/assets/7a7642cd-b3bf-49b4-b498-e03753f7e205)
The Graph below represents the VTC Curve and the value of the vin is selected as 0.7V as it is present in the saturation region of the VTC Curve
![image](https://github.com/user-attachments/assets/e5d2d8af-d4ab-4cce-beea-96a25c52f7be)
Then the input voltage parameters are given as;

![image](https://github.com/user-attachments/assets/684343c1-363f-489e-8e12-c405f55365de)
Length and Width of the Channel of the two MOSFETS used to obtain the given Current is shown in the figure below;
![image](https://github.com/user-attachments/assets/9e68ca88-9e85-4491-b88a-6f6f3bc1156f)
![image](https://github.com/user-attachments/assets/94e1c5ff-f901-4e7a-962a-e79b681c7743)
Now we will be performing the DC, Transient and AC Anlaysis;
1)DC ANALYSIS:

Procedure for Performing DC Analysis: we have to select the dc output print(DC op pnt) in the Edit Simulation Command and Run the Simulation
![image](https://github.com/user-attachments/assets/b92511aa-cd2d-413e-9d8d-d27c1d7b9fa6)
The Figure below shows the Values obtained from the DC Analysis :

![image](https://github.com/user-attachments/assets/1b40da4d-f32a-4d2b-b642-5d610d1c6d6b)
2)Transient Analysis:

Procedure for Performing Transient Analysis: we have to select the Transient Analysis in the Edit Simulation Command, Give the stop time as 1ms and Run the Simulation.
![image](https://github.com/user-attachments/assets/a6b315fc-b536-4fdd-9985-1ce1a85ccd68)
The Graphs below shows the Transient Response of the Given Design;
![image](https://github.com/user-attachments/assets/6f380642-5e85-4930-9006-a9852b9e5f49)
![image](https://github.com/user-attachments/assets/c5766f0b-0ef9-4b72-b63f-ff7f60573236)
3(AC Analysis:

Procedure for Performing AC Analysis: we have to select the AC Analysis in the Edit Simulation Command, Give the values as shown in the figure beowl and Run th Simulation.
![image](https://github.com/user-attachments/assets/047ceb7f-a48e-4f91-9158-b24529cf01dd)
RESULT(DESIGN-2)
1.DC Analysis:

The calculated drain current (Id) aligns with the expected value based on power and voltage, where the value of Id = 5.56*10^-5 A .
By fine-tuning the channel dimensions (L & W) of both MOSFETs ( M1 & M2), the desired current was achieved,
M1 : L= 180nm , W= 1105nm.
M2 : L= 180nm , W= 1105nm.
The circuit operates correctly within the selected DC parameters.
2.Transient Analysis:

The transient response graph confirms that the circuit transitions smoothly over time.
The circuit responds effectively to input variations, indicating stable operation.
3.AC Analysis:

The AC response graph confirms that the circuit maintains stability over the tested frequency range.
The gain(5.5 dB) and phase shift (which is nearly 180deg) align with theoretical expectations.
The circuit functions as expected under AC conditions.


Inference (Design-2):
The experiment validates that by appropriately selecting the MOSFET dimensions (L & W), the drain current can be precisely controlled.

The voltage transfer characteristics (VTC) helped in selecting the correct operating voltage (0.7V) for saturation.

Impact of Width Adjustments:

M2 has a stronger influence on Id, meaning its width significantly affects the output current.
M1 has a smaller influence, meaning changes in its width result in only minor variations in Id.
The design meets the expected performance criteria and follows theoretical predictions, demonstrating its feasibility in practical applications..
