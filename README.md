# AC-Light-Dimmer-and-Fan-Speed-Regulator
AC light dimmer and fan speed regulator using TRIAC-DIAC phase angle control for efficient AC power regulation.

# AC Light Dimmer & Fan Speed Regulator

An AC power control circuit using TRIAC-DIAC phase angle control to regulate the brightness of incandescent lamps and the speed of AC fans.

---

## Project Overview

The AC Light Dimmer and Fan Speed Regulator is a power electronics project designed to control the power delivered to AC loads using phase angle control.
The circuit uses a TRIAC as the main switching device and a DIAC to trigger the TRIAC at different firing angles. By adjusting the potentiometer, the firing angle changes, allowing smooth control of lamp brightness or fan speed while improving energy efficiency.

---

## Features

- Smooth brightness control
- Variable fan speed regulation
- TRIAC-based AC power control
- DIAC triggering circuit
- Compact and low-cost design
- Suitable for household AC loads

---

## Components Used

- TRIAC (BT136 / BT139)
- DIAC (DB3)
- Potentiometer
- Capacitor
- Resistors
- AC Bulb / AC Fan
- PCB / Breadboard
- AC Power Supply

---

## Working Principle

1. AC mains voltage is supplied to the circuit.
2. The capacitor charges through the potentiometer.
3. When the capacitor voltage reaches the DIAC breakover voltage, the DIAC conducts.
4. The TRIAC receives a gate pulse and turns ON.
5. The TRIAC remains ON until the AC current crosses zero.
6. Adjusting the potentiometer changes the firing angle, controlling the RMS voltage applied to the load.
7. As a result, the lamp brightness or fan speed changes smoothly.

---

## Project Images

<img width="600" height="600" alt="WhatsApp Image 2026-07-19 at 12 59 38 AM" src="https://github.com/user-attachments/assets/04d05ff1-047a-4cf5-b8d8-4d92b3d52196" />



## Circuit Diagram

<img width="680" height="550" alt="image" src="https://github.com/user-attachments/assets/43b42d3d-97b6-4cd4-b8d3-5b25158a6f64" />


---

## 🎥 Demonstration

Watch the complete project demonstration here:

https://youtube.com/shorts/_J8vx7e92Ys?feature=share

---

## Applications

- Home lighting control
- Ceiling fan speed control
- Decorative lighting
- Laboratory demonstrations
- Energy-saving applications

---

## Skills Demonstrated

- Power Electronics
- TRIAC Switching
- DIAC Triggering
- AC Phase Angle Control
- Analog Electronics
- PCB Assembly
- Circuit Testing
- Hardware Debugging

---

## Future Improvements

- ESP32-based digital dimmer
- Zero-cross detection
- Remote control using Wi-Fi
- Mobile application interface
- IoT-based home automation

---

## Author

Tanaya Karwande

Electronics & Telecommunication Engineering
