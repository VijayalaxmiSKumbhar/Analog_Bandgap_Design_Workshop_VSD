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

#### Spice netlist for PTAT circuit

* vim ptat_circuit.sp
  
* Spice Netlist for PTAT

```
*** PTAT Voltage Generation
.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** VCVS Definition
e1    net2    gnd    ra1    qp1    gain=1000

***MOSFET Definition

xmp1    q1    net2       vdd    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmp2    q2        net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4


*** BJT Definition

xqp1    gnd    gnd    qp1    vdd sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2     vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8

*** Resistor Definition
xra1    ra1     na1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8

*** Voltage Sources for current measurement
vid1    q1    qp1    dc    0
vid2    q2    ra1    dc    0

*** Supply voltage
vsup    vdd    gnd    dc     2
.dc    temp    -40    125    5

*** control statement 
.control
run
plot v(qp1) v(ra1)
plot vid1#branch vid2#branch
.endc
.end

```


* PTAT Voltage generation output

<img width="1398" height="547" alt="image" src="https://github.com/user-attachments/assets/37c85bda-b3dd-4432-8500-c41a693de87b" />

</details>

<details>
<summary> Lab 4: CTAT design and prelayout simulation </summary>
<br>

## CTAT voltage generation circuit

<img width="697" height="257" alt="image" src="https://github.com/user-attachments/assets/2c5c84d9-1fd5-4e24-8325-3bbb410d1593" />

#### Three different cases of CTAT voltage generation

* Case 1:

<img width="440" height="242" alt="image" src="https://github.com/user-attachments/assets/f64567b0-232d-46da-9b43-0e0f5594b226" />

* Case 2:

<img width="457" height="236" alt="image" src="https://github.com/user-attachments/assets/6be3cd7a-5e80-4d51-a5bc-46f787b4893b" />

* Case 3:

<img width="481" height="212" alt="image" src="https://github.com/user-attachments/assets/c7ed97df-cf73-409a-bd4d-8533df02c63f" />

#### Spice code for CTAT circuit

```
*** CTAT Voltage Generation

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"



.global vdd gnd

.temp 27




*** BJT Definition

xqp1  gnd  gnd  qp1  gnd sky130_fd_pr__pnp_05v5_W3p40L3p40         m=1


*** Supply voltage and Current

vsup     vdd gnd dc 2

isup     vdd qp1 dc 10u

.dc temp       -40 125 5


*** control statement 

.control
run
plot v(qp1)
.endc 
.end

```

#### CTAT Voltage Generation Output

<img width="700" height="542" alt="image" src="https://github.com/user-attachments/assets/cbd30cf2-4b95-4109-9141-eb9918f217f3" />

</details>


<details>
<summary> Lab 5: PTAT design and prelayout simulation </summary>
<br>

#### Simulation of PTAT Voltage Generation

* Plot `v(qp1)`

<img width="771" height="997" alt="image" src="https://github.com/user-attachments/assets/08092667-bdf2-4265-861c-445a3ef99cf4" />

* Plot `v(qp1) v(ra1)

<img width="703" height="622" alt="image" src="https://github.com/user-attachments/assets/2c08c6bc-1d55-4e32-a4f0-565c81ffff47" />

* Plot `v(qp2) v(ra1)

<img width="712" height="638" alt="image" src="https://github.com/user-attachments/assets/5b63acef-c452-428f-b79a-068f26dcf859" />

* PTAT Voltage: ` Plot v(qp2) v(ra1) v(ra1)-v(qp2)`

<img width="727" height="606" alt="image" src="https://github.com/user-attachments/assets/063e385c-5483-4c1f-b1f9-6756a2b7b9fc" />

</details>

<details>
<summary> Lab 6: BGR (ideal) design and prelayout simulation </summary>
<br>

#### BGR Circuit using VCVS as OPAMP

<img width="600" height="491" alt="image" src="https://github.com/user-attachments/assets/eba4f243-7489-42f4-8fd1-8810a6e2012a" />

#### BGR Spice code

