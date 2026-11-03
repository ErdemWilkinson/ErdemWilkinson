# Erdem Aslan

Embedded and TinyML developer. I write ESP32 firmware in C (ESP-IDF) and train small int8 models that fit on microcontrollers. I also build web and mobile apps.

I started with Arduino in the national "Kod Adı 2023" project. These days I'm working on a Turkish OCR model, a person detector for search-and-rescue drones and a handheld multi-tool on the ESP32-C6. My READMEs say what has been measured and what hasn't.

## Main projects

**[makeshift-flipper](https://github.com/ErdemWilkinson/makeshift-flipper)**
A DIY Flipper Zero-style handheld on a single ESP32-C6. The menu and the Wi-Fi and BLE tools run on the device. RFID and IR aren't tested on hardware yet.

**[InviolusOCR](https://github.com/ErdemWilkinson/InviolusOCR)** · [Hugging Face](https://huggingface.co/inviolus/InviolusOCR)
Reads one line of printed Turkish text. 598 KB as int8, and it reads 77.3% of held-out lines exactly (46.5% on printed-document lines, 56.2% on real scene text). There is also a 171 KB version.

**[VoxHOD](https://github.com/ErdemWilkinson/VoxHOD)** · [Hugging Face](https://huggingface.co/inviolus/VoxHOD)
Finds people in drone images, 197 KB as int8 for the ESP32-S3. It finds 83.9% of the people in the HERIDAL test set. The non-commercial branch [VoxHOD-NC](https://github.com/ErdemWilkinson/VoxHOD-NC) is also trained on Turkish drone footage by Ferhat Tatık ([@ferhattatik_dronoloji](https://www.instagram.com/ferhattatik_dronoloji/)). On that footage it finds 52.2% of people, up from 32.9%.

## Other projects

- [turkish-asr-whisper](https://github.com/ErdemWilkinson/turkish-asr-whisper): pipeline for offline Turkish voice commands, whispered speech included. The dataset isn't recorded yet.
- [deneysel_teknik_destek](https://github.com/ErdemWilkinson/deneysel_teknik_destek): a USB support terminal for municipal IT. An ESP32-P4 tells the PC it's plugged in, and the technician opens a repair terminal where an AI agent can only call whitelisted tools and asks before changing anything.
- [Açık Masa](https://github.com/ErdemWilkinson/Frp_deneysel): an online D&D 5e table for a DM and a player (React, Node.js). Finished.
- [evosim](https://github.com/ErdemWilkinson/evosim): an evolution simulation you can [play in the browser](https://erdemwilkinson.github.io/evosim/).
- [Shaman](https://github.com/ErdemWilkinson/Shaman): Android app that ranks possible conditions from symptoms. My graduation project.
- [beamer-pc2](https://github.com/ErdemWilkinson/beamer-pc2): my fork of [Beamer](https://github.com/kalkman-code/beamer) that sends files and apps to the other PC.

## Experience

**OME Marketing (Dubai)**, intern / contractor, 2026
Built "Onaylı Emlak", a real-estate app (Expo, Firebase, iyzico).

## Skills

- **Embedded and ML:** C (ESP-IDF), ESP32, Arduino, Python, TensorFlow / TFLite, int8 quantization
- **Software:** TypeScript, React, Node.js, React Native (Expo), PostgreSQL (Supabase), Kotlin (Jetpack Compose), Firebase

## Education

Karadeniz Technical University, Associate Degree in Computer Programming, Trabzon

Turkish (native), English (professional). Outside of code I play Space Station 13.

**Licenses:** code is MIT. Model weights keep the terms of their training data: VoxHOD is CC BY 4.0, VoxHOD-NC is CC BY-NC 4.0 and InviolusOCR is CC BY-NC-SA 4.0 (see each MODEL_LICENSE.md).

I'm open to internships, junior roles, freelance work and collaborations. The easiest way to reach me is here on GitHub.
