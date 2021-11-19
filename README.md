# LPT-port-P.O.S.T-reader


So, you got that 486 laptop from early '90s and you wanna play those old school DOS games, but of coures, the machine is not booting, probably BIOS battery, but you wanna cheack annyway. You go online and can't find any LPT / Parallel port / Printer port power on self test codes readers, beacuse it is ancient technology and you are living in Europe. That's why that project exists.


All THT component should be on the front side, like the ICs on the image. Design is prepared for 1 layer board, but gerber files include top layer solder mask data, because my CAD is not relly meant for single layer boards.


/*
Some people will complain that SN74LS47 will not show nice HEX values. YES, but good luck with finding the one that does! SN74LS47 is cheap, available, and manufacturers allow values >9 (the cheat sheet on the back of PCB is stright from Ti datasheet).
*/
