# OpenADSBReceiver Revision 0 - Testplatform
## Info

The OpenADSBReceiver Revision 0 testplatform is a PCB shield designed to mount the GNS 5892R ADS-B Receiver Chip (https://www.gns-electronics.de/product/gns-5892r-low-power-low-cost-ads-b-modul/) onto a Luckfox Pico Ultra W Devboard (https://www.luckfox.com/Luckfox-Pico/EN-Luckfox-Pico-Ultra-W).

It bridges the GNS 5892R's UART communication to the Luckfox Pico Ultra W's UART1 port.

</br>

## Board Description

Board Size: 50x50mm

Layers: 2


| Top    | Bottom |
| -------- | ------- |
| <img src="PCB%20Images/OpenADSBReceiver_Rev0_Upper_Photo.png" alt="drawing" width="500"/>  | <img src="PCB%20Images/OpenADSBReceiver_Rev0_Lower_Photo.png" alt="drawing" width="500"/>    |





</br>

## Circuit Diagram

![grafik](PCB%20Images/OpenADSBReceiver_Rev0_Diagram.png)

</br>

## Required Hardware


| Count    | Part | Part Description | Link |
| -------- | ------- | ------- | ------- |
| 1x | U3 | Luckfox Pico Ultra W |  https://www.luckfox.com/Luckfox-Pico/EN-Luckfox-Pico-Ultra-W
| 1x | U1 |GNS 5892R ADS-B Receiver |  https://www.gns-electronics.de/product/gns-5892r-low-power-low-cost-ads-b-modul/
| 1x | Q1 | MMBT2222A 1P NPN Transistor |  https://jlcpcb.com/partdetail/9007-MMBT2222A1P/C8512
| 2x | R1, R2 | R0805 470Ohms Resistor |  https://jlcpcb.com/partdetail/18398-0805W8F4700T5E/C17710
| 1x | FRAME  | LED0805 White/Yellow |  https://jlcpcb.com/partdetail/Hubei_KentoElec-KT0805Y/C2296
| 1x | PWR | LED0805 Green |  https://jlcpcb.com/partdetail/Hubei_KentoElec-KT0805G/C2297
| 1x | C1 | C0805 100nF Ceramic Capacitor |  https://jlcpcb.com/partdetail/Yageo-CC0805KRX7R9BB104/C49678
| 1x | U2 | SMA Antenna Connector |  https://jlcpcb.com/partdetail/Henrytech-HL_SMA_KWE17502/C22355858

</br>

