# H.A.L.O. Kiosk

An interactive prototype of **H.A.L.O.**, a live wait screen for the emergency room waiting room, designed as a concept for the **IU Health Bloomington Hospital** emergency department. A four-sided kiosk tower stands in the middle of the room, and patients can scan a QR code to see the same information on their phone. Both screens share one live wait list.

> Student project. Not affiliated with or endorsed by IU Health.

**Live demo:** https://wasiangrime.github.io/HALO-Kiosk/

![The H.A.L.O. kiosk tower](screenshots/kiosk-tower.png)

## What it does

| Feature | What happens |
|---|---|
| Live wait list | The clock runs in real time and the list updates every 10–18 seconds. A note says what changed, and tapping a ticket shows why its wait moved. |
| Triage levels | Each ticket shows its triage level (2 Emergent to 5 Non-urgent). Patients are seen by level first, then by arrival time. The screen shows only the ticket number and level, never a name or the reason for the visit. Level 1 patients go straight back and never appear. |
| Front desk check-in | A staff panel on the page: after the triage nurse assigns a level, one tap prints the ticket, texts the link and places the patient in the right spot in line. Everyone behind them sees why their wait changed. |
| Tap your phone | Next to the QR code is a glowing pad. Hold your phone near it, like tap to pay, and the H.A.L.O. page opens on your phone. No app needed. (In a real kiosk this is an NFC tag; in the demo, click the pad.) |
| Call for help | The button grows into a flashing alarm that covers the map, the tower's light ring turns red, and a countdown shows when the nurse arrives. Patients keep their place in line. Works from the phone too. |
| Detailed map | Tapping a place opens a floor plan with a moving route from "You are here," hours, walking time and a full map key. |
| Patient education video | A 30-second captioned stick-figure spot with three safety tips: clean hands, ask before you eat or drink, and tell staff if you feel worse. |
| Phone page | Shows the patient's own ticket (A118), triage level, people ahead and wait time, all synced to the kiosk. |
| 3D model | Under the front desk panel: the printable tower model, rebuilt from our PrusaSlicer file. Drag to turn it, zoom in and out, or press **Start rotating**. Runs on a small built-in WebGL viewer, so it needs no internet. The original print file is in [`model/`](model/). |

<p>
  <img src="screenshots/3d-model.png" alt="3D model of the hexagonal kiosk tower" width="32%">
  <img src="screenshots/front-desk.png" alt="Front desk check-in panel with triage levels 1 to 5" width="32%">
  <img src="screenshots/tap-your-phone.png" alt="Scan the code or hold your phone on the tap pad" width="62%">
</p>
<p>
  <img src="screenshots/call-for-help.png" alt="Call for help alarm" width="32%">
  <img src="screenshots/detailed-map.png" alt="Detailed map with directions and map key" width="32%">
  <img src="screenshots/phone.png" alt="Phone page with the page-ready notification" width="28%">
</p>

## Concept write-up

- [2-page summary (PDF)](docs/HALO-concept-system-2-pages.pdf)
- [4-page concept system with diagrams and evaluation (PDF)](docs/HALO-concept-system-4-pages.pdf)

## Running it

Everything is in one file, `index.html`, with no build step and no server needed. Open it in any browser, or use the live demo link above.

All tickets, times and places are examples. This prototype is not connected to a real hospital system and is not affiliated with or endorsed by IU Health.

*[TEAM NAMES] · ER Wait-Time Concept*
