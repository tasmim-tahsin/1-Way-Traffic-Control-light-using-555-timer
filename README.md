# 1-Way-Traffic-Control-light-using-555-timer

## Overview
This project is a simple **1-way traffic light controller** using a **555 timer** and a **4017 decade counter IC**. The circuit sequentially lights up **red, yellow, and green LEDs**, simulating a traffic light system. This project is useful for understanding the working principles of **timing circuits** and **sequential control using digital ICs**.

## Features
- Uses a **555 timer** as a clock pulse generator.
- Employs a **4017 decade counter** for sequential LED switching.
- Implements **red, yellow, and green LEDs** to mimic real-world traffic lights.
- Adjustable timing using **resistors and capacitors**.

## Circuit Diagram
![Image](https://github.com/user-attachments/assets/c1540b37-ae12-417a-9166-21cb0504e4f3)


## Components Used
- **555 Timer IC** (Clock pulse generator)
- **4017 Decade Counter IC** (Sequential output)
- **Red, Yellow, Green LEDs**
- **Resistors & Capacitors** (Timing adjustments)
- **Power Supply (5V or 9V)**
- **Breadboard & Connecting Wires**

## How It Works
```markdown
1. The **555 timer** is configured in **astable mode** to generate clock pulses.
2. The **4017 IC** receives the pulses and activates its output pins in a sequence.
3. Each output pin corresponds to an **LED**, lighting them up one by one.
4. The sequence repeats continuously, simulating a traffic light operation.
```

## Installation & Usage
```markdown
1. Assemble the circuit on a **breadboard** following the schematic.
2. Connect a **5V or 9V power supply**.
3. Observe the LEDs turning on in sequence, resembling a **1-way traffic signal**.
```

## Future Improvements
- Adding a **pedestrian crossing system**.
- Implementing **IR sensors** for real-time traffic control.
- Expanding the system to handle **multi-way intersections**.

## License
```markdown
This project is open-source. Feel free to modify and enhance it!
```

---

### Contribute
```markdown
If you find any improvements or want to enhance this project, feel free to fork and submit a **pull request**!
```

