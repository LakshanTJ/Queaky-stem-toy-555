# 🎵 Queaky STEM Toy using 555 Timer 

A beginner-friendly **embedded systems project** that generates a squeaky sound using the **555 Timer IC in astable mode**.
This project demonstrates the complete workflow from **circuit design →  PCB design using KiCad**.

---

## 🧰 Components Used

* IC 555 Timer ×1
* 9V Battery ×1
* 9V Battery Connector ×1
* 5–12V Buzzer ×1
* 1kΩ Resistor ×1
* 10kΩ Resistor ×1
* 1nF Ceramic Capacitor ×1
* 100µF Electrolytic Capacitor ×1
* Breadboard / PCB

---

## ⚙️ How It Works

The circuit uses the **555 Timer in astable mode** to generate a continuous square wave signal.

* The resistor-capacitor network controls oscillation frequency
* Output is generated at **Pin 3** of the 555 timer
* The buzzer converts electrical pulses into sound
* The capacitor ensures stable operation

---

## 🔄 Working Principle

1. Capacitor charges through resistors
2. Voltage reaches threshold level
3. 555 timer switches state
4. Capacitor discharges
5. Cycle repeats continuously

This rapid switching produces an audible tone.

---

## 📊 Frequency Formula

The output frequency is determined by:

f ≈ 1.44 / ((R1 + 2R2) × C)

Where:

* R1 = 1kΩ
* R2 = 10kΩ
* C = 1nF
---

## 🛠️ PCB Design Workflow (KiCad)

This project was designed using **KiCad**, an industry-relevant open-source EDA tool.

### Steps followed:

1. Created schematic in KiCad
2. Assigned footprints to components
3. Switched to PCB editor
4. Placed components strategically
5. Routed tracks with proper connections
6. Performed Design Rule Check (DRC)
7. Generated Gerber files for manufacturing

---

## 🧠 Skills Demonstrated

* 555 Timer (Astable Mode)
* Analog electronics fundamentals
* Breadboard prototyping & debugging
* KiCad schematic design
* PCB layout and routing
* Design Rule Check (DRC) validation
* Hardware development workflow

---

## 🎯 Why This Project Matters

This project demonstrates practical skills required for **Embedded Systems / IoT internships**:

* Hands-on circuit design and testing
* Experience with PCB design tools (KiCad)
* Understanding of hardware-level behavior
* Ability to convert theory into real-world implementation

---

## 🚀 Future Improvements

* Add potentiometer for adjustable frequency
* Replace buzzer with speaker for tone variation
* Develop enclosure for real-world usage

---

## 📂 KiCad Files

All design files are available in the `kicad-files/` directory:

* Schematic file (.kicad_sch)
* PCB layout file (.kicad_pcb)

