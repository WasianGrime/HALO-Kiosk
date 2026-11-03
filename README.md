# H.A.L.O. Kiosk

An interactive prototype of **H.A.L.O.**, a live wait screen for the emergency room waiting room. A four-sided kiosk tower stands in the middle of the room, and patients can scan a QR code to see the same information on their phone. Both screens share one live wait list.

**Live demo:** https://wasiangrime.github.io/HALO-Kiosk/

![The H.A.L.O. kiosk tower](screenshots/kiosk-tower.png)

## What it does

| Feature | What happens |
|---|---|
| Live wait list | The clock runs in real time and the list updates every 10–18 seconds. A note says what changed, and tapping a ticket shows why its wait moved. |
| Call for help | The button grows into a flashing alarm that covers the map, the tower's light ring turns red, and a countdown shows when the nurse arrives. Patients keep their place in line. Works from the phone too. |
| Detailed map | Tapping a place opens a floor plan with a moving route from "You are here," plus hours and walking time. |
| Patient education video | A 30-second captioned stick-figure spot with three safety tips: clean hands, ask before you eat or drink, and tell staff if you feel worse. |
| Phone page | Shows the patient's own ticket (A118), people ahead and wait time, all synced to the kiosk. |

<p>
  <img src="screenshots/call-for-help.png" alt="Call for help alarm" width="32%">
  <img src="screenshots/detailed-map.png" alt="Detailed map with directions" width="32%">
  <img src="screenshots/phone.png" alt="Phone page" width="28%">
</p>

## Concept write-up

- [2-page summary (PDF)](docs/HALO-concept-system-2-pages.pdf)
- [4-page concept system with diagrams and evaluation (PDF)](docs/HALO-concept-system-4-pages.pdf)

## Running it

Everything is in one file, `index.html`, with no build step and no server needed. Open it in any browser, or use the live demo link above.

All tickets, times and places are examples. This prototype is not connected to a real hospital system.

*[TEAM NAMES] · ER Wait-Time Concept*
