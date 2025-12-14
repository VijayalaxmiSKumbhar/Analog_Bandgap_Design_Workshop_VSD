# Bandgap Design Theory

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

<details>
<summary> BGR Components </summary>
<br>
	
* `CTAT` voltage generation circuit
* `PTAT` voltage generation circuit
* Self Biased Current Mirror Circuit
* Reference branch circuit
* Start-up circuit
  
</details>

<details>
<summary> CTAT Voltage generation Circuit </summary>
<br>

## CTAT Voltage generation 

<img width="922" height="337" alt="image" src="https://github.com/user-attachments/assets/55006a99-232b-459c-8657-ab1c6212545e" />

* When the constant current flows through diode or BJT voltage reduces by -2mV/degree centigrade
* The following structures are not used while designing `CTAT`
  <img width="893" height="261" alt="image" src="https://github.com/user-attachments/assets/a2758784-9ef6-430f-a183-fcabade26bd2" />

* Solution for CTAT voltage generation is as follows:

<img width="926" height="345" alt="image" src="https://github.com/user-attachments/assets/458231bb-4f17-49e9-ae68-e043d3316e89" />

* CTAT Circuit

<img width="1103" height="531" alt="image" src="https://github.com/user-attachments/assets/7bc79680-13b8-42f5-834e-80a431719627" />

* Different ways of generating CTAT voltage
  
<img width="925" height="472" alt="image" src="https://github.com/user-attachments/assets/7100a787-1bed-43f7-b38c-d79f54469bfc" />


</details>

<details>
<summary> PTAT Voltage generation Circuit </summary>
<br>

* `PTAT` Voltage generation

<img width="1336" height="718" alt="image" src="https://github.com/user-attachments/assets/caebb775-706a-4054-924d-b1790df3ee66" />

* Various plots

<img width="994" height="484" alt="image" src="https://github.com/user-attachments/assets/88c2441d-adad-4837-8080-eefd6768067f" />

* Design of R1 Resistance

<img width="1125" height="323" alt="image" src="https://github.com/user-attachments/assets/fae8cab3-0149-4164-ac85-db826216f96a" />

</details>

<details>
<summary> Self Bias Current Mirror Circuit </summary>
<br>

## Current Mirror

<img width="1041" height="502" alt="image" src="https://github.com/user-attachments/assets/4d0606e9-4773-446e-a498-9962f94cc6da" />

## Self-Biased Current Mirror

<img width="1107" height="541" alt="image" src="https://github.com/user-attachments/assets/d1ab5ec0-74dd-4706-89fd-35aefc39c81e" />

## Self-Biased Current Mirror with source resistance (Rs)

<img width="1095" height="591" alt="image" src="https://github.com/user-attachments/assets/4ddb90fe-2e79-4390-8ddc-dab9e09f2f61" />

## Self-Biased Current Mirror Summary

<img width="1045" height="502" alt="image" src="https://github.com/user-attachments/assets/7fa9e229-788e-4a21-9896-274a821671ae" />

</details>

<details>
<summary> Reference Voltage Branch Circuit </summary>
<br>

## Reference voltage branch circuit

<img width="1070" height="507" alt="image" src="https://github.com/user-attachments/assets/82cd3dc5-5954-4269-b682-fd60c0eb85a0" />

## Design of R2 Resistance

<img width="996" height="436" alt="image" src="https://github.com/user-attachments/assets/fad8769c-71f6-4773-965d-0e33d0572488" />

</details>

<details>
<summary> Start-up Circuit </summary>
<br>

## Start-up circuit Issue

<img width="1034" height="458" alt="image" src="https://github.com/user-attachments/assets/1399300c-8d2c-4d12-8f17-de0a89e27167" />

## Start-up Circuit

<img width="1039" height="501" alt="image" src="https://github.com/user-attachments/assets/8c6d29b3-04fe-425b-bcfc-9d8f72d8e4a3" />

</details>

<details>
<summary> Complete BGR Circuit </summary>
<br>

## Complete BGR Circuit

<img width="936" height="530" alt="image" src="https://github.com/user-attachments/assets/5c0863f5-f6c8-44f5-a579-f09e0b051bf2" />

</details>

# Bandgap Design Labs using SKY130

<details>
<summary> Lab 1: Tools and PDK Setup </summary>
<br>

## Analog Design Flow

