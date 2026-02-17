# Automatic Light Control (LDR + Arduino)

This project automatically turns a light ON when it is dark and turns it OFF when there is enough light. It uses an LDR connected to an Arduino board.

---

## Components Used

- Arduino UNO board
- LDR
- 10kΩ resistor (for voltage divider)
- LED
- Jumper wires
- Breadboard

---

## How It Works

1. The LDR senses the surrounding light intensity.
2. The Arduino reads the analog value from the LDR.
3. If the light level is low (dark), the output pin turns ON the light.
4. If the light level is high (bright), the light remains OFF.

---

## Pin Configuration

| Component | Arduino Pin |
|-----------|------------|
| LDR       | A5         |
| Light/LED | 2          |

---