```
**** BGR using Ideal OPAMP (VCVS) *****



.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt
* Taking typical corner of the spice model

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"
* Included the PMOS model file

.global vdd gnd
.temp 27

*** VCVS definition
e1 net2 gnd ra1 qp1 gain=1000

*** FET definition
xmp1    q1        net2       vdd        vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmp2    q2         net2       vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmp3    q3        net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
    
*** BJT definition
xqp1    gnd        gnd        qp1        vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40        m=1
xqp2    gnd     gnd     qp2        vdd  sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3        vdd  sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition

xra1    ra1     na1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8

xrb1    vref     nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41    l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41     l=7.8
xrb17   nb16    nb17    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb18   nb17    nb18    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb19   nb18    nb19    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb20   nb19    nb20    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb21   nb20    nb21    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb22   nb21    nb22    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41       l=7.8
xrb23   nb22    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8
xrb24   nb22    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41      l=7.8

*** Voltage source for current measurement
vid1    q1    qp1        dc    0
vid2    q2    ra1        dc    0
vid3    q3    vref    dc    0

*** Supply voltage
vsup    vdd     gnd     dc      2
*.dc    vsup    0       3.3     0.3.3
.dc    temp    -40     125     5

*vsup    vdd     gnd     pulse   0       2       10n     1u      1u      1m      100u
*.tran   5n      10u

.control
RUN
 
plot v(vref)

.endc
.end

```

* Plot `v(vref)`

<img width="702" height="857" alt="image" src="https://github.com/user-attachments/assets/2386b913-f4cc-4e7b-8852-48d2529d9789" />

* Plot `v(q1) v(q2)`

<img width="706" height="737" alt="image" src="https://github.com/user-attachments/assets/24a2c932-6e38-42a8-b2fe-6aecf87f361e" />

* Plot `vid1#branch vid2#branch`

<img width="702" height="752" alt="image" src="https://github.com/user-attachments/assets/e3ed57fd-1b56-4ee7-a5a9-46fe2676633a" />

* Plot `v(qp3)`

<img width="697" height="651" alt="image" src="https://github.com/user-attachments/assets/da1f6bd6-303d-40da-b0ee-407f253abd01" />

* Plot `v(vref)-v(qp3)`

<img width="697" height="710" alt="image" src="https://github.com/user-attachments/assets/efa65089-24fd-4e61-aacd-d334bba4b940" />

* Plot `v(vref)-v(qp3) v(qp3) v(vref)`

<img width="697" height="740" alt="image" src="https://github.com/user-attachments/assets/80568ed0-347d-47f6-859b-c9b61ff995f9" />

* To measure voltage across resistance R1: Plot `v(ra1)-v(qp2)`

<img width="707" height="665" alt="image" src="https://github.com/user-attachments/assets/adbe1808-7af8-4cf7-8859-c6f207d6723e" />

</details>


<details>
<summary> Lab 7: Complete BGR design and prelayout simulation </summary>
<br>

#### Complete BGR Circuit

<img width="728" height="445" alt="image" src="https://github.com/user-attachments/assets/5e87b74e-12b3-4d35-ac55-fd5b74df3651" />


#### Simulation Case 1: BGR at SS corner

* Spice Code

```
**** Bandgap reference circuit using self-bias current mirror at ss corner****

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" ss 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** circuit definition ***

*** MOSFET definitions self-biased current mirror and output branch
xmp1    net1    net2    vdd    vdd    sky130_fd_pr__pfet_01v8_lvt    l=2    w=5    m=4
xmp2    net2    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5        m=4
xmp3    net3    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmn1    net1    net1    q1      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8
xmn2    net2    net1    q2      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8

*** start-upcircuit
xmp4    net4    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp5    net5    net2    net4    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp6    net7    net6    net2    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=2
xmn3    net6    net6    net8    gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1
xmn4    net8    net8    gnd     gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1

*** BJT definition
xqp1    gnd    gnd    qp1    vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2       vdd   sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3         vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition
xra1    ra1    na1    vdd    sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

xrb1    vref    nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb17   nb16    qp3       vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb18   nb16    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

*** voltage source for current measurement
vid1    q1    qp1    dc    0
vid2    q2      ra1     dc      0
vid3    net3    vref    dc      0
vid4    net7    net1    dc    0
vid5    net5    net6    dc    0

*** supply voltage
vsup    vdd    gnd    dc     2
*.dc    vsup    0    3.3    0.3.3
.dc    temp    -40    125    5

*vsup    vdd    gnd    pulse    0    2    10n    1u    1u    1m    100u
*.tran    5n    10u

.control
run

plot v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)
plot vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch

.endc
.end

```

