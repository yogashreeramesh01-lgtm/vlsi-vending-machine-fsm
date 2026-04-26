# vlsi-vending-machine-fsm
FSM design of coin-operated vending machine in Verilog
🧾 Coin-Operated Newspaper Vending Machine (FSM - VLSI)

📌 Project Overview

This project implements a Finite State Machine (FSM) for a coin-operated newspaper vending machine using Verilog HDL.

💰 Specifications

- Cost: 15 cents
- Inputs:
  - Nickel (5 cents)
  - Dime (10 cents)
- No change is returned

🔁 Valid Sequences

- N + N + N
- N + D
- D + N
- D + D (no change)

⚙️ Design Type

- Mealy Machine

🧠 States

- S0 → 0 cents
- S5 → 5 cents
- S10 → 10 cents

🧪 Simulation

Testbench verifies all valid combinations.

📄 Project Report

See the attached PDF file in this repository.

👩‍💻 Tools Used

- Verilog HDL
- ModelSim / Vivado

📌 Author

Kanaka Yogashree
