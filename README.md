# Erdem Aslan

**Embedded & TinyML Developer**

🔌 I build firmware for ESP32 hardware in C (ESP-IDF) and train small, quantized models meant to run on it

🧠 Current focus: a DIY handheld multi-tool on the ESP32-C6, plus Turkish OCR and voice-command models sized for microcontrollers

🌐 I also ship web and mobile apps in TypeScript, Kotlin and React Native

🕹️ Space Station 13 (SS13) player, currently learning the /tg/station codebase

---

## About

Junior developer working where software meets hardware. I like projects I can hold in my hand: wiring a board, writing the firmware, and finding out on the real device what actually works. My READMEs state what has been measured or validated and what has not.

Before that I built apps: a real-estate marketplace for a company in Dubai, an Android health pre-assessment app, and two browser-based projects. I started with Arduino and basic electronics in the national "Kod Adı 2023" project.

---

## Projects

**[makeshift-flipper](https://github.com/ErdemWilkinson/makeshift-flipper)** — *working prototype*
DIY Flipper Zero-style handheld on a single ESP32-C6 (ESP-IDF/C). The display, buttons, joystick-driven menu, and the on-chip Wi-Fi and BLE tools (scan, access point, passive monitor, channel map, BLE radar) run on the real device. RFID and IR drivers are written but not yet validated on assembled hardware. CI builds the firmware and runs host-side logic tests on every push.

**[turkish-ocr-tinyml](https://github.com/ErdemWilkinson/turkish-ocr-tinyml)** — *in progress*
Training pipeline for a compact, full-int8 CNN-CTC model that reads a single line of printed Turkish text. Covers synthetic and real-photo dataset generation, a source-independent evaluation split, and int8 TFLite export. The model does not meet its accuracy targets yet; the README reports the measured numbers.

**[turkish-asr-whisper](https://github.com/ErdemWilkinson/turkish-asr-whisper)** — *in progress*
Training pipeline for an offline Turkish voice-command recognizer intended to work with whispered speech. The data contract, recording protocol and speaker-independent split are in place; the command dataset has not been recorded yet. Includes a separate character-level CTC research baseline trained on Mozilla Common Voice.

**[Frp_deneysel](https://github.com/ErdemWilkinson/Frp_deneysel)** — *in progress*
Single-player D&D RPG with an AI Game Master and a tactical grid (React + Vite, Node.js/Express, Gemini API). Falls back to rule-based template text when no API key is available.

**[evosim](https://github.com/ErdemWilkinson/evosim)**
Browser-based artificial-life simulation (TypeScript / Vite) where organisms evolve, reproduce and interact with no fixed evolutionary tree. Includes a lineage view, world events and seed-based planet generation.

**[Shaman](https://github.com/ErdemWilkinson/Shaman)**
AI-assisted Android health pre-assessment app (Kotlin, Jetpack Compose, Firebase, Claude API) that turns described symptoms into ranked possible conditions, in Turkish.

---

## Experience

**Intern / Contractor — Software Developer**, OME Marketing (Dubai) — *2026*
- Built "Onaylı Emlak," a real-estate marketplace app using Expo (React Native), Firebase, and iyzico payment integration

---

## Skills

**Embedded & ML**
- C (ESP-IDF) • ESP32 • Arduino & circuit design
- Python • TensorFlow / TFLite • int8 quantization

**Software**
- TypeScript/JavaScript • React • Node.js/Express • React Native (Expo)
- Kotlin (Jetpack Compose) • Firebase
- C# • .NET • Microsoft SQL Server • Java • C++

**Professional**
- Fast learner • Team collaboration • Documentation

---

## Education

**Karadeniz Technical University**
Associate Degree in Computer Programming • Trabzon, Turkey

---

## Languages

- Turkish (Native)
- English (Professional Working Proficiency)

---

## Connect

Open to internships, junior roles and collaborations. The best way to reach me is through GitHub.
