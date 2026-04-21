# ⚡ NMOS & PMOS I–V Characteristics using ngspice

##  Overview

This project demonstrates the simulation of **I–V characteristics of NMOS and PMOS transistors** using ngspice. Both **output and transfer characteristics** are analyzed and plotted.

---

## 🎯 Objectives

* Analyze **Output Characteristics** (Id vs Vds / Vsd)
* Analyze **Transfer Characteristics** (Id vs Vgs / Vsg)
* Understand MOSFET operating regions
* Compare NMOS and PMOS behavior

---

## ⚙️ Circuit Description

### 🔹 NMOS

* Source → Ground
* Gate controls conduction
* Drain voltage swept

### 🔹 PMOS

* Source → Supply
* Works with reversed polarity
* Uses Vsg and Vsd

---

## 📊 Results

### 🔹 NMOS Characteristics

* Output (Id vs Vds)
* Transfer (Id vs Vgs)

![NMOS Characteristics](results/nmos_output_transfer.png)

---

### 🔹 PMOS Characteristics

* Output (Id vs Vsd)
* Transfer (Id vs Vsg)

![PMOS Characteristics](results/pmos_output_transfer.png)

---

## 🧮 Key Equation

[
I_D = \frac{k}{2}(V_{GS} - V_T)^2
]

---

## ⚠️ Constraints

* MOSFET model must be defined
* Threshold voltage:

  * NMOS → positive
  * PMOS → negative
* W/L ratio affects current
* Proper voltage sweep required
* Use `-i(Vds)` / `-i(Vsd)` for correct current

---

## 📈 Expected Behavior

### ✔ NMOS

* No conduction below threshold
* Current increases with Vgs
* Saturation region observed

### ✔ PMOS

* Similar behavior with reversed polarity
* Controlled by Vsg

---

## 🚀 Applications

* CMOS design
* Analog circuits
* Digital switching

---

## 📌 Conclusion

The simulation verifies MOSFET behavior:

* Shows operating regions clearly
* Demonstrates dependence on gate voltage
* Confirms theoretical characteristics

---

## 🧠 Viva Questions

* What is threshold voltage?
* Why does current saturate?
* Difference between NMOS & PMOS?
* Effect of W/L ratio?

---

## 👨‍💻 Author

Amith A Airodagi
