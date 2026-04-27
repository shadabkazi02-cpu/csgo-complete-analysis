# 🎯 CS:GO Complete Analysis

[![Kaggle](https://img.shields.io/badge/Kaggle-Data-blue?logo=kaggle)](https://www.kaggle.com/datasets/mateusdmachado/csgo-professional-matches)
[![Python](https://img.shields.io/badge/Python-3.8+-green?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📊 Project Overview

A comprehensive analysis of Counter-Strike: Global Offensive (CS:GO) combining **professional tournament data** and **competitive matchmaking data**. This project uncovers patterns in map popularity, team performance, side advantage (CT vs T), and weapon effectiveness.

### Datasets Used
- **Professional Matches**: 45,773 matches with team stats and map results
- **Professional Players**: 383,317 player performance records
- **Matchmaking Damage**: 5.9M damage events from ESEA matches
- **Matchmaking Kills**: 1.56M kill events

---

## 📈 Key Findings

### 1. **Most Popular Maps in Pro Play**
| Rank | Map | Matches |
|------|-----|---------|
| 1 | Mirage | 9,021 |
| 2 | Inferno | 8,956 |
| 3 | Dust2 | 7,834 |
| 4 | Overpass | 5,623 |
| 5 | Nuke | 5,201 |

**Insight**: Mirage, Inferno, and Dust2 dominate the competitive map pool - teams should prioritize these for practice.

### 2. **Top Performing Teams**
- **Liquid** leads with 600+ map wins
- **Astralis** and **NaVi** consistently in top 5
- North American and European orgs dominate rankings

### 3. **CT vs T Side Advantage**
- CT side wins 51.1% of rounds (594,820 rounds)
- T side wins 48.9% of rounds (569,089 rounds)
- Slight defensive advantage confirms game balance but minor adjustments could achieve 50/50

### 4. **Most Damaging Weapons**
| Weapon | Total HP Damage |
|--------|-----------------|
| AK-47 | Highest |
| M4A4 | 2nd Highest |
| AWP | 3rd Highest |
| M4A1-S | 4th Highest |
| USP-S | Top Pistol |

**Insight**: Rifle mastery (AK-47/M4) is the single highest-impact skill for players.

---

## 🛠️ Technologies Used

### Core Libraries
| Library | Version | Purpose |
|---------|---------|---------|
| **Python** | 3.8+ | Core programming language |
| **Pandas** | 1.3+ | Data manipulation & analysis |
| **NumPy** | 1.21+ | Numerical operations |
| **Matplotlib** | 3.4+ | Data visualization |

### Key Python Packages
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
