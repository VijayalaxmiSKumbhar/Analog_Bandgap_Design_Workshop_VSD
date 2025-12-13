# Bandgap IP Design using SKY130 Technology Node

<details>
<summary> Introduction to Bandgap Voltage Reference (BGR) </summary>
<br>
	
 #### Block diagram of BGR

 <img width="825" height="302" alt="image" src="https://github.com/user-attachments/assets/4706c6da-006a-499a-9ef8-3962a5ab5006" /> <img width="387" height="137" alt="image" src="https://github.com/user-attachments/assets/c306cbcc-ccbb-4053-b694-0d2a54588c88" />

 * In the block diagram there is no input only VDD and GND
 * It produces the reference voltage which constant over the temperature

## Characteristics of BGR
 <img width="1247" height="272" alt="image" src="https://github.com/user-attachments/assets/29c3e07f-078b-4028-b90b-d089a77193b1" />

</details>

<details>
<summary> Why BGR </summary>
<br>
	
* A battery is unsuitable for use as a reference voltage source
  * A voltage drops over time
* A typical power supply is also not suitable
  * Noisy output and/or residual ripple
* <img width="1157" height="213" alt="image" src="https://github.com/user-attachments/assets/1066cddf-5953-4320-bf71-23cf277616c5" />

## Solution

<img width="1153" height="157" alt="image" src="https://github.com/user-attachments/assets/9f041dfb-33dd-4971-bebd-98d3e0784993" />

## Applications of BGR

<img width="652" height="380" alt="image" src="https://github.com/user-attachments/assets/4c39ffed-3cbc-425e-9274-cfac84f18093" />

* Low Dropout Regulators (LDR)

<img width="727" height="457" alt="image" src="https://github.com/user-attachments/assets/a4c944d7-d179-48e3-8cd7-6848c7ce6dc9" />

* DC-to-DC Buck Converter

<img width="772" height="497" alt="image" src="https://github.com/user-attachments/assets/3cfbc9f1-7b3f-4ea4-9003-4646704ebbd4" />

* Analog to Digital Converter (ADC)

<img width="702" height="482" alt="image" src="https://github.com/user-attachments/assets/56dd3419-5813-405c-821a-5944cd3276b1" />

* Digital to Analog Converter (DAC)

<img width="820" height="385" alt="image" src="https://github.com/user-attachments/assets/2e2a1410-e4ec-478b-a6b7-5239b87fa923" />


</details>

<details>
<summary> BGR Principle and its Types</summary>
<br>

#### BGR Principle

<img width="967" height="513" alt="image" src="https://github.com/user-attachments/assets/b5505651-25fc-4b9c-8e1a-ba38ef6d49e9" />
<img width="874" height="495" alt="image" src="https://github.com/user-attachments/assets/0a50ca92-1294-44e4-83dc-f97c456d953a" />

#### BGR Types

<img width="972" height="516" alt="image" src="https://github.com/user-attachments/assets/cd49997f-b5c6-4032-ad41-5491b9d78612" />

</details>

<details>
<summary> Self Biased Current Mirror Based BGR</summary>
<br>

## Advantages and Limitations

<img width="883" height="527" alt="image" src="https://github.com/user-attachments/assets/fce43689-5cc5-4c04-aae6-2aab08b6d624" />

</details>


