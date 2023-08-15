# Demonstration-of-wave-propagation
Demonstration of wave propagation within a transmission line for varying load impedances (0,50,100) ohms via animation using MATLAB

# THEORY OF TRANSMISSION LINES
A transmission line can be analyzed either by the solution of Maxwell's field equations or by the methods of distributed-circuit theory. The solution of Maxwell's equations involves three space variables (X,Y,Z) in addition to the time variable(t). The distributed-circuit method, however, involves only one space variable in addition to the time variable. the distributed circuit method is used to analyze a transmission line in terms of the voltage, current, impedance, and power along the line. Based on uniformly distributed-circuit theory, the schematic circuit of a conventional two-conductor transmission line with constant parameters R, L, G, and C are used. The parameters are expressed in their respective names per unit length, and the wave propagation is assumed in the positive z direction.

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/167bcf71-11ac-4858-99a1-7017b18fde3c)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/cad06cec-2f7a-4fd5-b8fb-fed96fe8ffdb)

# FORMATION OF WAVES INSIDE A TRANSMISSION LINE

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/21325f52-43ec-4922-b64c-518c33043ee8)

1)	When Z0=50 ohms, ZL=0 ohms,
We observe standing waves (resultant of both forward travelling wave and backward travelling wave).
2)	When Z0=50 ohms, ZL=50 ohms,
We observe a forward travelling wave propagating along the line.
3)	When Z0=50 ohms, ZL=100 ohms,
We observe a hybrid wave propagating along the line.

# ANIMATION OF STANDING WAVES USING MATLAB
•	Z0=50 ohms, ZL=0 ohms.
There is a forward travelling wave and a backward travelling wave whose resultant leads us to the formation of standing waves.

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/4e5f87cc-0705-44ee-a4c3-ca57c1b215a9)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/26ec4268-3695-4c51-b32e-7e6d1ea7d2ee)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/071db03e-764b-4d9e-a8df-52c0d193ab2b)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/bedc180d-e939-48a6-89d7-a1af9fba24e8)

BLUE WAVE- Indicates forward travelling wave.
RED WAVE- Indicates backward travelling wave.
ORANGE WAVE- Indicates the resultant of both the waves leading to formation of standing waves.

# ANIMATION OF TRAVELLING WAVE USING MATLAB
•	Z0=50 ohms, ZL=50 ohms.
There is a forward travelling wave propagating through the transmission line as it is a matched termination and there is no formation of backward travelling wave.

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/9b21d1b6-e77c-4159-a2e0-c604148b7b0f)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/7758229b-ab49-4711-b21b-86fcae025396)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/e6c289dd-b7a8-4568-9c8e-8b6983630534)

BLUE WAVE- Indicates forward travelling wave

# ANIMATION OF HYBRID WAVE USING MATLAB

•	Z0=50 ohms, ZL=100 ohms.
There is a forward travelling wave propagating through the transmission line and a backward travelling wave with a lower amplitude (0.707 of initial amplitude), the resultant of these two waves appear to be standing and travelling at different instants of time, giving rise to the hybrid wave.

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/cbbef9c9-e5f7-477c-be51-a2a04912e5d6)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/c2dc8c67-94f4-4b2f-8f00-3b217cbc4ff9)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/4ada7029-d375-4dfd-86e1-63a122d60a54)

![image](https://github.com/Vaishd30/Demonstration-of-wave-propagation/assets/139155413/9bf14b58-a24a-48e4-9032-580f32192257)

BLUE WAVE- Indicates forward travelling wave.
RED WAVE- Indicates backward travelling wave with reduced amplitude.
ORANGE WAVE- Indicates the resultant of both the waves .

# REFERENCES
1.	Microwave Devices and Circuits, Book by Samuel Y. Liao (3rd edition).
2.	Amit Singh (2022). Animating travelling waves (https://www.mathworks.com/matlabcentral/fileexchange/89223-animating-travelling-waves), MATLAB Central File Exchange. Retrieved June 3, 2022.
3.	Behind The Sciences (2022). Standing Wave Ratio (https://www.mathworks.com/matlabcentral/fileexchange/61089-standing-wave-ratio), MATLAB Central File Exchange. Retrieved June 3, 2022
4.	https://www.youtube.com/watch?v=5u1XX5kfID0 as a reference for understanding the concept behind standing wave formation.















