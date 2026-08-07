# F40-USB-HUB-1to4
This is a prety small USB HUB shaped like a F40. 

<img width="894" height="428" alt="aa" src="https://github.com/user-attachments/assets/4b098246-4382-4cc2-9206-44d1f60b805f" />

<img width="866" height="223" alt="image" src="https://github.com/user-attachments/assets/7f54b15c-ff3c-4b40-9e5f-fbbb401b7db3" />

It have 1 usb C to connect it to your PC and 1 usb C and 3 USB A where u can connect any of your devices.
It is made to use every USB with data transfer and not only like a charger so you can connect yuor smmartphone, racing wheel, etc,
You can design your custom case or print the one that i've done.

<img width="714" height="424" alt="image" src="https://github.com/user-attachments/assets/62264645-901d-43d9-8de8-9a7373c69202" />


I hope you like it, on JLPCB it cost more or less like 25$ without shipping costs and taxes.

<img width="1400" height="448" alt="prezzi nuovi 2" src="https://github.com/user-attachments/assets/eab80b20-6d51-41c1-b9c4-974bf7c490fa" />


Here the link to check it out: https://oshwlab.com/abbonasimone/project_bdkhchxi

Assembly:
The assembly is really easy, after you got the PCB, the components and the 3D printed case, you have to solder the components on the pcb following the schematics and then place the PCB in the case and simply screw it in with M3x5mm screws, there is no need of nuts or heat inserts, you can just screw it in the plastic.

<img width="703" height="458" alt="image" src="https://github.com/user-attachments/assets/d89c3d2a-7b5b-4852-98a3-f889fb1a9aca" />
<img width="982" height="544" alt="image" src="https://github.com/user-attachments/assets/5f1cf2e2-2896-454f-9db8-2f8718adae41" />



BOM:
|   Qty for each PCB   |      Top Designator      |       Comment       |             Footprint            |        Part #         |        Manufacturer       | JLCPCB Part # |                             Product link                            | Unit Price € | Total Price € |   |   |   |
|:--------------------:|:------------------------:|:-------------------:|:--------------------------------:|:---------------------:|:-------------------------:|:-------------:|:-------------------------------------------------------------------:|--------------|:-------------:|---|---|---|
|                    8 | C1,C2,C3,C4,C5,C6,C7,C10 | 1uF                 | C0603                            | CL10A105KB8NNNC       | Samsung Electro-Mechanics | C15849        | https://jlcpcb.com/partdetail/16531-CL10A105KB8NNNC/C15849          |       0,0653 |          0,52 |   |   |   |
|                    3 | C8,C9,C11                | 100nF               | C0603                            | CC0603JRX7R9BB104     | YAGEO                     | C91183        | https://jlcpcb.com/partdetail/YAGEO-CC0603JRX7R9BB104/C91183        |       0,0275 |          0,08 |   |   |   |
|                    2 | R1,R2                    | 5.1kΩ               | R0603                            | 0603WAF5101T5E        | UNI-ROYAL(Uniroyal Elec)  | C23186        | https://jlcpcb.com/partdetail/23913-0603WAF5101T5E/C23186           |       0,0073 |          0,01 |   |   |   |
|                    2 | R3,R4                    | 56kΩ                | R0603                            | SCR0603J56K           | VO                        | C3017697      | https://jlcpcb.com/partdetail/VO-SCR0603J56K/C3017697               |       0,0008 |          0,01 |   |   |   |
|                    1 | U1                       | SL2.1s              | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL | SL2.1s                | CoreChips                 | C2684433      | https://jlcpcb.com/partdetail/CoreChips-SL21s/C2684433              |        0,217 |          0,22 |   |   |   |
|                    2 | USB1,USB6                | TYPE-C16PIN2MD(073) | USB-C-SMD_TYPE-C-16PIN-2MD-073   | TYPE-C 16PIN 2MD(073) | SHOU HAN                  | C2765186      | https://jlcpcb.com/partdetail/SHOUHAN-TYPE_C_16PIN_2MD_073/C2765186 |       0,0637 |          0,13 |   |   |   |
|                    3 | USB2,USB3,USB4           | 10.0QHHTZB6.3       | USB-A-TH_10.0QHHTZB6.3           | 10.0 QHHTZB6.3        | SHOU HAN                  | C668591       | https://jlcpcb.com/partdetail/SHOUHAN-10_0_QHHTZB63/C668591         |       0,0573 |          0,17 |   |   |   |
|                      |                          |                     |                                  |                       |                           |               |                                                                     |              |               |   |   |   |
| Min Qty on JLPCB = 5 | PCB1                     | PCB                 |                                  |                       |                           |               |                                                                     |              |          1,73 |   |   |   |
| Min Qty on JLPCB = 2 | Assemble Top Side        | Assemble Top Side   |                                  |                       |                           |               |                                                                     |              |         26,59 |   |   |   |
|                      |                          |                     |                                  |                       |                           |               |                                                                     |              |               |   |   |   |
|                      |                          |                     |                                  |                       |                           |               |                                                                     |              |         29,46 |   |   |   |
