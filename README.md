# Boardoza TC7660S Negative Doubler Breakout Board

The **Boardoza TC7660S Negative Doubler Breakout Board** is a compact voltage conversion solution based on the **TC7660S** charge pump IC. It is designed to generate a **stable negative voltage (-VOUT)** and a  **doubled negative voltage (-2VOUT)** from a positive input supply without requiring inductors.

Using a switched-capacitor voltage converter architecture, this board efficiently inverts and doubles the input voltage, making it ideal for low-current precision analog applications. It is especially well-suited for powering operational amplifiers, sensor signal conditioning circuits, and instrumentation systems where a clean and stable negative supply is required. With a typical output capability of up to **10 mA**, it is optimized for reference and low-power analog designs rather than high-current loads.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)
| Front Side | Back Side |
| :---: | :---: |
| ![Front](./assets/TC7660S-NegativeDoubler%20Front.png) | ![Back](./assets/TC7660S-NegativeDoubler%20Back.png) |

---

## Key Features

- **Negative Voltage Generation:** Converts a single positive supply into stable negative voltage outputs.
- **Dual Output Capability:** Provides both -VOUT and -2VOUT options for flexible circuit design.
- **High Efficiency Charge Pump:** Achieves very high efficiency under light load conditions.
- **Low Power Consumption:** Optimized for precision, low-current applications.
- **Precision Focused Design:** Ideal for clean and stable reference voltage generation.

---

## Technical Specifications

**Model:** TC7660S-NegativeDoubler  
**Manufacturer:** Boardoza   
**Manufacturer IC:** Microchip Technology Inc.  
**Functions:** Negative voltage regulator  
**Input Voltage:** 1.5 V – 12 V  
**Voltage Input Type:** 2.50 mm pin header  
**Output Current:** 10 mA  
**Conversion Type:** Switched-capacitor charge pump  
**Oscillator Frequency:** Between 10 kHz to 45 kHz    
**Efficiency:** Up to 98–99% (typical, light load)  
**Operating Temperature:** -40 °C to +80 °C  
**Board Dimensions:** 40 mm × 20 mm

---

## Board Pinout

### ( J1 ) Power Input Connector

| Pin Number | Pin Name | Description |
| --- | --- | --- |
| 1 | VIN | Positive input voltage (1.5V – 12V) |
| 2 | GND | Ground |

### ( J2 ) Output Connector

| Pin Number | Pin Name | Description |
| --- | --- | --- |
| 1 | -2VOUT | Negative output, twice the input voltage |
| 2 | GND | Ground |
| 3 | -VOUT | Negative output, equal to input voltage |

---

## Board Dimensions

<img src="./assets/TC7660S-NegativeDoubler Dimensions.png" alt="Board Dimensions" width="450"/>

---

## Step Files

[Boardoza TC7660S-NegativeDoubler.step](./assets/TC7660S-NegativeDoubler%20Step.step)

---

## Datasheet

[TC7660S Datasheet.pdf](./assets/TC7660S-NegativeDoubler%20Datasheet.pdf)

---

## Version History

- V1.0.0 – Initial Release

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**
### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
