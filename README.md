
<img width="1920" height="1080" alt="16 Keys Macro Pad" src="https://github.com/user-attachments/assets/21c607ec-0d77-4bba-b276-1ad08401c6c8" />


---

|Title | Split-Keyboard|
|:-- |:--|
|Project Link |  [Link](https://forge.hackclub.com/projects/281) |
|Author | Sadrita Neogi|
|Platform | Forge|
|Tire | 3|

---


## Overview
This is a macro pad that has 16 customizable switches. the keys are 4 x4 Layout . I will be mainly using it for controlling music. like play, pause, skip and replay and adding macro for opening any application

---

## Project Inspiration


<img width="568" height="442" alt="1" src="https://github.com/user-attachments/assets/e83dc511-2d90-43ea-8fcc-f4da208dd088" />

### I want to make an Macro Pad  which is like this (I just draw it out of my imagination )

---
## PCB 

### For getting started I have choose Kicad for designing the PCB also the schematic 

<img width="2940" height="1912" alt="2" src="https://github.com/user-attachments/assets/ba9f8493-6a93-4d38-a9b2-d7491f9272dd" />

---

<img width="2940" height="1912" alt="3" src="https://github.com/user-attachments/assets/2322bce5-00b4-4cd1-b23d-87cfb9173e27" />

---

<img width="1838" height="1306" alt="5" src="https://github.com/user-attachments/assets/243d5286-9358-4812-a285-8c34a4d00988" />

---

<img width="1660" height="924" alt="7" src="https://github.com/user-attachments/assets/b769e452-6e69-4f5f-8d0d-e5359906341b" />


---

<img width="1096" height="1032" alt="8" src="https://github.com/user-attachments/assets/c30c534e-3c88-4792-b9ef-2d9026c88b79" />


---

## Case

### For the Case I have choose Fusion 360 for this project


<img width="1470" height="956" alt="12" src="https://github.com/user-attachments/assets/a5ff989c-f537-44df-95ab-66ab85d0652e" />


---

<img width="1470" height="956" alt="11" src="https://github.com/user-attachments/assets/7f530aa4-e5af-40a4-8957-1a94bdcbbb08" />


---

<img width="1470" height="956" alt="13" src="https://github.com/user-attachments/assets/d7a66ed6-2f75-4878-aef3-0f8e7c967179" />


---

## Top Plate 

<img width="1470" height="956" alt="14" src="https://github.com/user-attachments/assets/8eb3b186-ed86-44aa-9b99-29292d963f1e" />


---

### After Assembly

<img width="1470" height="956" alt="21" src="https://github.com/user-attachments/assets/e497fca9-f88e-4333-a31f-aaf9b2baace5" />


---

<img width="1470" height="956" alt="20" src="https://github.com/user-attachments/assets/1d1563f1-a433-40b4-b239-03bc674411f6" />


---

<img width="1470" height="956" alt="29" src="https://github.com/user-attachments/assets/e8875c9c-0dd5-4b20-9801-70b3a18f38de" />

---

### Final Model

<img width="1470" height="956" alt="30" src="https://github.com/user-attachments/assets/190828dc-b0ba-4cf8-a8c4-01cbb15e111d" />


---

<img width="1470" height="956" alt="31" src="https://github.com/user-attachments/assets/4dc60b87-65c1-4186-a4de-acb6bf415868" />


---

<img width="622" height="642" alt="32" src="https://github.com/user-attachments/assets/e7af4224-f8da-46fa-8f9f-271f98537d4a" />


---

## Assembly Instructions :-

1) First we need to get the PCB and then startrd soldering the **SK6812 MINI LEDs** to all the pads of the PCB .

2) After that we need to add the **SeeedStudio XIAO** to the designated spot on the PCb .

3) Next we will solder the  **0.91 inch Blue OLED Display** to the PCB.

4) After that we will need to connect the SeeedStudio XIAO to the PC and upload the code given in the [FIRMWARE](https://github.com/Sadrita404/16-Key-Macro-Pad/blob/main/FIRMWARE/main.py) and use **Arduino IDE** to upload the code .

5) After that we will take our 3d Printed PCB Case and and screw the pcb to the case .

