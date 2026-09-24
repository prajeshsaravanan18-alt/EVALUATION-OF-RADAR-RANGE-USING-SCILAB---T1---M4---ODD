# EVALUATION-OF-RADAR-RANGE-USING-SCILAB---T1---M4---ODD
## Aim
To calculate the maximum range of a radar system using the Radar Range Equation and verify the results through Scilab programming.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
The Radar Range Equation is a fundamental formula used in radar system design to determine the maximum range at which a radar can detect a target. 

### Mathematical Representation
The maximum radar range $R_{\max}$ is given by:

$$R_{\max} = \left( \frac{P_t G_t G_r \lambda^2 \sigma}{(4\pi)^3 P_{\min}} \right)^{\frac{1}{4}}$$

Where:
* $R_{\max}$ : Maximum detectable range of the radar (m)
* $P_t$ : Transmitted power (W)
* $G_t$ : Gain of the transmitting antenna
* $G_r$ : Gain of the receiving antenna
* $\lambda$ : Wavelength of the radar signal (m), calculated as $\lambda = \frac{c}{f}$ (where $c = 3 \times 10^8 \text{ m/s}$)
* $\sigma$ : Radar cross-section of the target ($\text{m}^2$)
* $P_{\min}$ : Minimum detectable signal power of the receiver (W)

---

## Procedure / Algorithm
1. **Set Up the Scilab Environment:** Launch the Scilab workspace/console.
2. **Define Parameters:** Set values for transmitted power ($P_t$), antenna gains ($G_t, G_r$), frequency ($f$), radar cross section ($\sigma$), and minimum power ($P_{\min}$).
3. **Calculate Wavelength:** Convert signal frequency to wavelength using $\lambda = \frac{c}{f}$, where $c = 3 \times 10^8 \text{ m/s}$.
4. **Define Radar Range Equation:** Compute the numerator and denominator using Scilab's built-in math functions and `%pi`.
5. **Calculate Maximum Range:** Evaluate $R_{\max}$ by raising the ratio to the power of $0.25$ (1/4th power).
6. **Execute and Display Results:** Run the Scilab script (`.sce`) to display the maximum radar range in meters and kilometers.

---
## PROGRAM
<img width="1053" height="1600" alt="image" src="https://github.com/user-attachments/assets/06a8f3b9-2bc4-47af-a59a-0be97294e611" />
<img width="965" height="1600" alt="image" src="https://github.com/user-attachments/assets/5ee1d3e9-823d-43cb-b85c-b137c2cd128f" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/ea3f3ea2-cd71-4a11-96ef-77a3b9e2a0b0" />

## TABULATION
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/89a2d8e1-36ce-499f-9bf9-db372785bbe0" />

## MODEL GRAPH
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/2f653e3f-ab71-4f06-a8f7-0d2c54768906" />
## MARK SPLIT UP
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/07385380-b059-4614-af88-fd51faf6ec24" />
