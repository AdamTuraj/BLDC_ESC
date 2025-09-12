# BLDC ESC

**25A 8.4V Sensored BLDC Motor Driver (DRV8323 Based)**

This ESC was originally designed for my **AT25 project**, but the project was discontinued due to time and budget constraints. The board itself is theoretically still fully functional (I have not physically tested it).

- **Continuous Current:** 25A
- **Peak Current:** 50A
- **Input Voltage:** 8.4V (2S Li-Po)
- **Driver IC:** TI DRV8323
- **Control Mode:** Single PWM mode (simplifies control, avoids heavy math)

## Design Overview

The ESC is built around the **DRV8323** gate driver IC, making use of its 1x PWM control mode for easier firmware integration.

## Renders & Schematics

### 3D Renders

![Top 3D view](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1b5981fe5e4784d4f2b0ee5b1a6dcda7e0f423bf_image.png)  
![Bottom 3D view](https://hc-cdn.hel1.your-objectstorage.com/s/v3/7a810ac6512c31312f6ddd808e0fd90367a3e9a3_image.png)

### Electrical Schematic

![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/ddac5715fec5595bad41269cdfbf382eb142a4cd_schematic.png)

### PCB Layout (4-Layer Stackup)

- **Top Layer (Signals)**  
  ![Top Layer](https://hc-cdn.hel1.your-objectstorage.com/s/v3/9f8e1b4175542b33a1ba0a7470f9491c47891c17_top__sig_.png)

- **Second Layer (Ground Plane)**  
  ![Second Layer](https://hc-cdn.hel1.your-objectstorage.com/s/v3/7868285cecc9167cbf4e487c935e2ba2e2b22b5d_second__gnd_.png)

- **Third Layer (Power / Signals)**  
  ![Third Layer](https://hc-cdn.hel1.your-objectstorage.com/s/v3/45edf28f2726666a7836bc2db6545642fd9c70ab_third__pwr_sig_.png)

- **Bottom Layer (Signals)**  
  ![Bottom Layer](https://hc-cdn.hel1.your-objectstorage.com/s/v3/4a3391e93502b0d636ed5e2579460d9380708836_back__sig_.png)
