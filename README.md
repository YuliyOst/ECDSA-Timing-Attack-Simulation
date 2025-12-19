# ECDSA Security Research: Attack Simulations

## Project Overview
The goal of this project is to demonstrate vulnerabilities in ECDSA implementations. We focused on two critical vectors:
1. **Nonce Reuse Attack**: Recovering the private key when the same $k$ is used.
2. **Timing Attack (Side-Channel)**: Extracting the secret key by analyzing time variations.

## Technologies
* **Python 3.x** — core logic.
* **SageMath** — mathematical computations.
* **Matplotlib/NumPy** — statistical analysis (CPA/SPA).

## Key Results 
* Successfully recovered secret key bits with **100% accuracy**.
* Verified **RFC 6979** and constant-time algorithms as effective defenses.

## Authors 
* **Yuliy Ostashkov**
* **Lise Makarenko**
* ![Timing Attack Chart](main/graph.png)
https://drive.google.com/file/d/16PJQEX6-OL2qbFhcmMzi-Z-ZlU0Lw_Fh/view?usp=sharing
