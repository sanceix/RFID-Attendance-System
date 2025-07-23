📚 RFID-Based IoT Attendance System

📌 Project Overview
This project presents a low-cost, efficient **RFID-based IoT Attendance System** using the **ESP32 microcontroller**. The solution automates traditional attendance processes by allowing students or employees to scan RFID cards, instantly logging their presence into a Google Sheet via Wi-Fi.
It ensures accurate attendance records, eliminates proxy marking, and significantly reduces time and human error associated with manual systems.

🎯 Objectives
✅ Automate attendance tracking using RFID and IoT.
✅ Eliminate false or proxy entries.
✅ Display real-time confirmation using an LCD.
✅ Store attendance data securely in Google Sheets.
✅ Minimize manual workload for administrators and educators.

🛠️ Tech Stack
Hardware:
  - ESP32 Devkit V1
  - RFID RC522 Module
  - RFID Tags/Cards
  - LCD 20x4 I2C Display
  - Breadboard & Jumper Wires
  - USB Type-C Cable

Software & Tools:
  - Arduino IDE
  - Google Sheets + Apps Script
  - Draw.io (for system diagrams)
  - MS Word (for documentation)
  - Fritzing (for schematic & circuit diagrams)

🧩 System Architecture
- RFID card is scanned → UID read by RC522 module.
- ESP32 processes the data.
- Attendance is displayed on LCD.
- UID and timestamp are sent via Wi-Fi and logged in Google Sheets.
- Only two entries per user/day: Time In & Time Out.

🔁 Development Phases
1. Phase 1: Setup ESP32 and Serial Monitor output.
2. Phase 2: Connect and test RFID RC522.
3. Phase 3: Interface LCD and Google Sheets.
4. Phase 4: Full system integration and real-time testing.

✅ Testing & Results

| Test | Objective | Result |
|------|-----------|--------|
| RFID Tag Detection | Validate UID recognition | ✅ Successful |
| Attendance Logging | Confirm Google Sheets entry | ✅ Logged correctly |
| Time In/Out Control | Ensure 2 scans per day per user | ✅ Accurate |
| Monitor Output | Verify on-screen confirmation | ❌ Monitor display issue (future fix needed) |

📈 Future Improvements
- 🔊 Add buzzer/LED feedback for better UX.
- 📱 Integrate mobile app for student/parent access.
- 🔐 Combine with biometric features for security.
- 📊 Generate reports & analysis using AI.
- ⚡ Battery-based portable version.
- 📡 Link with other smart campus systems (labs, library, etc).



