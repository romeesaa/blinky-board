# blinky-board
a  simple pcb board that has LEDS on it. will need to write the firmware to actually make it work but i essentially followed the blinky starter project guide since this is my second ever electronics project and second time designing a pcb board (so proud yay) 

the guide I used: https://blueprint.hackclub.com/starter-projects/blinky 

# the final look
<img width="755" height="482" alt="image" src="https://github.com/user-attachments/assets/c209359b-cfdd-4ec9-a433-bc0faad134fb" />

# the struggles
1) random DRC errors that caused me to change the shape of my pcb board
2) routing (took me some time to figure out u can use two layers but we ball)
3) showing a cute shape and (whatever changed it anyways)
4) trying to import the foot prints (i am stupid)
5) connecting the schematic (grateful that i got no errors this time)

<img width="726" height="821" alt="image" src="https://github.com/user-attachments/assets/217050d2-6a30-4d0c-95f1-505ea8c94d16" />

the shape before i got lazy and gave up because of the errors
:( 

<img width="855" height="724" alt="image" src="https://github.com/user-attachments/assets/1fbd7478-5e7e-40b7-9443-b7cc5fd33a55" />

the schematic 
<img width="847" height="736" alt="image" src="https://github.com/user-attachments/assets/73464592-602d-44fb-b56e-14aaef8834b1" />

the pcb routing (idk whats this called yet..)

<img width="633" height="450" alt="image" src="https://github.com/user-attachments/assets/18a6e07d-bae2-4e7d-8090-610c78957b20" />

an easter egg :

<img width="63" height="57" alt="image" src="https://github.com/user-attachments/assets/c61ea111-c9c5-44f3-8a72-9805b9095dbc" />

# bom


| #  | Component              | Specification       | Qty.     | Price (PKR) | Purchase link                                                                                        |
| -- | ---------------------- | ------------------- | -------- | ----------- | ---------------------------------------------------------------------------------------------------- |
| 1  | 555 Timer IC           | NE555P, DIP-8       | 1        | 30          | [Pak Modules](https://pakmodules.com/?utm_source=chatgpt.com)                                        |
| 2  | Decade Counter IC      | CD4017, DIP-16      | 1        | 65          | [Electronic Store](https://electronicstore.pk/product/cd4017-ic-in-pakistan/?utm_source=chatgpt.com) |
| 3  | Red LEDs               | 5mm through-hole    | 10       | 30          | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 4  | Orange LEDs            | 5mm through-hole    | Optional | 3 each      | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 5  | Yellow LEDs            | 5mm through-hole    | Optional | 3 each      | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 6  | Green LEDs             | 5mm through-hole    | Optional | 3 each      | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 7  | Blue LEDs              | 5mm through-hole    | Optional | 3 each      | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 8  | Resistor               | 1 kΩ, ¼ W           | 1        | 2–5         | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 9  | Resistor               | 470 Ω, ¼ W          | 1        | 2–5         | [Circuit.pk](https://circuit.pk/category/resistor?utm_source=chatgpt.com)                            |
| 10 | Potentiometer          | 50 kΩ               | 1        | 10          | [Electronation](https://electronation.pk/product-category/common-components/?utm_source=chatgpt.com) |
| 11 | Electrolytic capacitor | 1 µF                | 1        | 5–10\*      | [Electronic Store](https://electronicstore.pk/product-category/capacitor/?utm_source=chatgpt.com)    |
| 12 | Ceramic capacitor      | 10 nF               | 1        | 5–10\*      | [Electronic Store](https://electronicstore.pk/product-category/capacitor/?utm_source=chatgpt.com)    |
| 13 | 2-pin connector        | PCB power connector | 1        | 10–20\*     | [Electronic Store](https://electronicstore.pk/product-category/connector/?utm_source=chatgpt.com)    |
| 14 | 1-pin header           | Debug output        | 1        | 5–10\*      | [Electronic Store](https://electronicstore.pk/product-category/connector/?utm_source=chatgpt.com)    |


| # | Item           | Specification       | Qty.      | Estimated price (PKR) | Purchase link                                                                                                       |
| - | -------------- | ------------------- | --------- | --------------------- | ------------------------------------------------------------------------------------------------------------------- |
| 1 | Power supply   | Regulated 5V USB    | 1         | 250–400               | [Electronic Store](https://electronicstore.pk/product-category/battery-charger-powersupply/?utm_source=chatgpt.com) |
| 2 | PCB            | Custom-designed PCB | 1         | Not yet quoted        | [JLCPCB](https://jlcpcb.com/?utm_source=chatgpt.com)                                                                |
| 3 | IC socket      | 8-pin DIP           | 1         | 10–15                 | [Electronic Store](https://electronicstore.pk/product-category/ic-socket-base/?utm_source=chatgpt.com)              |
| 4 | IC socket      | 16-pin DIP          | 1         | 15–25                 | [Electronic Store](https://electronicstore.pk/product-category/ic-socket-base/?utm_source=chatgpt.com)              |
| 5 | Soldering wire | Electronics solder  | As needed | 150–250               | [Pak Modules](https://pakmodules.com/?utm_source=chatgpt.com)                                                       |
| 6 | Jumper wires   | Testing/debugging   | A few     | 50–100                | [Electronic Store](https://electronicstore.pk/product-category/jumper-wire-crimshell/?utm_source=chatgpt.com)       |

funding needed : 1000-2000 rs or (3.61 US Dollars to 7.22 US Dollars to cover the shipping costs and everything)
