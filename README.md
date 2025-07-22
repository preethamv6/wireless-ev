# ⚡ Wireless Electric Vehicle Charging using Inductive Coupling

This project demonstrates a working prototype of **Wireless EV Charging** using **inductive power transfer (IPT)**. The system charges a battery wirelessly through **magnetic resonance coupling** between two coils: one in the transmitter (charging station) and one in the receiver (vehicle module).

> Built as part of Project-Based Learning at **RV College of Engineering**, Bengaluru (2024)

---

## 🎯 Objectives

- Implement a wireless charging system using resonant inductive coupling.
- Design a compact, low-loss coil arrangement for efficient power transfer.
- Eliminate physical plug-in requirements in electric vehicle charging systems.
- Enhance safety and durability through non-contact energy transmission.

---

## ⚙️ System Architecture

| Module          | Description                                                           |
|-----------------|------------------------------------------------------------------------|
| Transmitter     | Generates high-frequency AC power and sends it via a flat spiral coil |
| Receiver        | Receives induced power wirelessly through magnetic field interaction  |
| Control Circuit | MOSFET-based driver to modulate the transmitter coil signal           |
| Load            | Rechargeable Li-ion Battery / LED to verify power delivery            |

---

## 📐 Videoa




[Wireless EV Charging ](vid.mp4)


---

## 🧪 Working Principle

The transmitter coil produces a **high-frequency alternating magnetic field** using an oscillating driver circuit. When the receiver coil (placed near the transmitter) comes into range, the changing magnetic field induces an **EMF** via **Faraday’s Law**. This is then rectified and filtered to power a DC load (battery or LED).

- **Power Transfer**: ~4V–5V at 50–100mA in prototype
- **Range**: Optimized for ~2–4 cm gap
- **Efficiency**: Improves with coil alignment and shielding

---

## 🔩 Components Used

- 2 × Copper Coil (Transmitter & Receiver)
- MOSFET driver circuit (IRF540N)
- 555 Timer IC or Oscillator Module (optional)
- Diode (1N4007), Capacitor (filtering)
- Rechargeable Battery / LED load
- Acrylic/Plastic frame to hold coils
- Breadboard, jumpers, 12V DC input

---

## ✅ Advantages

- 🔌 No mechanical connector wear or shock risk
- ⚡ Improved user convenience and automation potential
- 🔋 Safe for damp environments, weather-proof system
- 🚘 Future scalable for EV charging pads, buses, smart parking

---

## 📄 Project Report


[Full Report (PDF)](rprt.pdf)




---

## 🚀 Future Scope

- Increase output power for higher-capacity EV batteries
- Integrate over-voltage and thermal protection circuitry
- Implement alignment detection using proximity sensors
- Add BLE for charge status monitoring in mobile app

---

## 👨‍💻 Contributors
 
- Sneha Pandey  
- Preetham V  
- Ritvik Unnikrishnan
- Sonia Girish Deshpande

---

## 📬 Contact

- Email: preethamv.et23@rvce.edu.in  
- GitHub: [github.com/preethamv6](https://github.com/preethamv6)

---

> “Charging the future — no plugs, no wires, just power.” ⚡🚗
