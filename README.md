# -Smart-Home-Communication-System-Simulation-Using-Dataset-NRZ-BPSK-Hamming-7-4-
Smart Home Communication System (NRZ + BPSK + Hamming(7,4))

This project demonstrates a Smart Home Communication System that uses digital modulation and error correction to simulate reliable data transfer between IoT devices. It combines Non-Return-to-Zero (NRZ) encoding, Binary Phase Shift Keying (BPSK) modulation, and Hamming(7,4) error correction coding to transmit 4-bit data from smart devices through a noisy communication channel.

🚀 Project Overview

Each smart home device (e.g., temperature sensor, light controller, motion detector) sends a 4-bit binary message representing its data or status. The system performs the following steps:

Encoding:

Input 4-bit data is encoded using the Hamming(7,4) code, which adds 3 parity bits for single-bit error correction.

Encoding ensures the receiver can detect and correct transmission errors caused by noise.

Modulation (NRZ + BPSK):

Encoded bits are converted into NRZ format.

BPSK modulation is applied by mapping binary bits to signal phases (0° and 180°).

Transmission Through Noisy Channel:

The signal passes through an Additive White Gaussian Noise (AWGN) channel to simulate real-world noise conditions.

The user can adjust the noise level using a slider or dataset-based simulation.

Demodulation & Decoding:

The received signal is demodulated using BPSK detection and decoded using Hamming logic to recover original bits.

System compares transmitted and received data, showing success or detected errors.

🧩 Features

Hamming(7,4) error correction with single-bit recovery

Adjustable noise simulation (AWGN channel)

NRZ and BPSK visualization using Matplotlib

Supports dataset input for multiple IoT devices

Auto-demo mode for low and high noise comparisons

📊 Technologies Used

Python 3

NumPy – mathematical operations

Matplotlib – waveform plotting

Pandas – dataset management

Tkinter (optional) – GUI for simulation

🧠 Learning Outcomes

Understand digital communication concepts

Observe error correction effectiveness

Visualize modulation under noise

Model IoT reliability in smart home networks