* Plot `v(vref)`

<img width="712" height="703" alt="image" src="https://github.com/user-attachments/assets/1579df8b-cf15-4c4b-8c79-b3c629a170b3" />

* Plot `v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)`

<img width="698" height="547" alt="image" src="https://github.com/user-attachments/assets/618e0d27-4d6f-45fe-a04e-bde45db322db" />

* Plot `vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch`

<img width="702" height="552" alt="image" src="https://github.com/user-attachments/assets/66b3cbe2-85af-41d4-9dbc-4f3c4b35cbb2" />


#### Simulation Case 2: BGR at TT corner

* Spice Code

```
**** Bandgap reference circuit using self-bias current mirror at tt corner****

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** circuit definition ***

*** MOSFET definitions self-biased current mirror and output branch
xmp1    net1    net2    vdd    vdd    sky130_fd_pr__pfet_01v8_lvt    l=2    w=5    m=4
xmp2    net2    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5        m=4
xmp3    net3    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmn1    net1    net1    q1      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8
xmn2    net2    net1    q2      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8

*** start-upcircuit
xmp4    net4    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp5    net5    net2    net4    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp6    net7    net6    net2    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=2
xmn3    net6    net6    net8    gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1
xmn4    net8    net8    gnd     gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1

*** BJT definition
xqp1    gnd    gnd    qp1    vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2       vdd   sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3         vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition
xra1    ra1    na1    vdd    sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

xrb1    vref    nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb17   nb16    qp3       vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb18   nb16    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

*** voltage source for current measurement
vid1    q1    qp1    dc    0
vid2    q2      ra1     dc      0
vid3    net3    vref    dc      0
vid4    net7    net1    dc    0
vid5    net5    net6    dc    0

*** supply voltage
vsup    vdd    gnd    dc     2
*.dc    vsup    0    3.3    0.3.3
.dc    temp    -40    125    5

*vsup    vdd    gnd    pulse    0    2    10n    1u    1u    1m    100u
*.tran    5n    10u

.control
run

plot v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)
plot vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch

.endc
.end

```

* Plot `v(vref)`

<img width="705" height="716" alt="image" src="https://github.com/user-attachments/assets/44fe114c-546e-4d98-85f1-aba5107945c7" />

* Plot `v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)`

<img width="702" height="541" alt="image" src="https://github.com/user-attachments/assets/d73331fb-67e7-41c1-b26e-b01cf4628053" />

* Plot `vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch`

<img width="705" height="537" alt="image" src="https://github.com/user-attachments/assets/304bb4d3-9d4a-4cd7-8315-2b2d136ff170" />

#### Simulation Case 3: BGR at FF corner

* Spice Code

```

**** Bandgap reference circuit using self-bias current mirror at ff corner****

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" ff 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** circuit definition ***

*** MOSFET definitions self-biased current mirror and output branch
xmp1    net1    net2    vdd    vdd    sky130_fd_pr__pfet_01v8_lvt    l=2    w=5    m=4
xmp2    net2    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5        m=4
xmp3    net3    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmn1    net1    net1    q1      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8
xmn2    net2    net1    q2      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8

*** start-upcircuit
xmp4    net4    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp5    net5    net2    net4    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp6    net7    net6    net2    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=2
xmn3    net6    net6    net8    gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1
xmn4    net8    net8    gnd     gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1

*** BJT definition
xqp1    gnd    gnd    qp1    vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2       vdd   sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3         vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition
xra1    ra1    na1    vdd    sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

xrb1    vref    nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb17   nb16    qp3       vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb18   nb16    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

*** voltage source for current measurement
vid1    q1    qp1    dc    0
vid2    q2      ra1     dc      0
vid3    net3    vref    dc      0
vid4    net7    net1    dc    0
vid5    net5    net6    dc    0

*** supply voltage
vsup    vdd    gnd    dc     2
*.dc    vsup    0    3.3    0.3.3
.dc    temp    -40    125    5

*vsup    vdd    gnd    pulse    0    2    10n    1u    1u    1m    100u
*.tran    5n    10u

.control
run

plot v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)
plot vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch

.endc
.end

```

