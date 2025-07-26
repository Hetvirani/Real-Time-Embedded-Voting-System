# 🗳️ Real-Time Embedded Voting System using ATmega2560

🔧 Developed in **Proteus 8 Professional** using **Embedded C**  
🎯 Designed for classroom elections with secure and user-friendly operation

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
- [🙋‍♂️ Author Info](#-author-info)
- [🔐 License](#-license)
- [🏷️ Tags](#-tags)

---

## 📌 Project Overview

This project simulates a **real-time voting machine** using **ATmega2560**, built in **Proteus 8**. The voting system is built for **Head Girl** and **Head Boy** elections.

📟 Interfaces:
- 4x3 Keypad  
- 16x2 LCD Display  
- LED Bar Graphs (for live voting stats)

🎮 Modes:
- 🧑 Voter Mode (secured with roll number)
- 🧑‍🏫 Admin Mode (results and stats)

---

## 🎯 Features

✨ Real-time simulation  
🔐 Roll number-based secure voting  
📟 LCD shows step-by-step guidance  
📊 LED bar graphs visualize live vote count  
❌ Prevents duplicate voting  
🔒 Admin-only result access

---

## 🧰 Tools & Technologies

| Tool               | Usage                        |
|--------------------|------------------------------|
| Proteus 8 Pro      | Circuit design & simulation  |
| WinAVR / AVR-GCC   | Embedded C programming       |
| Git & GitHub       | Version control              |
| Markdown           | For documentation            |

---

## 📁 File Structure

```
Real-Time-Embedded-Voting-System/
├── src/
│   └── Real_Time_Embedded_Voting_System.PDSPRJ   # Proteus project file
├── docs/
│   └── circuit.png                                # Circuit snapshot
└── README.md
```

---

## 🔧 Setup & Installation

### 📌 Requirements

- ✅ [Proteus 8 Professional](https://www.labcenter.com/)
- ✅ [WinAVR Compiler](http://winavr.sourceforge.net/)
- ✅ Git & GitHub account

---

### 🧑‍💻 Clone the Repo

```bash
git clone https://github.com/<your-username>/Real-Time-Embedded-Voting-System.git
cd Real-Time-Embedded-Voting-System
```

---

## 🚀 How to Run the Project

### 🛠️ Step-by-Step Instructions

1. **Open Proteus**  
   Navigate to: `src/Real_Time_Embedded_Voting_System.PDSPRJ`  
   Double-click to open in Proteus

2. **Start Simulation**  
   Press the **"Run"** button in Proteus  
   Use the **keypad** to input roll number and vote

3. **Voting Flow**  
   Roll No → Vote for Head Girl (1 or 2) → Vote for Head Boy (1 or 2)

4. **Admin View**  
   Press **Admin Button** → View results on LCD and LED bar graph

---

## 📈 Output Walkthrough

### 👨‍🎓 Voter Mode

```
WELCOME !!
ID:12
headgirl voting
ren | sriya   ->  1 | 2
Vote: 2

headboy voting
om  | het     ->  1 | 2
Vote: 1
```

✅ Vote stored  
❌ Invalid ID or duplicate voting is denied

---

### 👩‍🏫 Admin Mode

Displays results:

```
ren: 3     sriya: 5
om: 4      het: 4
```

💡 **LED Bar Graphs**  
🟩 PORTB: Head Girl votes  
🟥 PORTD: Head Boy votes  

---

## 🧠 Circuit Design

### 🔌 Components Used

- ✅ ATmega2560 Microcontroller  
- ✅ 16x2 LCD (PORTC)  
- ✅ 4x3 Keypad (PORTA)  
- ✅ 2 Push Buttons (Voter/Admin Mode)  
- ✅ LED Bar Graphs (PORTB & PORTD)

---

## 🙋‍♂️ Author Info

👤 **Het Virani**  
📧 [hetvirani1305@gmail.com](mailto:hetvirani1305@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/het-virani) | [GitHub](https://github.com/hetvirani)

---

## 🔐 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## 🏷️ Tags

`#ATmega2560` `#Proteus` `#EmbeddedC` `#VotingMachine` `#AVR` `#EngineeringProject` `#LCD` `#Keypad`
