# 🔋 Scalable 18650 Power Bank

A modular, 3D-printable power bank designed for 18650 Li-ion cells. Scale it to any capacity you need — from a compact 1-cell build to a high-capacity multi-cell pack.

---

## ✨ Features

- **Fully 3D printable** — all structural parts are designed for FDM printing
- **Modular & scalable** — supports any number of 18650 cells
- **USB-C PD** — up to 20W input and output
- **USB Type-A QC** — Quick Charge protocol support
- **IP5328P IC** — advanced power management with battery protection
- **SOC indicator** — state of charge LED indicator

---

## 📐 Specifications

| Parameter | Value |
|---|---|
| Cell Type | 18650 Li-ion |
| Number of Cells | Scalable (2 and above) |
| Power Management IC | IP5328P |
| Charging Input | USB-C PD, up to 20W |
| Output | USB-C PD 20W / USB-A QC |
| Enclosure | 3D Printed (FDM) |
| Fasteners | M3 screws & nuts |

---

## 🛒 Bill of Materials (BOM)

| Item | Quantity | Notes |
|---|---|---|
| 18650 Li-ion cells | N × cells | Any standard 18650 |
| IP5328P controller PCB | 1 | Commercially available (search "IP53288P")|
| M3 nuts | 4 | Press-fit into printed holes |
| M3 screws | 4 | For lid fastening |
| 3D printed parts | — | See print files |
### Control Board sample pictire
![pcb](/images/PCB.jpg)

---

## 🖼️ Images

![CAD design](/images/Screenshot%202026-06-15%20123551.png)
![front view](/images/IMG_0278.JPG)
![inside view](/images/IMG_0279.JPG)
![compare](/images/IMG_0280.jpg)

---

## 🖨️ Printing Guidelines

- **Material:** PLA or PETG recommended
- **Infill:** 20–30%
- **Supports:** Required for nut pockets and button hole
- **Layer height:** 0.2mm

---

## 🔧 Assembly Guide

1. **Print all parts** from the provided files
2. **Insert M3 nuts** into the designated press-fit pockets
![nut](/images/IMG_0282.jpg)
3. **Glue the push button** onto the top case — ensure it actuates smoothly and aligns with the button on the PCB
![push botton](/images/IMG_0281.jpg)
4. **Mount the controller board** into the top case, aligning the USB ports with the cutouts
![pcb install](/images/IMG_0283.jpg)
5. **Weld the battery cells** to the PCB, observing correct polarity
6. **Close the lid** and fasten with 4 M3 screws
![complete](/images/IMG_0278.JPG)

> ⚠️ **Safety Warning:** Always observe correct polarity when wiring Li-ion cells. Short circuits can cause fire or injury.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

*If you find this project useful, please ⭐ star the repository — it helps others discover it!*