* Plot `v(vref)`

<img width="706" height="738" alt="image" src="https://github.com/user-attachments/assets/6eee5dfd-9a78-41d2-8773-be22a8f76ac9" />


* Plot `v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)`

<img width="701" height="547" alt="image" src="https://github.com/user-attachments/assets/307fb5a7-7fb8-4bba-9f46-b69047f4b0bc" />


* Plot `vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch`

<img width="707" height="540" alt="image" src="https://github.com/user-attachments/assets/9b88f269-dd8d-49b9-b8f0-a674bc6506ad" />

</details>

<details>
<summary> Lab 8: Detailed Startup circuit Simulation </summary>
<br>

#### Start-up circuit

<img width="687" height="440" alt="image" src="https://github.com/user-attachments/assets/3981091c-31d4-481b-865d-64c78a18c07e" />

* Simulation: Transient Analysis

* Spice code

```

**** Bandgap reference circuit using self-bias current mirror at tt corner****

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** circuit definition ***

*** MOSFET definitions self-biased current mirror and output branch
xmp1    net1    net2    vdd    vdd    sky130_fd_pr__pfet_01v8_lvt    l=2    w=5    m=4
xmp2    net2    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5        m=4
xmp3    net3    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmn1    net1    net1    q1      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8
xmn2    net2    net1    q2      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8

*** start-upcircuit
xmp4    net4    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp5    net5    net2    net4    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp6    net7    net6    net2    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=2
xmn3    net6    net6    net8    gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1
xmn4    net8    net8    gnd     gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1

*** BJT definition
xqp1    gnd    gnd    qp1    vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2       vdd   sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3         vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition
xra1    ra1    na1    vdd    sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

xrb1    vref    nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb17   nb16    qp3       vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb18   nb16    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

*** voltage source for current measurement
vid1    q1    qp1    dc    0
vid2    q2      ra1     dc      0
vid3    net3    vref    dc      0
vid4    net7    net1    dc    0
vid5    net5    net6    dc    0

*** supply voltage
*vsup    vdd    gnd    dc     2
*.dc    vsup    0    3.3    0.3.3
*.dc    temp    -40    125    5

vsup    vdd    gnd    pulse    0    2    10n    1u    1u    1m    100u
.tran    5n    10u

.control
run

plot v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)
plot vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch

.endc
.end

```

* plot ` v(vdd) v(vref) `

<img width="708" height="777" alt="image" src="https://github.com/user-attachments/assets/a4989c01-0050-4774-a9a4-794792c8fbc5" />

* plot `v(vdd) v(net2) v(net1)`

<img width="707" height="752" alt="image" src="https://github.com/user-attachments/assets/f2fded3c-f1e7-4e38-930f-46555f403518" />

* plot `v(vdd) v(net2) v(net6)`

<img width="696" height="598" alt="image" src="https://github.com/user-attachments/assets/511d4d29-10c2-40ee-ad7c-8779462c85bd" />

* Due to this current startup happens: plot `vid4#branch`

<img width="702" height="756" alt="image" src="https://github.com/user-attachments/assets/d08786d5-4f5e-405f-bd8f-af24af881aad" />

* If transistor MP6 is removed from the circuit that means no start-up circuit in BGR then following changes can be observed:

#### Spice code

