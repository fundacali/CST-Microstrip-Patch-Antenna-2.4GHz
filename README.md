# CST-Microstrip-Patch-Antenna-2.4GHz

This project is a simulation of a Microstrip Patch Antenna using **CST Studio Suite**. 
The antenna is designed to work at **2.4 GHz** frequency.

# Detailed 2.4 GHz Microstrip Patch Antenna Design and Simulation

This repository contains the design and simulation files for a **Microstrip Patch Antenna** operating at the **2.4 GHz** ISM band. The project was modeled and analyzed using **CST Studio Suite**.



##  Design Specifications
The antenna is built with the following parameters as seen in the CST Parameter List:

* **Substrate Material:** FR-4 (Lossy)
* **Substrate Height (SH):** 1.5 mm
* **Substrate Dimensions:** 59 mm (SL) x 76 mm (SW)
* **Patch Material:** Copper (Annealed)
* **Metal Thickness (Mt):** 0.035 mm
* **Feed Technique:** 50 Ohm Inset Feed for impedance matching

##  My Simulation Results
Based on the transient solver results, the antenna performs as follows:

* **Resonance Frequency:** Exactly **2.38 GHz**, which is perfectly aligned with the 2.4 GHz ISM band requirements.
* **S11 (Return Loss):** Achieved a minimum value of approximately **-16.7 dB** at 2.38 GHz, indicating more than 98% power transmission efficiency.
* **Bandwidth:** The antenna shows a clear bandwidth where S11 < -10 dB between approximately 2.34 GHz and 2.43 GHz.




## 📺 Credits
This project was implemented by following the educational tutorial by **Tensorbundle** on YouTube.
