# NEEV — North-East Emergency & Evacuation Grid

**Live App:** [https://neev-site-ashen.vercel.app](https://neev-sitepwars-6mj3nykcy-prompt-wars11.vercel.app/)

## Problem Statement
Several regions across North East India face recurring challenges related to floods, landslides, and natural disasters. During emergencies, standard disaster portals often fail because 4G cellular networks collapse, phone batteries drop below 15%, highway washouts (NH-10, NH-6) isolate communities, and dialect barriers delay emergency assistance.

## Solution Overview
**NEEV** is an offline-first, low-bandwidth disaster response and evacuation coordination platform built specifically for North East India's terrain and connectivity constraints:
- **2G / Low-Battery Survival Mode:** Instantly compresses the interface into a 14 KB locally cached emergency terminal that works on weak 2G or zero signal while conserving battery.
- **1-Tap Multilingual SOS (SMS + Offline Rescue QR):** Generates instant emergency alerts in **Assamese, Khasi, Bengali, Hindi, and English** with critical vulnerability tags (*Needs Boat, Insulin/Medical, Infant, Elderly*), compressing GPS and needs into a 45-character SMS string and an offline-scannable QR rescue card while routing live to the **Responder Triage Feed**.
- **Hyper-Local Chokepoint & Relief Hub Telemetry:** Tracks live river danger levels (e.g., Brahmaputra at Pandu), highway blockages, and real-time shelter capacities (*24x7 Power/Charging, Boat Extraction, Beds*) with 1-tap spot reservation and spoken audio survival guides.
