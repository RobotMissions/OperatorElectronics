**Qty**|**Value**|**Device**|**Reference Designators (keypad)**|**Reference Designators (display)**|**Digikey part number**|**Other source**|**Notes**
:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:
1| |FE09-2W| |SV1|S5562-ND| | 
1| |JST\_2PIN-THM| |BATT1|455-1704-ND| |Only needed if you're using a LiPo battery
2|2.0K|R-US\_0207| |R9, R12|2.0KQBK-ND| | 
1|PN2222A|PN2222A| |Q1|PN2222AD26ZCT-ND| |Can also be a 2N3904 if you have that
1|5V IN|22-23-2021| |SV2|S9407-ND| |You can also just solder wires to this. Not needed if using a LiPo battery.
1|Housing for SV2| | | |S9435-ND| |Only needed for SV2
2|Pins for SV2| | | |S9473CT-ND| |Only needed for SV2
2|10u|CPOL-USE2.5-6| |C1, C2|P5134-ND| | 
1|ADAFRUIT-OLED-1.3|ADAFRUIT-OLED-1.3| |MOD2|1528-1512-ND|https://www.adafruit.com/product/938|Includes 8-pin pin header
1|Socket header for MOD2| | | |S7006-ND| |Also can get a longer header, cut in pieces, and use for this and U1
1|EG1213|EG1213| |S7|EG1906-ND| | 
1|MCP73831T-2ACI|MCP73831/OT| |U3|MCP73831T-2ACI/OTCT-ND| |Only needed if you want to charge the battery with the board
1|SPEAKER/PS12|SPEAKER/PS12| |SP1|445-2525-1-ND|https://www.adafruit.com/product/160| 
1|TEENSY\_3.2|TEENSY\_3.0+4| |U1|1528-2385-ND|https://www.pjrc.com/store/teensy32.html|Needs to be a Teensy 3.2 - 3.3V regulator on earlier versions isn't powerful enough
2|Socket header for U1| | | |S7012-ND| |Also can get a longer header, cut in pieces, and use for this and MOD2
1|5-pin pin header for U1| | | |S1011EC-05-ND| |Also can cut a piece of a longer header
1|5-pin socket header for U1| | | |S6103-ND| |Also can get a longer header, cut in pieces, and use for this and MOD2
1|XBEE|XBEE| |MOD1|602-1560-ND|https://www.adafruit.com/product/968|Also needs 2 10-pin 2mm headers and an antenna (below). For more range, use 602-1558-ND instead
2|10-pin socket 2mm header| | | |1528-1392-ND|https://www.adafruit.com/product/366|For Xbee. Come as a pair - only order one pair!
1|2.4 GHz antenna| | | |A24-HASM-450-ND|https://www.adafruit.com/product/944|For Xbee. Only needed if using the RP-SMA Xbee
6| |40-XX|S1, S2, S3, S4, S5, S6| |SW412-ND| | 
8|Green|LED5MM|LED1, LED2, LED3, LED4, LED5, LED6|LED8, LED10|C503B-GAN-CC0D0891-ND| | 
2|Red|LED5MM| |LED7, LED9|C503B-RCN-CX0Y0AA1-ND| | 
1| |MA09-2W|SV1| |S2112EC-09-ND| | 
2|10K|R-US\_0207/10|R12, R13| |10KQBK-ND| | 
11|330|R-US\_0207/10|R1, R2, R3, R4, R5, R6|R7, R8, R10, R11, R13|330QBK-ND| | 
1|EG1313|EG1313|S8| |EG2485-ND| | 
1|JOYSTICKPTH|JOYSTICKPTH|U2| |1568-1526-ND|https://www.aliexpress.com/item/3D-Analog-Joystick-Stick-Sensor-Repair-Parts-For-Microsoft-For-Xbox-360-For-PS2-Controller-Joystick/32744295312.html?spm=2114.search0104.3.10.YIwqqZ&ws\_ab\_test=searchweb0\_0,searchweb201602\_1\_10152\_10065\_10151\_10344\_10068\_10130\_10345\_10342\_10547\_10343\_10340\_10341\_10548\_10541\_10084\_10083\_10139\_10307\_10178\_10060\_10155\_5640011\_10154\_5370011\_10056\_10055\_10539\_10538\_10537\_10312\_10536\_10059\_10313\_10314\_10534\_10533\_100031\_10103\_10073\_10102\_5720011\_10142\_10107,searchweb201603\_1,ppcSwitch\_5&btsid=da10db06-a55d-4e19-ba11-507ed7700f7d&algo\_expid=3cc89f35-19bb-4318-881e-d405c70ba0de-1&algo\_pvid=3cc89f35-19bb-4318-881e-d405c70ba0de|Much cheaper from Aliexpress. Also need joystick cap.
1| |Joystick Cap|-| |-|https://www.aliexpress.com/item/High-Quality-Analog-3D-Thumb-Sticks-Joystick-Thumbstick-Mushroom-Cap-Cover-For-PS2-Controller-Thumb-Grips/32763331342.html?spm=2114.search0104.3.73.LJbVnk&ws\_ab\_test=searchweb0\_0,searchweb201602\_1\_10152\_10065\_10151\_10344\_10068\_10130\_10345\_10342\_10547\_10343\_10340\_10341\_10548\_10541\_10084\_10083\_10139\_10307\_10178\_10060\_10155\_5640011\_10154\_5370011\_10056\_10055\_10539\_10538\_10537\_10312\_10536\_10059\_10313\_10314\_10534\_10533\_100031\_10103\_10073\_10102\_5720011\_10142\_10107,searchweb201603\_1,ppcSwitch\_5&btsid=9a0e423b-ad57-4341-9268-c438ec8125bd&algo\_expid=6906629b-d6ff-4fad-8999-3167be9cbc5a-9&algo\_pvid=6906629b-d6ff-4fad-8999-3167be9cbc5a|Not needed if Joystick includes one