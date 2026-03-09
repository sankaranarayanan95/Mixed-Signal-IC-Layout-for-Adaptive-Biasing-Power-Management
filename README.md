# ⚡ Mixed-Signal IC Layout for Adaptive Biasing & Power Management

A compact, reusable mixed-signal analog IP designed for **low-power applications** using the GPDK 90nm CMOS process.  
This project integrates essential analog building blocks such as **Bandgap Reference, OTAs, Error Amplifiers, Comparators, and Flash ADC** with digital feedback.

---

## 📂 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Architecture](#architecture)
- [Performance](#performance)
- [Layouts](#layouts)
- [Results](#results)
- [projectposter](#projectposter)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Overview
This project demonstrates the design and layout of a **mixed-signal IC** optimized for low-power operation.  
It highlights **adaptive biasing techniques** and **block-level modularity** for reusability in VLSI design.

---

## ✨ Key Features
- 🔋 Low-power operation (IQ: 15–30 µW)
- 📐 Layout reusability & modularity
- ⚡ Integrated Bandgap Reference
- 🎛 Signal Conditioning Front-End
- 📊 Flash ADC with Digital Feedback
- ✅ Post-layout verified performance

---

## 🏛 Architecture
![Architecture Diagram](images/schematic.jpeg)

---

## 📊 Performance
| Parameter              | Value                  |
|------------------------|------------------------|
| Supply Voltage         | 1.8 V                 |
| Load Current Range     | 0–10 mA               |
| Quiescent Current (IQ) | 15–30 µW              |
| Transient Overshoot    | < 50 mV               |
| Line Regulation        | < 1%                  |
| Load Regulation        | < 2%                  |
| ADC Resolution         | 3-bit (8:1 Flash ADC) |
| Efficiency @ 10 mA     | 85–88%                |
| Operating Temperature  | -5°C to 90°C (sim.)   |


---

## 🖼 Layouts
### Full Chip Layout
![IC Layout](images/Toplayout.jpeg)

---

## 📈 Results
### Line Regulation (FF, -20 °C)
![Line Regulation Graph](images/line_regulation_plot.png)

### Load Regulation (TT, 1.8 V, 27 °C)
![Load Regulation Graph](images/load_regulation_plot.png)

---

## 📰 Project Poster

The following poster summarizes the **Mixed-Signal IC Layout for Adaptive Biasing and Power Management in Low-Power Applications**.  
It highlights the **overview, key features, performance metrics, architecture, layout techniques, and results** of the design.

![Project Poster](images/poster.jpeg)

### 🔑 Poster Highlights
- **Overview**: Compact mixed-signal analog IP using GPDK 90nm CMOS process.  
- **Key Features**: Bandgap Reference, OTAs, Error Amplifiers, Comparators, Flash ADC with digital feedback.  
- **Performance**: Verified post-layout with <1% line regulation, <2% load regulation, and 85–88% efficiency at 10 mA.  
- **Layout Techniques**: Symmetry, Matching, Guard Rings, Shielded Routing, Common Centroid, LVS/DRC compliance.  
- **Results**: Graphs for Bandgap vs Temperature, Transient Response, and Load Regulation.  

---

📌 *Tip*: Keep the poster image inside `docs/images/posters/` and reference it with a relative path so GitHub can render it directly.


## 🤝 Contributing
Contributions are welcome!  
Fork the repo, make improvements, and submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.  
See the LICENSE file for details.
