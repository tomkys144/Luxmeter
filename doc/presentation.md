---
marp: true
theme: gaia
---

# Luxmetr

Tomáš Kysela

---

# Hardware

- LDR
- Nucleo G491RE
- Alfanumerický LCD
![height:8cm](assets/ldr.png) ![height:8cm](assets/lcd.png)

---

# Software

- ADC pak přepočet
- Curve fitting
- `lux = 48.824 * voltage ^ (-1.974)`

![height:8cm](assets/lin_reg)