6) Then we will add the 3d Printed top Plate to the Case and fix it.

7) After that we will put the  Switches in the PCB gently , to all the Places.

8) And then we will add the Key Caps to the Switches.

9) The last step connect the Keyboard to the PC and start using it...

---

## Bill Of Material (BOM)
| Name | Purpose | Qty | Total Price (USD) | Component Link | Distributor |
|------|------|------|------|------|------|
| PCB | For adding all the component | 5 | $10.00 | [Link](https://jlcpcb.com/) | JLCPCB |
| 0.91 inch Blue OLED Display | For the Display to add in the PCB | 1 | $1.61 | [Link](https://robocraze.com/products/0-91-inch-blue-oled-display-module?variant=40194383413401&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&campaignid=23607785032&adgroupid=&keyword=&device=c&gad_source=1&gad_campaignid=23597632947&gbraid=0AAAAADgHQvauLmSVauQQPRd1beTFKUXXL&gclid=Cj0KCQjw2YDQBhD_ARIsAE1qeSdtsCi1PB5ZLIsSXxdBe14DWB5-7qhPSGIfVvL-1njtE7h3b2JocGYaAlYdEALw_wcB) | Robocraze |
| M3 Heatset | For securing the PCB with the case | 4 | $0.10 | [Link](https://onlyscrews.in/products/m4-x-4mm-brass-threaded-inserts?variant=49091565650233) | Onlyscrews |
| M3x16 Bolts | For securing the PCB with the case | 16 | $0.08 | [Link](https://onlyscrews.in/products/phillips-csk-m3-x-16mm-pack-of-20?variant=48463065383225) | Onlyscrews |
| XIAO RP2040 | For Controlling the PCB | 1 | $6.35 | [Link](https://robocraze.com/products/seeed-studio-xiao-rp2040-development-board?variant=47742255562976&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&campaignid=23145906364&adgroupid=182236965810&keyword=&device=c&gad_source=1&gad_campaignid=23145906364&gbraid=0AAAAADgHQvY7vNn6tBKmEbNcZWqh0FXp9&gclid=Cj0KCQjw2YDQBhD_ARIsAE1qeSdN5Bc6n-bF-js2k0JcLxiAmVTYQn5RVq83atbN41ASwhdKKu2RFEwaAmApEALw_wcB) | Robocraze |
| SK6812 MINI LEDs | For adding to the PCB (RGB) | 16 | $0.00 | Self Sourced | Self Sourced |
| Blank DSA Keycaps | For adding to the switches | 16 | $2.24 | [Link](https://meckeys.com/shop/accessories/keyboard-accessories/keycaps/blank-dsa-keycaps-1u/) | Meckeys |
| Cherry MX Switches | For the PCB where I need to place the Switch | 16 | $3.39 | [Link](https://neomacro.in/products/outemu-lemon-v3-silent?variant=50885007147286) | Neomacro |
| 1n4148 diodes | For PCB | 16 | $0.21 | [Link](https://robu.in/product/1n4148-1w-zener-diode-pack-of-50?gclid=Cj0KCQjw2YDQBhD_ARIsAE1qeSe2U2oOhGqeyOlnmYYVhdBReY2mHgCjhgFxyJprTLmK7heT-BqfC_QaAjtLEALw_wcB&gad_campaignid=17427802703&gbraid=0AAAAADvLFWcnjaEJ_u30hDzEYqbT_rE-N&gad_source=1) | Robu |
|  Total    |       |       |          |         |     $23.98   |
## For 3d Printing I have use Legion where the cost is included in the Shipping
|Tax (USD)| Shipping (USD)|
|:-- | :--|
|$14.52 |   $17|
| Total (USD)(Including BOM)   |  $55.49  |
| Round Off Total (USD)   |  $58  |


---

#### Project Under [Hack Club](https://hackclub.com/) & [Forge](https://forge.hackclub.com/)





