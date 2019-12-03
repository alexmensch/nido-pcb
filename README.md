*This respository holds the [Eagle](https://www.autodesk.com/products/eagle/overview) schematic and board CAD files for the Nido smart thermostat sensor printed circuit board (PCB). This PCB connects directly to the Raspberry Pi GPIO header for the simplest possible installation. If you're looking for instructions on how to run Nido on a Raspberry Pi, see https://github.com/alexmensch/nido for instructions and the full project background.*

## Nido PCB v2.0 (Top | CAD | Bottom)

![Nido PCB Top](https://raw.githubusercontent.com/alexmensch/nido-pcb/master/doc/top.png) ![Nido PCB CAD](https://raw.githubusercontent.com/alexmensch/nido-pcb/master/doc/eagle.png) ![Nido PCB Bottom](https://raw.githubusercontent.com/alexmensch/nido-pcb/master/doc/bottom.png)

## Bill of Materials (BOM)

Item | Reference | Qty. | Manufacturer  | Part Number   | Package | Type | Notes
:----|:----------|:-----|:--------------|:--------------|:--------|:-----|:-----
1    |JP1        |1     |TE Connectivity|1986712-2		  |         |TH    |Mount on top of board
2    |Q1         |1     |Diodes Inc     |BCW66HTA       |SOT-23-3 |SMD   |
3    |R1-3,R5    |4     |Yageo          |RC0402JR-0710KL|0402     |SMD   |
4    |C2         |1     |Samsung        |CL05A104MP5NNNC|0402     |SMD   |
5    |U2         |1     |IXYS           |CPC1017NTR	    |4-SOP    |SMD   |Align dot on chip with silkscreen dot
6    |U1         |1     |Bosch          |BME280         |8-LGA    |SMD   |Align dot on chip with silkscreen dot
7    |JP2        |1     |Sullins        |PPTC042LFBN-RC |         |TH    |Mount on bottom of board
