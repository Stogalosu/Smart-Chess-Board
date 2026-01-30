# Smart Chess Board

## What?
A smart chess board that connects to your phone and automatically makes the moves you and your opponent make on the screen. It can even play against you! It works by moving a magnet under the board, thus also moving the pieces which will have magnets in them.

## Why?
Because I had this idea in the back if my head for a long time and I thought this was the perfect time. Also, I wanted a challenge, something new.

## How do I use it?
Well, I haven't thought it through, but my idea is to also make an Android app that connects through Bluetooth with the board so you can visualise the moves there, as well as make new ones. I also hope to allow players to make their own moves on the board using the Hall sensors that are in the board.

3D Render:
<img width="1517" height="844" alt="image" src="https://github.com/user-attachments/assets/766c2a24-4032-4103-a096-84ca58b42512" />

PCB that has the Raspberry Pi on it:
<img width="1317" height="860" alt="image" src="https://github.com/user-attachments/assets/4ed3d1c1-610b-49b6-97b5-e4634050e65d" />

The other PCB, which will be used 3 times to form a grid:
<img width="1313" height="855" alt="image" src="https://github.com/user-attachments/assets/a16f6f82-b392-4059-a3f9-b70393d1e6a9" />

Wiring diagrams for the special PCB:
<img width="1527" height="871" alt="image" src="https://github.com/user-attachments/assets/308e0392-0507-49e6-ae5b-e5a55a2fddb7" />
<img width="1523" height="889" alt="image" src="https://github.com/user-attachments/assets/b2d576b2-08b0-4e2c-a7f7-766299cbfb00" />

Wiring diagram for tileable PCB:
<img width="1530" height="879" alt="image" src="https://github.com/user-attachments/assets/7aafd1c9-bf85-40a9-8a66-b27abafc629a" />

