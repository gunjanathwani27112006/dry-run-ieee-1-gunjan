# GuardianSlider: Smart Safety Keychain & App

## 1. Ideation & Research (AI Assisted)
- **Problem:** Apps are hard to use during panic struggles.
- **Solution:** A physical slider keychain that triggers SOS without touching the phone.
- **AI Tools:** Used ChatGPT for market research and hardware selection (ESP32).

## 2. Business Model
- **Target:** Women's safety, elderly care, and solo travelers.
- **Revenue:** One-time keychain sale + Monthly subscription for 24/7 monitoring and cloud evidence storage.

## 3. System Architecture
[Keychain Hardware] --(BLE)--> [Mobile App] --(API)--> [Emergency Services/Contacts]
- **Slider Mechanism:** Designed to require intentional movement to prevent accidental false alarms.

## 4. Technical Implementation
- **Frontend:** UI Prototype developed with HTML/CSS (located in `/frontend`).
- **Backend:** Node.js (`server.js`) handles SOS signals and GPS routing.
- **Hardware:** ESP32-C3 for low-power Bluetooth connectivity.

## 5. Hardware Simulation
The slider is simulated as a digital input (GPIO) that triggers an interrupt when pushed. This sends an immediate SOS packet via Bluetooth to the paired device.

## 6. Contributions
- [Gunjan, Taniya, Yogita, Khushi]: Project Ideation, UI Prototyping, and Research Documentation.