```

**** Bandgap reference circuit using self-bias current mirror at tt corner****

.lib "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130.lib.spice" tt 

.include "/home/vsduser/Bandgap_IP/skywater-pdk-libs-sky130_fd_pr/models/sky130_fd_pr__model__pnp.model.spice"

.global vdd gnd
.temp 27

*** circuit definition ***

*** MOSFET definitions self-biased current mirror and output branch
xmp1    net1    net2    vdd    vdd    sky130_fd_pr__pfet_01v8_lvt    l=2    w=5    m=4
xmp2    net2    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5        m=4
xmp3    net3    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=4
xmn1    net1    net1    q1      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8
xmn2    net2    net1    q2      gnd     sky130_fd_pr__nfet_01v8_lvt     l=1     w=5     m=8

*** start-upcircuit
xmp4    net4    net2    vdd     vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
xmp5    net5    net2    net4    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=1
* xmp6    net7    net6    net2    vdd     sky130_fd_pr__pfet_01v8_lvt     l=2     w=5     m=2
xmn3    net6    net6    net8    gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1
xmn4    net8    net8    gnd     gnd     sky130_fd_pr__nfet_01v8_lvt     l=7     w=1     m=1

*** BJT definition
xqp1    gnd    gnd    qp1    vdd    sky130_fd_pr__pnp_05v5_W3p40L3p40    m=1
xqp2    gnd     gnd     qp2       vdd   sky130_fd_pr__pnp_05v5_W3p40L3p40       m=8
xqp3    gnd     gnd     qp3         vdd sky130_fd_pr__pnp_05v5_W3p40L3p40       m=1

*** high-poly resistance definition
xra1    ra1    na1    vdd    sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra2    na1     na2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra3    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xra4    na2     qp2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

xrb1    vref    nb1     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb2    nb1     nb2     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb3    nb2     nb3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb4    nb3     nb4     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb5    nb4     nb5     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb6    nb5     nb6     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb7    nb6     nb7     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb8    nb7     nb8     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb9    nb8     nb9     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb10   nb9     nb10    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb11   nb10    nb11    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb12   nb11    nb12    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb13   nb12    nb13    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb14   nb13    nb14    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb15   nb14    nb15    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb16   nb15    nb16    vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb17   nb16    qp3       vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8
xrb18   nb16    qp3     vdd     sky130_fd_pr__res_high_po_1p41     w=1.41  l=7.8

*** voltage source for current measurement
vid1    q1    qp1    dc    0
vid2    q2      ra1     dc      0
vid3    net3    vref    dc      0
vid4    net7    net1    dc    0
vid5    net5    net6    dc    0

*** supply voltage
*vsup    vdd    gnd    dc     2
*.dc    vsup    0    3.3    0.3.3
*.dc    temp    -40    125    5

vsup    vdd    gnd    pulse    0    2    10n    1u    1u    1m    100u
.tran    5n    10u

.control
run

plot v(vdd) v(net1) v(net2) v(qp1) v(ra1) v(qp2) v(vref) v(qp3)
plot vid1#branch vid2#branch vid3#branch vid4#branch vid5#branch

.endc
.end

```

* plot `v(vdd) v(net2) v(net1)`

<img width="706" height="796" alt="image" src="https://github.com/user-attachments/assets/1ac808e0-0298-47c6-b3f2-6cb671f7e058" />

* plot `v(vdd) v(net2) v(net1) v(vref)`

<img width="700" height="760" alt="image" src="https://github.com/user-attachments/assets/018e2d1a-2e7f-469f-940e-969e080b9e06" />

* Current is zero: plot `vid4#branch`

<img width="700" height="858" alt="image" src="https://github.com/user-attachments/assets/5d3c91a3-78d4-486d-b307-e4232631323b" />

* If the start-up circuit is isolated, then what is the current flowing need to be measured: plot `vid5#branch`
  * current is nA

<img width="705" height="782" alt="image" src="https://github.com/user-attachments/assets/f90df316-f502-4417-8fab-1b7b22587574" />


</details>

<details>
<summary> Lab 9: Layout of the components </summary>
<br>

* To invoke the magic, give the command ` magic -T /home/vsduser/Bandgap_IP/eda-technology/sky130/tech/magic/sky130A.tech`

<img width="1447" height="912" alt="image" src="https://github.com/user-attachments/assets/7344bdd4-9ae9-4eaa-8162-666faca99cdb" />

* For grids Press `g`

<img width="1916" height="1012" alt="image" src="https://github.com/user-attachments/assets/1c35c65f-a102-4e66-b729-f1b30bdfeed8" />

* Basic commands

