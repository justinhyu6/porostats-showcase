# Porostats

I couldn't find a League of Legends stats website that had everything I wanted, so I made a personal website that pulls everything into one place. I desgined it to be clean, readable, and around what players actually need.

<br/>

<p align="center">
  
  <img width="681" height="616" alt="Screenshot 2026-06-26 at 10 12 15 PM" src="https://github.com/user-attachments/assets/4226040c-d583-430a-b258-ef91bbb79e1c" />
<img width="574" height="654" alt="Screenshot 2026-06-26 at 10 12 43 PM" src="https://github.com/user-attachments/assets/4304ba87-4558-4b7d-9015-f4adeaac3d26" />
<img width="571" height="724" alt="Screenshot 2026-06-26 at 10 13 15 PM" src="https://github.com/user-attachments/assets/e24047ec-07ff-41f6-b0e5-0d80ca3b09ce" />

</p>

---

## What makes this different from other stat websites

- **ML winrate model** — derives in-game features from match data and trains a model using PyTorch. Instead of relying on intuition, you can measure in-game events with actual metrics.
- **VOD reviewer** — a replay tool that overlays your winrate graph directly onto your game timeline.

---

## Tech stack

| Layer | Tech |
|---|---|
| Frontend | React, Tailwind CSS |
| Backend | FastAPI, Python |
| ML | PyTorch |
| Data | Riot Games API |

---

## Status

Currently running locally. In active development.

- [x] Core stat website with Riot Games API integration
- [x] Player and champion info display
- [x] ML winrate model
- [x] VOD reviewer with winrate graph overlay
- [ ] Cloud deployment and cleaning up UI elements (in progress)
- [ ] Public release — pending Riot Games production API key (~6 months)
- [ ] Desktop app (potentially)

---

## Note on availability

Public access requires a Riot Games production API key, which is currently under review. Once approved, the site will be deployed and publicly accessible.

---

## Local setup

*Instructions coming soon*
