# 💧 Qatratak (قطرتك)

> don’t let it hit zero.

Qatratak is a small interactive web project that turns water usage into something you can actually *see*.

it’s basically a game:

* water = your health
* wasting it = damage
* saving it = recovery

nothing complicated, just a different way to make the idea stick.

---

## 🧠 the idea

we hear “save water” all the time, but it doesn’t really hit.

so this project flips it into something visual:

* a dripping tap slowly drains your water bar
* you stop it → it recovers
* ignore it → everything dries out

simple loop, real meaning.
### Part 2: ML Water Savings Calculator
- Predicts daily water savings based on habits
- 97% accuracy model
- 20+ real-world test cases
- Personalized recommendations

---

## 🤖 ML Model

### Performance
| Metric | Value |
|--------|-------|
| Model Accuracy | 97% (R² score) |
| Training Data | 60 realistic UAE household scenarios |
| Test Cases | 20 real-world scenarios |
| Prediction Range | 43L - 96.4L per day |

### Features (9 Inputs)
1. Kitchen taps closed (0-3)
2. Bathroom taps closed (0-2)
3. Outdoor taps closed (0-1)
4. Shower duration (minutes)
5. Plant watering instances (0-4)
6. Washing machine cycles (0-3)
7. Car washes (0-1)
8. Toilet type (regular/lowflow)
9. Lawn irrigation method (drip/sprinkler/none)

### Test Results
- **Eco-conscious households:** 85-96L savings
- **Medium usage:** 65-85L savings
- **High usage:** 43-65L savings

---

## 🏗️ Tech Stack

**Frontend:**
- Next.js + TypeScript
- Tailwind CSS
- React

**Backend:**
- Python (scikit-learn)
  
**ML:**
- Linear Regression model
- LabelEncoder for categorical features
- joblib for model serialization

---

## 📊 Real-World Impact

Based on 20 test scenarios:
- **7 eco-conscious households** can save 85-96L daily
- **5 medium-usage households** can save 65-85L daily
- **8 high-usage households** can save 43-65L daily
- **Average potential savings:** 72.9L per day

---

## 🎮 How It Works

### User Journey
1. Fill in water usage habits
2. ML model processes input
3. Gets personalized savings prediction
4. Sees impact visualization
5. Gets conservation tips
---

## 🎮 what’s in it

* interactive water “health bar”
* tap simulation (drip = damage)
* recovery actions (turn it off, get water back)
* game over state (dry environment)
* real-life facts built into the experience
* floating / anti-gravity style UI

---

## 🌍 real-world side

not just visuals — it’s based on actual habits:

* leaking taps waste ~15–20L/day
* long showers use way more water than expected
* leaving taps open adds up fast

the idea is to connect those habits to something you can *feel*.

---

## ⚙️ stack

* Next.js
* TypeScript
* Tailwind CSS

---

## 🤝 contributing

open to ideas, improvements, and experiments.

if you’ve got something cool:

* open an issue
* or just send a PR

doesn’t have to be perfect.

---

## 📜 license

All rights reserved. This project and its contents are the exclusive property of the author. No part of this project may be copied, modified, distributed, or used in any form without explicit written permission.

---

## 🧩 future stuff

* smoother animations
* more interactions / maybe full mini-game
* better mobile feel
* more real-world scenarios

---

## 👤

built by a student trying to make something a bit more interesting than a normal “save water” poster.

---

> your drop. your responsibility.
