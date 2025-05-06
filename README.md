# concretelyscrewed-battery
Open Hardware eBike battery. Easy to assemble and recell.

Inspired by [vape-power-bank project](https://github.com/chrisdoelcreates/vape-power-bank)

## Specification for cs_bat_pcb_hailong_13s5p_v1
- Casing: Hailong SSE-077 (more to be added later)
- Voltage: 48V setup (13S5P) (more to be added later)
- Cells: 65x 18650 (Samsung INR18650-E35 advised to get 48V / 40A / 1900W / 16.75Ah / 780Wh), maybe not enough space considering room for screws.
- Current: Over rated current capabilities 200A (150A necessary to support Samsung INR18650-20S)
- BMS: Daly BMS Li-ion 13S 48V 40A (48mm x 75mm x 14mm)
- Connector for balancing cables: Molex Micro-Fit Single-Row 7-pin (molex 216571-3007) 3mm pitch. But also have footprint for 2.54mm pitch and 1.27mm.
- Footprints for charging port: to solder 2x(+) and 2x(-) AWG 4 wires (Ø5.2mm)
- Footprints for discharging port: to solder 2x(+) and 2x(-) AWG 4 wires (Ø5.2mm)
- Footprints for voltage sensing: to solder 2x(+) and 2x(-) AWG 18 wires (Ø1.0mm)
- Cells holder: 3d printable, screwed to PCB.
- Screws: M4 flat head barrel binding, number TBD
  - https://www.harfington.com/products/p-1545720?variant=45396336247033
  - https://www.harfington.com/products/p-1528134?variant=45273402278137
  - https://www.harfington.com/products/p-1000215?variant=42152366735609 35mm screws
  - https://www.harfington.com/products/p-1528134?variant=45273402147065 45mm binding barrel
  - https://www.harfington.com/products/p-1181221 M3x45mm screws (0.07$)
  - https://www.harfington.com/products/p-1528134?variant=45273401491705 M3x35mm binding barrels (0.33$) (outer D 4mm)
