# Reinforcement Learning for Offer Type  
*A Proof-of-Concept in Personalized Credit Card Marketing*  
Developed by [HOSTA Analytics](https://hosta-analytics.com)

---

## Overview

This repository contains a working simulation of how **Reinforcement Learning (RL)** can improve credit card offer targeting by adapting to customer behavior over time. Instead of relying on static rules or one-off model scores, this RL agent learns which offers perform best for different behavioral profiles and adjusts its strategy with every interaction.

We apply **Q-learning** to a simulated customer environment, demonstrating how financial institutions can use RL to build smarter, more adaptive marketing systems.

---

## Contents

| File | Description |
|------|-------------|
| `Reinforcement Learning for Offer Type.ipynb` | Main Jupyter notebook containing simulation logic, Q-learning implementation, and performance comparison |
| `Offer Targeting with Reinforcement Learning.docx` | Accompanying white paper that explains the business case, modeling framework, and key takeaways |
| `requirements.txt` | Python dependencies (see below for pip install instructions) |
| `README.md` | This file |

---

## Key Concepts

- **Environment**: Simulated population of 100,000 credit card customers
- **Actions**: Five marketing strategies (Balance Transfer, APR Discount, CLI, Cash Back, No Offer)
- **State**: Encoded behavioral snapshot (utilization, spend score, tenure, revolver status, activity)
- **Reward**: Simulated net value generated if the offer is accepted
- **RL Algorithm**: Tabular Q-learning

---

## Why This Matters

Most credit card marketing systems are static; they guess once and move on. This simulation shows how RL can:
- Adapt to customer behavior over time
- Optimize long-term outcomes, not just one-off predictions
- Double or triple marketing ROI compared to traditional rule-based strategies

---
