*This respository holds the [Eagle](https://www.autodesk.com/products/eagle/overview) schematic and board CAD files for the Nido smart thermostat sensor printed circuit board (PCB). This PCB connect directly to the Raspberry Pi GPIO header for the simplest possible installation. If you're looking for instructions on how to run Nido on a Raspberry Pi, see https://github.com/alexmensch/nido for instructions and the full project background.*

## Nido PCB v1.0 (Top)

![Nido PCB Top](https://raw.githubusercontent.com/alexmensch/nido-pcb/master/doc/top.png)

## Nido PCB v1.0 (Bottom)

![Nido PCB Bottom](https://raw.githubusercontent.com/alexmensch/nido-pcb/master/doc/bottom.png)

## Bill of Materials (BOM)

Description           | Qty. | Manufacturer Part Number (MPN)| Notes
:---------------------|:-----|:------------------------------|:--------------------
0.1µF capacitor       |1     |C320C104M5U5TA                 |Ceramic
10kΩ resistor         |4     |CF14JT10K0                     |¼W 5% axial
Signal relay          |1     |HE3621A0510                    |SPST NO 5V unshielded
BC337 transistor      |1     |BC337-25-AP                    |NPN
BME280 sensor         |1     |BME280                         |SMD packaging
2x4 female header     |1     |Generic                        |0.1" (2.54mm) pin spacing
2 wire terminal block |1     |1-2834016-2*                   |Push spring terminated

*\*This part does not match the PCB dimensions as designed in v1.0. This will be resolved in a future PCB revision.*
