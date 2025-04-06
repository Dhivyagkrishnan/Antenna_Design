
## Microstrip Antenna Design using Rogers RT5880 (1 GHz to 6 GHz)

This repository contains the design implementation of a **microstrip patch antenna** operating from **1 GHz to 6 GHz**, modeled using Rogers RT5880 lossy substrate with ε<sub>r</sub> = 2.2. The design includes the substrate, ground plane, patch, feed cut, and feed insertion.

##  Tool Used

- CST Studio Suite

## Objectives

- Design a broadband microstrip antenna covering 1 GHz to 6 GHz
- Use high-frequency substrate Rogers RT5880 with minimal loss
- Implement accurate feed and patch placement
- Visualize geometry using computer simulation tool(CST)

## Geometry Breakdown

### Substrate

- **Material:** Rogers RT5880 (lossy)  
- **ε<sub>r</sub>:** 2.2  
- **Dimensions:**  
  - **Length & Width:** 100 mm × 100 mm  
  - **Thickness (Z-axis):**
    - Z<sub>min</sub> = 0 mm  
    - Z<sub>max</sub> = 1.575 mm  

### Ground Plane

- **Material:** Same as patch  
- **Dimensions:**  
  - **Length & Width:** 100 mm × 100 mm  
  - **Z<sub>min</sub>:** -1.675 mm (1.575 + 1 mm)  
  - **Z<sub>max</sub>:** 0 mm  
  - **Total Thickness:** 1 mm  

###  Patch

- **X-dimensions:** -49/2 mm to +49/2 mm  
- **Y-dimensions:** -41.3/2 mm to +41.3/2 mm  
- **Z-position:** 0 mm (flat on top of substrate)  
- **Thickness:** 0 mm  

###  Feed Cut (Patch Cut for Feed Insertion)

- **Material:** Nickel (Cut-away region)  
- **X-dimensions:** -3.5 mm to +3.5 mm  
- **Y-dimensions:**
  - Min: -41.3/2 mm  
  - Max: (-41.3/2 + 14.5 mm)

### Feed Insertion

- **Material:** Same as patch  
- **X-dimensions:** -4.85/2 mm to +4.85/2 mm  
- **Y-dimensions:** -50 mm to 0 mm  
- **Z-dimensions:** 0 mm to 0.1 mm  


##  Output

The following images represent the simulation structure of the designed antenna:
 
### Designed Antenna
 ![image](https://github.com/user-attachments/assets/ed4b3828-f2b2-4819-a3e1-c3d29196c149)

### S- parameter plot 
![image](https://github.com/user-attachments/assets/30db6da4-499c-404a-9c59-5173cf3dcc21)



