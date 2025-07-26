# 🗳️ Real-Time Embedded Voting System using ATmega2560

🔧 Developed in **Proteus 8 Professional** using **Embedded C**  
🎯 Targeted for classroom elections using a secure and user-friendly interface  

---

## 📚 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Features](#-features)
- [🧰 Tools & Technologies](#-tools--technologies)
- [📁 File Structure](#-file-structure)
- [🔧 Setup & Installation](#-setup--installation)
- [🚀 How to Run the Project](#-how-to-run-the-project)
- [📈 Output Walkthrough](#-output-walkthrough)
- [🧠 Circuit Design](#-circuit-design)
- [🙋‍♂️ Author Info](#️-author-info)
- [🔐 License](#-license)

---

## 📌 Project Overview

This project is a **real-time voting machine** simulation using **ATmega2560**. It simulates a voting process for **Head Girl** and **Head Boy** using:

- 🧮 4x3 keypad input  
- 📟 16x2 LCD display  
- 🔆 LED bar graph to show results  

### It includes:
- 👨‍🎓 **Voter Mode** (secured with roll number)
- 👨‍🏫 **Admin Mode** (displays total results in real-time)

---

## 🎯 Features

- ✨ Simple & Real-Time voting system  
- 🔐 Secured via roll number-based validation  
- 📟 LCD displays candidate info and voting steps  
- 📊 LED bar graph shows voting percentage  
- 🚫 Duplicate votes are prevented  
- 🧑‍💼 Admin-only result access  

---

## 🧰 Tools & Technologies

| 🛠 Tool            | 🧩 Purpose                          |
|-------------------|-------------------------------------|
| Proteus 8 Pro     | Circuit design & simulation         |
| WinAVR / AVR-GCC  | Programming in Embedded C           |
| Git & GitHub      | Version control & collaboration     |
| Markdown          | For this documentation              |

---

## 📁 File Structure

Real-Time-Embedded-Voting-System/
├── src/
│ ├── Real_Time_Embedded_Voting_System.PDSPRJ # Proteus project file
├── docs/
│ └── circuit.png # Circuit snapshot
├── README.md # This file

---

## 🔧 Setup & Installation

### ✅ Requirements Before You Begin

- [✔️] [Proteus 8 Professional](https://www.labcenter.com/)
- [✔️] [WinAVR Compiler](http://winavr.sourceforge.net/)
- [✔️] GitHub account

---

### 🧑‍💻 Clone the Repo

```bash
git clone https://github.com/<your-username>/Real-Time-Embedded-Voting-System.git
cd Real-Time-Embedded-Voting-System
🚀 How to Run the Project
🛠️ Step-by-Step Instructions
1. Open Proteus
Navigate to: src/Real_Time_Embedded_Voting_System.PDSPRJ

Double-click to open the project in Proteus

2. Start Simulation
Press the "Run" button in Proteus

Use the Keypad to input roll number and vote

3. Voting Flow
Input Roll No → Vote for Head Girl (1 or 2) → Vote for Head Boy (1 or 2)

4. Admin View
Press the Admin Button → View results and percentages on LCD and LED bars

📈 Output Walkthrough
👨‍🎓 Voter Mode
makefile
Copy
Edit
WELCOME !!
ID:12
headgirl voting
ren|sriya||1|2
Vote: 2

headboy voting
om|het||1|2
Vote: 1
✅ Vote stored, roll marked as voted
❌ Invalid ID or duplicate voting is denied

👩‍🏫 Admin Mode
Displays results:
ren: 3     sriya: 5
om: 4      het: 4

💡 LED Bar Graphs:
🟩 Green LEDs (PORTB): Head Girl votes

🟥 Red LEDs (PORTD): Head Boy votes

🧠 Circuit Design
🔌 Components Used
✅ ATmega2560 Microcontroller

✅ 16x2 LCD (PORTC)

✅ 4x3 Keypad (PORTA)

✅ 2 Push Buttons (for Voter/Admin Mode)

✅ LED Bar Graphs (PORTB & PORTD)

🙋‍♂️ Author Info
👤 Het Virani
📧 hetvirani1305@gmail.com
🔗 LinkedIn | GitHub

🔐 License
This project is licensed under the MIT License – see the LICENSE file for details.

🏷️ Tags
#ATmega2560 #Proteus #EmbeddedC #VotingMachine #AVR #EngineeringProject #LCD #Keypad
