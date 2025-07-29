# 4-bit Carry Look-Ahead Adder (CLA) using Static CMOS Logic

This project presents the design and implementation of a **4-bit Carry Look-Ahead Adder (CLA)** using **transistor-level static CMOS logic**. The adder is optimized to eliminate traditional carry-generate (`Gi`) and carry-propagate (`Pi`) signals, improving speed and power efficiency.

---

##  Objective

- Design a transistor-level 4-bit CLA using static CMOS logic.
- Minimize average power consumption and propagation delay.
- Simplify carry generation using direct input bit usage.
- Compare the performance with traditional CLA methods.

---

##  Block Diagram & Circuit

The project includes:
- Logic gate-level representation of the proposed CLA
- Transistor-level CMOS implementation of individual carry-out bits (C1 to C4)
- Complete CMOS CLA circuit


---

##  Methodology

- Removed conventional Pi/Gi signals and used direct input-based equations.
- Constructed NMOS and PMOS networks using simplified Boolean equations.
- XOR logic used for sum computation remains the same.
- Designed circuits for each carry bit and combined them into a full CLA.

---

##  Results

- **Technology node used**: 90 nm
- **Power consumption**: ~0.5258 µW
- **Propagation Delay**:
  - Rise time: 0.0362 ns
  - Fall time: 0.11788 ns

Transient analysis and timing plots were generated and compared with input signals.

---

##  Conclusion

The simplified CLA design using static CMOS logic resulted in enhanced performance and reduced power consumption. Even though a different technology node was used (90nm vs. 45nm in the reference), the results are promising for low-power VLSI design.

---



