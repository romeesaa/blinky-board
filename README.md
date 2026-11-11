# blinky-board
a  simple pcb board that has LEDS on it. will need to write the firmware to actually make it work but i essentially followed the blinky starter project guide since this is my first ever electronics project and first time designing a pcb board (so proud yay) 

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
made this with chatgpt.

| #  | Component              | Specification              | Quantity | Purchase link                                                                                                 |
| -- | ---------------------- | -------------------------- | -------- | ------------------------------------------------------------------------------------------------------------- |
| 1  | 555 Timer IC           | NE555P, DIP-8              | 1        | [Pak Modules](https://pakmodules.com/product/ne555-timer-ic/?utm_source=chatgpt.com)                          |
| 2  | Decade Counter IC      | CD4017, DIP-16             | 1        | [Pak Modules](https://pakmodules.com/product/cd4017-decade-counter-ic/?utm_source=chatgpt.com)                |
| 3  | Red LEDs               | Standard through-hole LEDs | 10       | [Electronic Store](https://electronicstore.pk/product-category/led-penal-light/?utm_source=chatgpt.com)       |
| 4  | Orange LEDs            | Standard through-hole LEDs | Optional | [Electronic Store](https://electronicstore.pk/product-category/led-penal-light/?utm_source=chatgpt.com)       |
| 5  | Yellow LEDs            | Standard through-hole LEDs | Optional | [Electronic Store](https://electronicstore.pk/product-category/led-penal-light/?utm_source=chatgpt.com)       |
| 6  | Green LEDs             | Standard through-hole LEDs | Optional | [Electronic Store](https://electronicstore.pk/product-category/led-penal-light/?utm_source=chatgpt.com)       |
| 7  | Blue LEDs              | Standard through-hole LEDs | Optional | [Electronic Store](https://electronicstore.pk/product-category/led-penal-light/?utm_source=chatgpt.com)       |
| 8  | Resistor               | 1 kΩ, ¼ W                  | 1        | [Electronic Store](https://electronicstore.pk/product-category/resistor-through-hole/?utm_source=chatgpt.com) |
| 9  | Resistor               | 470 Ω, ¼ W                 | 1        | [Electronic Store](https://electronicstore.pk/product-category/resistor-through-hole/?utm_source=chatgpt.com) |
| 10 | Potentiometer          | 50 kΩ                      | 1        | [Art of Circuits](https://artofcircuits.com/shop?utm_source=chatgpt.com)                                      |
| 11 | Electrolytic capacitor | 1 µF, polarized            | 1        | [Electronic Store](https://electronicstore.pk/product-category/capacitor/?utm_source=chatgpt.com)             |
| 12 | Ceramic capacitor      | 0.01 µF (10 nF)            | 1        | [Electronic Store](https://electronicstore.pk/product-category/capacitor/?utm_source=chatgpt.com)             |
| 13 | 2-pin connector        | PCB power connection       | 1        | [Electronic Store](https://electronicstore.pk/product-category/connector/?utm_source=chatgpt.com)             |
| 14 | 1-pin header           | Debug output connection    | 1        | [Electronic Store](https://electronicstore.pk/product-category/connector/?utm_source=chatgpt.com)             |


| # | Item           | Specification                               | Quantity     | Purchase link                                                                                                       |
| - | -------------- | ------------------------------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------- |
| 1 | Power supply   | Regulated 5V USB supply                     | 1            | [Electronic Store](https://electronicstore.pk/product-category/battery-charger-powersupply/?utm_source=chatgpt.com) |
| 2 | PCB            | Custom-designed PCB, manufactured by JLCPCB | 1            | [JLCPCB](https://jlcpcb.com/?utm_source=chatgpt.com)                                                                |
| 3 | IC socket      | 8-pin DIP socket for NE555                  | 1 (optional) | [Electronic Store](https://electronicstore.pk/product-category/ic-socket-base/?utm_source=chatgpt.com)              |
| 4 | IC socket      | 16-pin DIP socket for CD4017                | 1 (optional) | [Electronic Store](https://electronicstore.pk/product-category/ic-socket-base/?utm_source=chatgpt.com)              |
| 5 | Soldering wire | Electronics solder                          | As needed    | [Pak Modules](https://pakmodules.com/?utm_source=chatgpt.com)                                                       |
| 6 | Jumper wires   | For testing and debugging                   | A few        | [Electronic Store](https://electronicstore.pk/product-category/jumper-wire-crimshell/?utm_source=chatgpt.com)       |