Bom table:
|Name                          |Price/unit|Amount|Shipping|Product Cost|Notes           |Link                                                                                                        |
|------------------------------|----------|------|--------|------------|----------------|------------------------------------------------------------------------------------------------------------|
|X-axis guiderail              |$13,37    |1     |$0,00   |$13,37      |MGN9H, 350mm    |https://www.aliexpress.com/item/1005002516956172.html                                                       |
|Y-axis Steel Rod              |$2,21     |2     |$1,12   |$5,54       |6mm, 350mm      |https://www.aliexpress.com/item/1005007648646117.html                                                       |
|Y-axis Linear Bearing         |$1,26     |2     |$0,00   |$2,52       |LM6UU           |https://www.optimusdigital.ro/ro/mecanica-rulmenti/3812-rulment-liniar-lm6uu.html                           |
|Stepper Motor                 |$3,88     |2     |$0,00   |$7,76       |                |https://www.optimusdigital.ro/ro/motoare-motoare-pas-cu-pas/101-driver-uln2003-motor-pas-cu-pas-de-5-v-.html|
|Servomotor                    |$3,20     |1     |$0,00   |$3,20       |                |https://www.optimusdigital.ro/ro/motoare-servomotoare/26-micro-servomotor-sg90.html                         |
|Neodymium Magnet 6x3mm        |$2,26     |1     |$0,00   |$2,26       |                |https://www.emag.ro/magnet-neodim-disc-6mm-x-3mm-00004824/pd/DZW0Y6BBM/                                     |
|Neodymium Magnet 10x3mm       |$6,97     |2     |$6,48   |$20,42      |100pcs          |https://www.aliexpress.com/item/1005010439392352.html                                                       |
|GT2 Belt                      |$2,31     |1     |$1,82   |$4,13       |                |https://www.robofun.ro/3d-printer-cnc/curea-gt2-la-metru-liniar.html                                        |
|M3x6 Headless Screws          |$0,08     |10    |$0,00   |$0,77       |                |https://www.optimusdigital.ro/ro/mecanica-suruburi-si-piulite/5785-m3x6-mm-urub-de-fixare-cu-cap-plat.html  |
|M3x6 Screws                   |$0,02     |100   |$6,00   |$8,00       |Minimum quantity|https://www.tme.eu/ro/details/m3x6_d912-a2/suruburi-cu-piulita/kraftberg/                                   |
|M3x10 Screws                  |$0,03     |100   |$0,00   |$3,20       |Minimum quantity|https://www.tme.eu/ro/details/b3x10_bn3/suruburi-cu-piulita/bossard/1003771/                                |
|Steel Pins 2.5x10mm           |$4,60     |1     |$0,00   |$4,60       |50pcs           |https://www.aliexpress.com/item/1005003326358562.html                                                       |
|Steel Pins 4x30mm             |$5,04     |1     |$0,00   |$5,04       |20pcs           |https://www.aliexpress.com/item/1005003326358562.html                                                       |
|GT2 Timing Pulleys 5pcs       |$5,53     |1     |$2,99   |$8,52       |20T W6 B5       |https://www.aliexpress.com/item/1005001933418605.html                                                       |
|GT2 Idler Timing Pulleys 12pcs|$9,28     |2     |$2,99   |$21,55      |20T W6 B4       |https://www.aliexpress.com/item/1005007557987612.html                                                       |
|Hall Sensors                  |$0,41     |65    |$0,00   |$26,65      |                |https://www.tme.eu/ro/details/ss30at/senzori-hall/honeywell/                                                |
|I2C I/O expander              |$1,66     |1     |$0,00   |$1,66       |                |https://www.tme.eu/ro/en/details/tca9555pwr/interfaces-others-integrated-circuits/texas-instruments/        |
|I2C Driver                    |$1,69     |1     |$0,00   |$1,69       |                |https://www.tme.eu/ro/en/details/tbd62083afwg/drivers-integrated-circuits/toshiba/                          |
|Resistor network              |$0,30     |1     |$0,00   |$0,30       |                |https://www.tme.eu/ro/en/details/4609x-101-103lf/resistor-networks/bourns/                                  |
|Bus transciever               |$0,80     |1     |$0,00   |$0,80       |                |https://www.tme.eu/ro/en/details/sn74hct245dwr/latches/texas-instruments/                                   |
|Resistors                     |$0,03     |5     |$0,00   |$0,13       |                |https://www.tme.eu/ro/details/rc1206fr-072k7/rezistente-smd/yageo/rc1206fr-072k7l/                          |
|Inductors                     |$0,41     |4     |$0,00   |$1,64       |                |https://www.tme.eu/ro/details/b82422h1103k000/inductoare/epcos-tdk/                                         |
|Polarized Capacitors          |$0,70     |4     |$0,00   |$2,80       |                |https://www.tme.eu/ro/details/tajc107k010r/condensatoare-cu-tantal-smd/kyocera-avx/tajc107k010rnj/          |
|Capacitors                    |$0,17     |3     |$0,00   |$0,51       |                |https://www.tme.eu/ro/details/cl31b104kbcnnnd/condensatoare-mlcc-smd/samsung/                               |
|40 pin Connector Female       |$0,46     |1     |$0,00   |$0,46       |                |https://www.tme.eu/ro/details/zl262-40dg/pini-cu-benzi-si-soclu/connfly/ds1023-2-20s21/                     |
|40 pin Connector Male         |$4,51     |1     |$0,00   |$4,51       |                |https://www.tme.eu/ro/details/zl2038-40/pini-cu-benzi-si-soclu/ninigi/                                      |
|7 pin Connector Female        |$0,08     |10    |$0,00   |$0,81       |Minimum quantity|https://www.tme.eu/ro/details/zl262-7sg/pini-cu-benzi-si-soclu/connfly/ds1023-1-7s21/                       |
|4 pin Connector Female        |$0,08     |10    |$0,00   |$0,78       |Minimum quantity|https://www.tme.eu/ro/details/zl262-4sg/pini-cu-benzi-si-soclu/connfly/ds1023-1-4s21/                       |
|3 pin Connector Male          |$0,17     |1     |$0,00   |$0,17       |                |https://www.tme.eu/ro/details/tsw-103-07-l-s/pini-cu-benzi-si-soclu/samtec/                                 |
|PCBs                          |$29,40    |1     |$22,59  |$51,99      |                |                                                                                                            |
|Total Cost                    |          |      |$43,99  |$205,78     |                |                                                                                                            |
