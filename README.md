This project implements a complete digital communication chain on FPGA for Software Defined Radio (SDR) systems.
The design includes digital modulation, demodulation, error correction, and bit error rate (BER) analysis — all built and verified in Verilog using Xilinx Vivado and deployed on a Zynq-7000 FPGA.

The goal is to demonstrate how real-time baseband signal processing can be implemented directly in hardware, forming a core component of modern SDR architectures.
⚙️ Features

Random bit generation and serial data transmission

Digital modulation and demodulation (BPSK, QPSK, 8-PSK, 16-QAM)

Error correction using Hamming encoding/decoding

Bit error rate (BER) measurement

RTL design in Verilog, verified through simulation and FPGA testing

Power, timing, and resource utilization analysis using Vivado reports

🧠 Future Scope

Add channel noise modeling and BER vs. SNR characterization

Integrate with RF front-end (PlutoSDR or USRP) for over-the-air testing

Implement adaptive modulation and Viterbi decoding

Explore design migration to ASIC flow using Synopsys tools
