         # FIR Filter Using Vedic Multipliers in Verilog

## 🌟 Project Overview

This project implements a 32-tap Finite Impulse Response (FIR) Filter** in Verilog HDL, utilizing custom-designed Vedic multipliers and ripple carry adders. The design is fully pipelined and suitable for high-performance digital signal processing applications.

The filter leverages a 32-stage delay line using D Flip-Flops. Each delayed input is multiplied with a corresponding coefficient using hierarchical Vedic multipliers (2x2 → 4x4 → 8x8), and accumulated using 4-bit, 8-bit, and 16-bit ripple carry adders.


## 🔧 Key Features

* 🔹 **Hierarchical Vedic Multipliers** (2x2, 4x4, 8x8)
* 🔹 **Custom Ripple Carry Adders** (4-bit, 8-bit, 16-bit)
* 🔹 **Pipelined FIR Filter** with 32 D Flip-Flops as delay elements
* 🔹 Fully modular, reusable Verilog design


## 📊 Applications

* Audio/Video Digital Filters
* FPGA/SoC Signal Processing Units
* Communication Systems


## 🔹 Repository Structure

fir-filter-vedic-verilog/
├── src/                      # RTL Verilog source files
│   ├── fir_filter.v
│   ├── vedic_multiplier_2x2.v
│   ├── vedic_multiplier_4x4.v
│   ├── vedic_multiplier_8x8.v
│   ├── adder_4bit.v
│   ├── adder_8bit.v
│   ├── adder_16bit.v
│   └── d_flipflop.v
│
├── tb/                       # Testbenches
│   ├── tb_fir_filter.v
│   ├── tb_vedic_multiplier.v
│   └── tb_adders.v
│
├── docs/                     # Documentation and diagrams
│   ├── block_diagram.png
│   ├── timing_diagram.png
│   └── architecture.md
│
├── waveform/                 # Simulation waveforms
│   ├── fir_output.vcd
│   └── fir_waveform.png
│
├── .gitignore                # Ignored temp/sim files
|
└── README.md                 # Project overview and usage guide



## 📉 Block Diagram


<img width="1040" height="128" alt="image" src="https://github.com/user-attachments/assets/5d26f14f-6551-4b86-98ec-f641dc93d4ab" />




## ▶️ How to Run

1. Open the design in your preferred Verilog simulator (e.g., ModelSim, Icarus Verilog, Vivado).
2. Compile the source files in `src/` and the testbench files in `tb/`.
3. Run simulation and observe waveforms using GTKWave or ModelSim.
4. Modify FIR coefficients as needed in `fir_filter.v`.



## ✨ Author

**Sakinala Sreehitha**

*https://www.linkedin.com/in/sreehitha-sakinala-68a157220
      
*https://github.com/SreehithaSakinala


## Results
  <img width="1137" height="478" alt="image" src="https://github.com/user-attachments/assets/368baf9d-ad3e-426a-b325-dda6c50cdd27" />

