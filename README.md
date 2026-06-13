# 🌍 EcoPulse — Carbon Footprint Awareness Platform

> **Challenge 3 — Carbon Footprint Awareness Platform**  
> Design a solution that helps individuals understand, track, and reduce their carbon footprint through simple actions and personalized insights.

---

## 🔥 The Problem

Most people have **zero intuition for carbon emissions**. Numbers like "25 kg CO₂" are meaningless in isolation. They don't connect emotionally, so they don't change behaviour.

> You can't change what you can't feel.

---

## 💡 Our Solution — The Real-World Equivalents Engine

EcoPulse translates invisible CO₂ numbers into **shocking, relatable real-world comparisons** — the moment someone truly *sees* their impact, that's when behaviour changes.

Instead of showing `25 kg CO₂`, EcoPulse shows:

- 📱 **13,500 smartphone full charges**
- 🚗 **207 km driven by a petrol car**
- 🌳 **415 days for one tree to absorb this**
- 🍔 **10 fast-food cheeseburgers**

---

## ✨ Key Features

### 1. Interactive CO₂ Slider
Drag the slider from 0–50 kg and watch every equivalent update in real time. This builds **carbon intuition** — users develop a gut feeling for what their choices actually cost.

### 2. The Aha! Moment
A large, prominent centrepiece that shows the single most shocking equivalent for the selected category. Engineered to stop you mid-scroll and make you think *"wait… really?"*

### 3. Category Filters
Switch between **Trees, Water, Food, Travel, Energy, and Products** to see the same footprint through different lenses. A food-conscious user gets food framing; a frequent flyer gets travel framing — **personalised awareness**.

### 4. Share Card
One click generates a shareable card with your shocking equivalent. Turns private realisation into public conversation — awareness multiplies beyond the app.

### 5. Zero State Handling
At 0 kg, the app celebrates the user and invites exploration — no broken states, no NaN values.

### 6. Conversion Reference Table
Full database of 11 scientifically-sourced conversion factors with citations (EPA, DEFRA, Our World in Data, EEA) — **awareness backed by credibility**.

---

## 🎯 Why Awareness is the Game Changer

| Approach | Problem |
|---|---|
| Just tracking | Data without emotion = forgotten |
| Just offsetting | Guilt without understanding = disengagement |
| Just tips | Generic advice = ignored |
| **Awareness first** | **Emotional connection = lasting behaviour change** |

Awareness is the ignition. Every other feature — tracking, nudges, offsetting — runs on it.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Styling | CSS Custom Properties, Responsive Grid |
| Data | Inline JS database with 11 conversion factors |
| Deployment | Static HTML — zero dependencies, zero build step |

No frameworks. No libraries. No backend. Just a single `index.html` file that works anywhere.

---

## 📊 Conversion Database

| Equivalent | Factor (per 1 kg CO₂e) | Source |
|---|---|---|
| Tree absorption | 16.6 days | European Environment Agency |
| Plastic bottles (500ml) | 33 bottles | Our World in Data |
| Beef production | 0.037 kg | Our World in Data (Poore & Nemecek) |
| Dry rice | 0.25 kg | Our World in Data |
| Cheeseburgers | 0.4 burgers | Various LCA estimates |
| Car driving | 8.3 km | UK DEFRA/BEIS |
| Economy flight | 6.7 km | UK DEFRA/BEIS |
| Smartphone charges | 540 charges | US EPA |
| LED bulb hours | 270 hours | US EPA eGRID |
| HD video streaming | 3.5 hours | IEA |
| Cotton T-shirt | 0.15 shirts | Ellen MacArthur Foundation |

---

## 🚀 Getting Started

### Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/ecopulse-equivalents-engine.git

# Open in browser — no build step needed
open index.html
```

### Or just open the deployed link directly →
[Live Demo](https://yourusername.github.io/ecopulse-equivalents-engine)

---

## 📁 Project Structure

```
ecopulse-equivalents-engine/
│
├── prompt.html          # Complete app — all HTML, CSS, JS in one file
└── README.md           # This file
```

---

## 🎨 Design Decisions

- **Dark theme** — reduces eye strain for long sessions; makes the pink accent pop for maximum emotional impact on the Aha moment
- **Single file** — zero friction to deploy, fork, or contribute
- **No external dependencies** — loads instantly, works offline
- **Responsive grid** — works on mobile, tablet, and desktop without media query overload

---

## 🔮 Future Roadmap

- [ ] AI-powered daily personalised equivalents based on user habits
- [ ] Integration with UPI/payment apps to show carbon cost at checkout
- [ ] Community leaderboard — see how your footprint compares to your city
- [ ] Spotify Wrapped-style annual carbon year in review
- [ ] Browser extension to show carbon labels on e-commerce and food delivery apps

---

## 📄 License

MIT License — free to use, modify, and distribute.
