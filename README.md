# concretelyscrewed-battery
Open Hardware eBike battery. Easy to assemble and recell.

Inspired by [vape-power-bank project](https://github.com/chrisdoelcreates/vape-power-bank)

## Specification for cs_bat_pcb_hailong_13s5p_v1
- Casing: [Hailong SSE-077](https://de.aliexpress.com/item/1005004498580462.html?gatewayAdapt=glo2deu) (more to be added later)
- Voltage: 48V setup (13S5P) (more to be added later)
- Cells: 65x 18650 ([Samsung INR18650-E35](https://www.nkon.nl/fr/samsung-inr18650-35e.html) advised to get 48V / 40A / 1900W / 16.75Ah / 780Wh), maybe not enough space considering room for screws.
- Current: Over rated current capabilities 150A (125A necessary to support [Samsung INR18650-25S](https://www.nkon.nl/fr/samsung-inr18650-25s-2500mah-25a.html))
- BMS: [Daly BMS Li-ion 13S 48V 40A](https://fr.aliexpress.com/item/1005008836055398.html?spm=a2g0o.productlist.main.4.25d47938N0tVqZ&algo_pvid=c3fa70b5-d2cb-41f5-ac36-45ff14ceecbd&algo_exp_id=c3fa70b5-d2cb-41f5-ac36-45ff14ceecbd-3&pdp_ext_f=%7B%22order%22%3A%2228%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21CHF%217.29%216.37%21%21%218.67%217.58%21%4021038df617465652867206529e2ac8%2112000046885473015%21sea%21CH%210%21ABX&curPageLogUid=GrWfwVTxUrFX&utparam-url=scene%3Asearch%7Cquery_from%3A) (48mm x 75mm x 14mm)
- Connector for balancing cables: Molex Micro-Fit Single-Row 7-pin ([molex 216571-3007](https://www.mouser.ch/ProductDetail/Molex/216571-3007?qs=pBJMDPsKWf1VoNqKJmnHYw%3D%3D), [molex 215759-1007](https://www.mouser.ch/ProductDetail/Molex/215759-1007?qs=pBJMDPsKWf2GPEsYA0UAYA%3D%3D)) 3mm pitch. But also have footprint for 2.54mm pitch and 1.27mm.
- Footprints for charging port: to solder 2x(+) and 2x(-) AWG 4 wires (Ø5.2mm)
- Footprints for discharging port: to solder 2x(+) and 2x(-) AWG 4 wires (Ø5.2mm) (AWG 8 (Ø3.3mm) is enough for 40A)
- Footprints for voltage sensing: to solder 2x(+) and 2x(-) AWG 18 wires (Ø1.0mm)
- Cells holder: 3d printable, screwed to PCB.
- Screws: [M3x35mm flat head barrel binding](https://www.harfington.com/products/p-1528134?variant=45273401491705), with [M3x45mm screws](https://www.harfington.com/products/p-1181221) number TBD
- Gaine thermo: [TRU COMPONENTS 93014c88e](https://www.conrad.ch/fr/p/tru-components-93014c88e-gaine-thermoretractable-pour-batteries-sans-colle-bleu-130-mm-65-mm-taux-de-retreint-2-1-1-pc-s-1489702.html) flat width 198mm x 333mm

## BOM
| item    | quantity | unit price  |  tot price |
|:--------|---------:|------------:|-----------:|
| Case    |        1 |  CHF 17.000 | CHF  17.00 |
| Cells   |       65 |    €  1.670 |   € 108.55 |
| BMS     |        1 |  CHF 16.160 | CHF  16.16 |
| ConnF   |        2 |  CHF  2.780 | CHF   5.56 |
| ConnM   |        2 |  CHF  0.445 | CHF   0.89 |
| Screws  |       10 |    $  0.073 |   $   0.73 |
| Binding |       10 |    $  0.326 |   $   3.26 |
| Gaine   |     0.33 |  CHF 14.950 | CHF   4.93 |
| PCB     |        1 |    $  2.400 |   $   2.40 |
| total   |          |             |~CHF 159.48 |
