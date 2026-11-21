# AEGIS — A second set of eyes, even when families can't be there

**Team NeuroX · The Corporate Glitch '26 (Builders Hub) · Healthcare: AI-powered patient monitoring & emergency response**

🔗 **Live demo:** https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/

AEGIS is a connected care companion: a wearable band + patient app + caregiver/clinician dashboard that monitors vitals, understands context, reminds medication, and escalates to the right person at the right time.

## Try it (no install)
Open the live demo and press **▶ Auto Demo** (~100 s), or use the scenario buttons at the bottom:
Normal · Walking (high HR, expected) · Noisy sensor · Tachycardia · Low SpO₂ · Fall · Medicine due.

## What the prototype shows
- Simulated smart band (HR, SpO₂, temperature, motion, signal quality, SOS, vibration alerts)
- Patient app: risk ring, vitals, medicine reminders and adherence, "Are you OK?" confirmation
- Caregiver/clinician dashboard: live charts, editable thresholds, audit log
- Closed-loop response: Detect → Verify → Notify → Acknowledge → Document
- Context-aware triage: no false alarm while walking or when the sensor signal is poor
- Escalation chain: caregiver → backup caregiver → clinician, with simulated voice calls

## Tech
Single self-contained `index.html` (HTML/CSS/JavaScript, no dependencies). Planned hardware path: ESP32 + MAX30102 + MPU6050 → BLE → mobile gateway → backend → risk engine → response hub.

## Disclaimer
Prototype with **simulated** sensor data. Not a medical device, not diagnostic, and not a substitute for emergency services.
