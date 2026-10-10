# ATM Simulation System (Java)

A simple console-based ATM simulation program written in Java. It allows a user to log in with a PIN and perform basic banking operations such as checking balance, depositing money, withdrawing money, viewing transaction history, and changing the PIN.

---

## 📋 Table of Contents

- [Features](#-features)
- [Requirements](#-requirements)
- [How to Run](#-how-to-run)
- [Default Credentials](#-default-credentials)
- [How to Use](#-how-to-use)
- [Menu Options](#-menu-options)
- [Program Logic](#-program-logic)
- [Project Structure](#-project-structure)
- [Limitations](#-limitations)
- [Possible Improvements](#-possible-improvements)

---

## ✨ Features

- **PIN Authentication** — 3 login attempts before the account is locked.
- **Check Balance** — View the current account balance.
- **Deposit Money** — Add money to the account.
- **Withdraw Money** — Withdraw money (with insufficient-balance check).
- **Transaction History** — View a list of all past deposits and withdrawals.
- **Change PIN** — Change the ATM PIN after verifying the current one.
- **Input Validation** — Rejects zero or negative amounts, invalid PINs, etc.
- **Transaction Recording** — Stores up to 100 transactions using parallel arrays.

---

## 🛠 Requirements

- **Java JDK 8 or higher** installed.
- Any IDE (IntelliJ IDEA, Eclipse, NetBeans, VS Code) **or** a terminal with `javac` and `java` commands.

---

## ▶ How to Run

### Option 1: Using the Command Line

1. Save the file as `ATMSimulationSystem.java` inside a folder named `MiniProjects`.
2. Open a terminal in the parent directory.
3. Compile:

   ```bash
   javac MiniProjects/ATMSimulationSystem.java
