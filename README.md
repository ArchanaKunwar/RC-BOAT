# RC Boat — CAD Design 

A fully parametric CAD model of a radio-controlled boat, designed from scratch in **Onshape**
---

### Open vs. Closed Assembly

| Assembly Open | Assembly Closed |
| :---: | :---: |
| ![Assembly Open](Images/AssemblyOpen.png) | ![Assembly Closed](Images/AssemblyClosed.png) |

### Parts

| Hull  | Lid  |
| :---: | :---: |
| ![Hull](Images/Hull.png) | ![Lid](Images/Lid.png) |

| Assembly  | Slicer  |
| :---: | :---: |
| ![Assembly](Images/Assembly.png) | ![Slicer](Images/Slicer.png) |


---

## Overview

This project contains the complete CAD design for a small RC boat, including:
- **Hull** — lofted from 4 cross-section stations
- **Deck plate** — removable top cover
- **Motor mount** — cross-shaped bracket with M3 bolt holes
- **Propeller** — 3-blade twisted prop with hub
- **Shaft & coupling** — rod connecting motor to propeller
- **Electronics layout** — battery, servo, and ESC placement inside the hull

The design is split so that each team member owns distinct sub-assemblies, making collaboration clean and reviewable.

## Team

| Member | Contribution |
|--------|-------------|
| **Bishow** | Propeller design (hub, 3 lofted blades, shaft coupling) |
| **Archana** | Hull, deck, motor mount, shaft, electronics assembly |



## Getting Started

1. Clone this repo
2. Open `.step` files in Onshape, Fusion 360, FreeCAD, or any CAD viewer
3. Open `.stl` files in your slicer (PrusaSlicer, Cura, Bambu Studio)
4. View the live Onshape document: **https://cad.onshape.com/documents/000ae551268fb42816427738/w/8f4ce627ee08794ee4e8480f/e/ccb63d3aac4362792a76f92b?renderMode=0&uiState=6aaa0bdb45a0f105887e06a2**

## Key Dimensions

| Part | Dimension |
|------|-----------|
| Hull length | ~200 mm |
| Hull width | ~90 mm |
| Hull height | ~40 mm |
| Propeller diameter | ~35 mm |
| Shaft diameter | ~3 mm |
| Motor mount hole spacing | ~16 mm |

---

# RC BOAT — Bill of Materials (BOM)

> **USD conversion:** 1 USD = NPR 150  
> Prices may vary depending on availability.

| # | Component | Specification / Product | Qty. | Price (NPR) | Price (USD) | Buy Link |
|---|---|---|---:|---:|---:|---|
| 1 | **RC Transmitter + Receiver** | FlySky FS-i6 TX + RX | 1 set | 9,000 | $60.00 | [Buy on Daraz](https://www.daraz.com.np/products/flysky-fs-i6-remote-for-quadcopter-6-channels-for-multiple-control-option-i488181181.html) |
| 2 | **LiPo Battery** | 2200mAh 3S 11.1V LiPo | 1 | 3,500 | $23.16 | [Buy on Daraz](https://www.daraz.com.np/products/2200mah-111v-35c-3s-zop-power-lipo-battery-i130076598.html?spm=a2a0e.store_keyword.list.21.ae781939ZRWD4P) |
| 3 | **Brushless Motor** | 1000KV A2212 Brushless Motor | 1 | 900 | $6.00 | [Buy on Daraz](https://www.daraz.com.np/tag/a2212/) |
| 4 | **Brushless ESC** | 30A Brushless ESC | 1 | 999 | $6.66 | [Buy on Daraz](https://www.daraz.com.np/products/30a-brushless-esc-for-rc-fixed-wing-plane-helicopter-2-3s-i292619586.html) |
| 5 | **Servo Motor** | Metal Gear MG90S Servo | 1 | 415 | $2.77 | [Buy on Daraz](https://www.daraz.com.np/tag/servo-mg/) |
| 6 | **3D Printing** | PLA filament — 158.75 g, approx. 17h 18m print | 1 | 476 | $3.17 | — |

## Total Cost

| Category | Amount |
|---|---:|
| Components | **NPR 14,200** |
| 3D Printing | **NPR 476** |
| **TOTAL** | **NPR 14,670** |
| **TOTAL (USD)** | **$97.09** |

> **Note:** 3D printing cost is calculated from approximately **158.75 g of PLA filament**, with an estimated material cost of **$3.17**.
---

## Print Settings (Recommended)

- **Layer height:** 0.2 mm
- **Infill:** 20–30% (hull), 100% (propeller)
- **Supports:** Yes for overhangs on hull
- **Material:** PETG (waterproof-ish), PLA (prototype)


##  License

This project is licensed under the **MIT License** — free to use, modify, and distribute.


---

