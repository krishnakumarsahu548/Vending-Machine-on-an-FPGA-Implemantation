# Vending-Machine-on-an-FPGA-Implemantation
A digital Vending Machine designed and implemented on an FPGA board using Verilog/SystemVerilog. The system handles product selection, coin input, change return, and display logic.
 Vending Machine on FPGA

This project implements a **Vending Machine** on an FPGA board using **Verilog/SystemVerilog**. The machine handles product selection, coin insertion, balance checking, and change return — all designed for real-time hardware execution on FPGA.

---

## 🛠️ Features

- Product selection via input switches/buttons
- Accepts coins of fixed denominations (e.g., ₹1, ₹2, ₹5)
- Displays current balance
- Dispenses item if sufficient balance
- Returns change if excess amount is inserted
- Display interface using 7-segment display or LEDs

---

## ⚙️ Technologies Used

- **Language:** Verilog / SystemVerilog
- **Platform:** Xilinx Vivado
- **Target Board:** (e.g., Boolean FPGA board / Basys 3 / any other)

---

## 🧠 Working Principle

1. User selects a product using input buttons
2. Inserts coins
3. Machine compares inserted value with product cost
4. If enough coins → product dispensed + change returned
5. If not enough → shows balance, waits for more coins

---

## 📟 State Machine Design

The vending machine is designed using a **Finite State Machine (FSM)** approach with states like:
- `IDLE`
- `WAIT_FOR_COIN`
- `CHECK_BALANCE`
- `DISPENSE_ITEM`
- `RETURN_CHANGE`
- `RESET`

---


##RTL Circuit
<img width="1920" height="1013" alt="image" src="https://github.com/user-attachments/assets/1eba2bee-37f4-4ad2-ada8-b6481194e68d" />
<img width="1920" height="882" alt="image" src="https://github.com/user-attachments/assets/79a10cfb-d348-4fe9-bf19-10a1cdd884de" />