| #  | Command                 | Purpose                      |
| -- | ----------------------- | ---------------------------- |
| 1  | `:layers`               | Show available layers        |
| 2  | `:layer metal1`         | Set active layer             |
| 3  | `:paint poly`           | Draw polysilicon             |
| 4  | `:paint ndiff`          | Draw n-diffusion             |
| 5  | `:paint pdiff`          | Draw p-diffusion             |
| 6  | `:paint nwell`          | Draw n-well (SKY130)         |
| 7  | `:paint metal1`         | Draw Metal1                  |
| 8  | `:paint via1`           | Via between M1–M2            |
| 9 | `:label VDD metal1`     | Label power net              |
| 10 | `:label GND metal1`     | Label ground net             |
| 11 | `:drc check`            | Run DRC                      |
| 12 | `:drc why`              | Explain DRC error            |
| 13 | `:extract all`          | Extract layout               |
| 14 | `:ext2spice lvs`        | Generate SPICE for LVS       |


#### The following devices are present in BGR circuit

* `BJTs`
* `Resistor Bank`
* `PFETs`
* `NFETs`

#### Design of Basic Cells

#### Design of NFET

* In our design `LVT` type `NFET` are used. In our design there are two different size of NFET

#### Case 1: Design of NFET with w=5 l=1

<img width="1917" height="1022" alt="image" src="https://github.com/user-attachments/assets/b7547f97-d121-4719-a8b2-6e821163d5d8" />

#### Case 2: Design of NFET with w=1 l=7

<img width="1435" height="745" alt="image" src="https://github.com/user-attachments/assets/097ffd4e-289d-4136-97da-5a7d2fba035a" />


#### Design of PFET

* In our design `LVT` type `PFET` are used
* Design of PFET with w=5 l=2

<img width="1438" height="743" alt="image" src="https://github.com/user-attachments/assets/6f8d1e47-4975-4e4e-95d0-c7d514d7b637" />

#### Design of Resistor

* Poly resistors with w=1.41 l=7.8

<img width="1435" height="737" alt="image" src="https://github.com/user-attachments/assets/b24e3895-b9ce-4adc-bcb5-4ec45a9881d7" />

#### Design of PNP type of BJT

<img width="1431" height="737" alt="image" src="https://github.com/user-attachments/assets/0b82cb8c-0932-45ec-8cd1-6af00e811da6" />

## Design of NFETS

<img width="1436" height="743" alt="image" src="https://github.com/user-attachments/assets/31793327-0401-4d49-8b66-ea7adf5f4bcb" />

## Design of PFETs

<img width="1438" height="745" alt="image" src="https://github.com/user-attachments/assets/e220a4f3-dd80-4d9c-8c12-6e0570f235a4" />

## Design of Resistor Bank

<img width="1433" height="737" alt="image" src="https://github.com/user-attachments/assets/fa66ae4a-e6fe-44ee-8799-612642c4e3da" />

## Design of BJT PNP10

<img width="1432" height="738" alt="image" src="https://github.com/user-attachments/assets/1ce1f43d-4cf3-4346-b1d6-141f45c39e74" />

## Design of Starter NFET w=1 l=7

<img width="1432" height="740" alt="image" src="https://github.com/user-attachments/assets/0db2ae48-b3a9-47c0-857c-a7b3c6316753" />

</details>


<details>
<summary> Lab 10: top-level layout extraction lvs postlayout simulation Final </summary>
<br>

## Top level Design

<img width="1426" height="737" alt="image" src="https://github.com/user-attachments/assets/f647189f-93a7-474f-a651-c55afe7ae25a" />

## Extraction of individual components

* NFET
  * Steps for Extraction
    * Go to Options then click on cell Manager
    * Click on top
    * Click on nfets
    
	<img width="442" height="425" alt="image" src="https://github.com/user-attachments/assets/2bfcf01b-9904-4668-b6f0-23884557a170" />

	* Load the cell

    <img width="1536" height="740" alt="image" src="https://github.com/user-attachments/assets/e3c6bde2-4a4c-4b87-bbfe-efb2104f42db" />

* Write the following commands for extraction
  1. extract all
  2. ext2sim label on
  3. ext2sim
  4. ext2spice scale off
  5. ext2spice hierarchy off
  6. ext2spice

  <img width="663" height="341" alt="image" src="https://github.com/user-attachments/assets/5c121c2a-59d2-4261-9283-d274c1a730bc" />



</details>