<img width="563" height="641" alt="image" src="https://github.com/user-attachments/assets/3cf9b4a6-668d-4fd9-bbc1-d0c9f44bb0da" />

* Step 1: Go to the website https://github.com/google/skywater-pdk
  
* Step 2: In that go to libraries, select sky130_fd_pr then click on latest @ f62301
  
* Step 3: git clone https://github.com/google/skywater-pdk-libs-sky130_fd_pr.git
  
<img width="1152" height="346" alt="image" src="https://github.com/user-attachments/assets/2438b7d0-07e6-4584-9161-a258ef5fd3ac" />

* Step 4: git clone the link https://github.com/silicon-vlsi-org/eda-technology

<img width="730" height="237" alt="image" src="https://github.com/user-attachments/assets/796b0dd6-8ec2-4630-884f-829c21d20575" />

* Step 5: `ls` and then cd `eda-technology`

<img width="533" height="132" alt="image" src="https://github.com/user-attachments/assets/247b7144-92c0-4f53-8f59-ea2fab8c47c7" />

* Step 5: Following steps are followed to see the sky130 spice models. For the design sky130.lib.spice and sky130_fd_pr__model__pnp.model.spice will be used.

<img width="1637" height="552" alt="image" src="https://github.com/user-attachments/assets/91e2aae0-728f-4cae-b6b0-71c0996f7cee" />

* Step 6: To include library and model files in the spice, following path address need to be given

<img width="742" height="78" alt="image" src="https://github.com/user-attachments/assets/e7e03e7b-93e0-4616-9b81-4f839640c692" />

# Steps to open the Magic 

* cd `eda-technology/sky130/tech/magic`
  
* magic -T  /home/vsduser/Bandgap_IP/eda-technology/sky130/tech/magic

<img width="1692" height="867" alt="image" src="https://github.com/user-attachments/assets/9fd200d3-0cf4-43e7-aede-cd4a0a3e5f59" />

# Steps for Netgen

* cd `eda-technology/sky130/tech/netgen`


</details>

<details>
<summary> Lab 2: Design spec, Device data, Design Step </summary>
<br>

# Design Specification

<img width="702" height="323" alt="image" src="https://github.com/user-attachments/assets/fddb62ac-af82-42fe-bd87-a4448f257b27" />

# Device Datasheet: MOSFET & BJT

<img width="1091" height="585" alt="image" src="https://github.com/user-attachments/assets/5794e576-da2a-4f70-abd6-73b2f6d19b0b" />

# Device Datasheet: Resistor

<img width="1042" height="367" alt="image" src="https://github.com/user-attachments/assets/9653b9a6-0668-4f26-ac2d-35e4e612fa3f" />

# Circuit Design

* Step 1: Calculation of Current
  
<img width="786" height="255" alt="image" src="https://github.com/user-attachments/assets/a56f9a7a-4fe8-4082-81f5-18a65ab4c984" />

* Step 2: Choosing number of BJT in parallel in branch 2

<img width="1233" height="258" alt="image" src="https://github.com/user-attachments/assets/ddf1a9af-65a6-4f48-8052-ecb0a795c755" />

* Step 3: Calculation of R1

<img width="911" height="172" alt="image" src="https://github.com/user-attachments/assets/515ef033-afc0-4859-a218-d1d3e4745fa4" />

* Step 4: Calculation of R2

<img width="1195" height="347" alt="image" src="https://github.com/user-attachments/assets/1aaa0c3b-3fc6-475f-b535-19a8dd006432" />

* Step 5: PMOS design in SBCM

<img width="820" height="203" alt="image" src="https://github.com/user-attachments/assets/3dee88a0-dad8-4ae9-bc42-1c029257e217" />

* Step 6: NMOS design in SBCM

<img width="1187" height="258" alt="image" src="https://github.com/user-attachments/assets/0a7fb342-f01b-405b-8bd8-ca047bfd6597" />

# Final BGR Design

<img width="1020" height="558" alt="image" src="https://github.com/user-attachments/assets/81328301-d4da-4d57-bc56-5b7d7ad02d2f" />

</details>

<details>
<summary> Lab 3: Component design with spice netlist </summary>
<br>

# PTAT Voltage generation circuit

<img width="1135" height="589" alt="image" src="https://github.com/user-attachments/assets/3db7200f-2e7c-4568-9491-4e6d6c2b64cb" />


</details>

