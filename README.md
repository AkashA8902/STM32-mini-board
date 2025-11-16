# STM32 Mini Board (UFQFPN48) – Hardware + Firmware Project
Custom STM32-based mini development board designed in Altium Designer.

This project includes the full hardware schematic, power stage, clock circuitry, user interfaces, expansion headers, and firmware support for GPIO, LEDs, buttons, and sensor interfacing.

---

## 📌 Features

### 🔹 **Microcontroller**
- STM32 MCU (UFQFPN48 package)
- 48 MHz system clock
- USB device-capable pins (D+ / D–)

### 🔹 **Power System**
- USB 5V input (Micro-USB)
- Resettable PTC fuse (1812L050PR)
- 3.3V LDO regulator (SOT-223)
- Bulk + decoupling capacitors for stable operation

### 🔹 **Clocking**
- 8 MHz crystal (system clock)
- 32.768 kHz crystal (RTC oscillator)
- Proper load caps (22 pF / 12 pF)

### 🔹 **User Interface**
- USER button
- RESET button
- RGB status LEDs + current-limit resistors

### 🔹 **Expansion**
- 40-pin 2.54 mm header exposing:
  - All GPIO pins
  - 3V3, GND, VBAT
  - SWD programming pins

### 🔹 **Sensor Interface**
- DHT22 temperature & humidity sensor (1-wire GPIO)

---

## 📁 Repository Structure

