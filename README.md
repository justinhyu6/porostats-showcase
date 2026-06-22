# Porostats — In Progress

I couldn't find a League of Legends stats website that had everything I wanted, so I made a personal website that pulls everything into one place. Clean, readable, and designed around what players actually need.

---

## What makes this different

- **ML winrate model** — derives in-game features from match data and trains a model using PyTorch. Instead of relying on intution, you can measure impact with actual metrics.
- **VOD reviewer** — a replay tool that overlays your winrate graph directly onto your game timeline,.

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
- [ ] Cloud deployment (in progress)
- [ ] Public release — pending Riot Games production API key (~6 months)
- [ ] Desktop app (potentially)

---

## Note on availability

Public access requires a Riot Games production API key, which is currently under review. Once approved, the site will be deployed and publicly accessible. 

---

## Local setup

*Instructions coming soon*
