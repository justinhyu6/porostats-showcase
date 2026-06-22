# Porostats

I couldn't find a League of Legends stats website that had everything I wanted, so I made a personal website that pulls everything into one place. I desgined it to be clean, readable, and around what players actually need.

<p align="center">
  <img src="https://github.com/user-attachments/assets/7550edc1-83d5-490f-9af8-7c75b3130676" width="80%"/>
  <img src="https://github.com/user-attachments/assets/e9dba1a8-a082-4d6a-b725-49acd0124f40" width="80%"/>
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
