# BetterBreakout Board

The **BetterBreakout Board** is a prototyping and breakout solution designed to simplify wiring, power distribution, and I/O access for microcontroller-based projects. It is intended for hobby, educational, and experimental use.

---

## 📐 Mechanical Drawings

The following image shows the overall dimensions and mounting hole locations for both the **BetterBreakout** and **BetterBreakout MINI** boards.

![BetterBreakout Mechanical Drawings](Amazon_Pictures1_75.jpg)

**Notes:**
- All dimensions are in millimeters
- Mounting holes are Ø3 mm
- Corner radius: R2.54 mm
- MINI version maintains the same layout philosophy at a reduced footprint

---

## 🔌 Wiring Suggestions

The diagram below illustrates recommended wiring practices and explains the onboard power and ground distribution.

![BetterBreakout Wiring Suggestions](Wiring_Suggestions.png)

### VIN Pads (**IMPORTANT**)
- Connected directly to the VIN terminal block through the PCB
- Intended for input voltages **greater than 5V**
- Use an external voltage regulator to step down to 5V if required
- Regulated 5V can then be fed into the 5V pads to power the microcontroller

### 5V Pads
- Automatically connected to the microcontroller’s VIN / 5V pins
- Can be used to distribute regulated 5V across the board

### 3.3V Pads
- Automatically connected to the microcontroller’s 3.3V pins
- Suitable for sensors and peripherals requiring 3.3V logic

### Ground Pads
- Connected directly to the microcontroller GND pins
- Multiple ground points provided for convenient wiring

### Other IO Terminal Blocks / JST Connectors
- **Not connected by default**
- Intended for user-defined wiring depending on project needs

> Wiring is identical between the standard BetterBreakout and the MINI version unless otherwise noted.

---

## 📦 CAD Models

CAD models are available for enclosure design, integration, and modification:

👉 https://cad.onshape.com/documents/641fb402b50249ed35852e66/w/ed6f31275fe70e4d50fd9af3/e/aa7b3e3c1d21e0f3346701bb

---

## ❤️ Support This Project

If you’d like to support this project and others, consider supporting on Patreon:

👉 https://www.patreon.com/MichaelRechtin

---

## ⚠️ Disclaimer

This PCB is sold **as-is** and is intended for project, hobby, and experimental use only.  
All use of this PCB is undertaken at the user’s own risk.

The seller shall not be held liable for any direct, indirect, incidental, or consequential damages, including but not limited to personal injury, property damage, equipment failure, or financial loss resulting from the use, misuse, or modification of this PCB.