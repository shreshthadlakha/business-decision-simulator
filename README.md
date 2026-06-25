# Business Decision Simulator
**Trial project for Digital Heroes** · Built by [Your Full Name]

> Describe your business decision. Five AI agents — a skeptic, investor, competitor, analyst, and early adopter — each react, raise concerns, and predict what happens. You get a consensus verdict, risk level, and action plan in seconds.

**Inspired by [MiroFish](https://github.com/666ghj/MiroFish)** — a 65k⭐ open-source swarm intelligence engine that runs thousands of agents to predict real-world outcomes. This tool distils that concept into a free, browser-based experience using Claude.

---

## 🚀 Deploy in 5 Minutes (Free)

### Step 1 — Add your name & email
Open `index.html` and replace:
- `[Your Full Name]` → your actual name  
- `[your@email.com]` → your actual email

These appear twice — in the form footer and the result footer.

### Step 2 — Push to GitHub
```bash
git init
git add .
git commit -m "Business Decision Simulator"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/decision-simulator.git
git push -u origin main
```

### Step 3 — Deploy on Vercel (Free)
1. [vercel.com](https://vercel.com) → New Project → Import repo
2. Framework: **Other**
3. Click **Deploy**
4. Live in ~30 seconds — no card, no upgrade

---

## ✅ Submission Checklist
- [ ] Live Vercel URL working
- [ ] Public GitHub repo
- [ ] Your name + email visible on page
- [ ] "Built for Digital Heroes" button → https://digitalheroesco.com
- [ ] Simulation produces a real AI-generated report
- [ ] Added to portfolio
- [ ] ₹0 / $0 spent

---

## The 5 Agents

| Agent | Role | What They Represent |
|---|---|---|
| 😤 Skeptical Customer | Hard-to-convince buyer | Loyalty and trust at risk |
| 💰 Potential Investor | VC evaluating viability | ROI, scalability, market share |
| 🎯 Direct Competitor | Rival brand | Counter-strategy, market reaction |
| 📊 Industry Analyst | Market expert | Trends, data, precedent |
| 🚀 Early Adopter | Most enthusiastic customer | Evangelism or abandonment |

---

## What the Simulation Returns

Each agent gives:
- **Reaction** — 2-3 sentences in their authentic voice
- **Biggest Concern** — their sharpest criticism
- **Their Prediction** — what they think will happen

Synthesis layer:
- **Consensus Report** — balanced assessment from all perspectives
- **Verdict** — Go For It / Proceed With Caution / Rethink This
- **Risk Level** — Low / Medium / High / Very High
- **3 Recommended Actions** — specific, tailored to the decision

---

## Why This Is Relevant to Digital Heroes

Digital Heroes' clients — DTC founders, funded brands, SaaS startups — make high-stakes decisions constantly: pricing changes, platform migrations, product launches, market pivots. This tool shows what a $50K consultant would normally surface, in seconds, for free. It's a direct lead-generation asset for Digital Heroes.

---

## Design Notes
- **Dark cosmic purple theme** — distinct from other tools in this set
- **Subtle grid background** — nods to the "simulation environment" of MiroFish
- **Terminal-style loading animation** — agent spawning sequence with blinking cursor
- **5 agent cards** with distinct colour accents (red / green / amber / blue / violet)
- **Claude API returns structured JSON** — reliable, clean rendering
- Responsive — works on mobile and desktop

---

## Stack
- Plain HTML / CSS / Vanilla JS (zero dependencies)
- Anthropic Claude API (`claude-sonnet-4-6`)
- Vercel static deployment

---

## The MiroFish Connection

[MiroFish](https://github.com/666ghj/MiroFish) (65k+ GitHub stars) runs a full Python + Vue + Docker stack with Zep Cloud memory graphs and hundreds of agents per simulation. This tool takes the same core idea — feed it a scenario, let multiple intelligent agents react, get a prediction — and makes it:

- Free (no Zep, no Python backend, no Docker)
- Instant (single Claude API call)
- Deployable on Vercel as a static site
- Useful for any business decision, not just social simulations

---

Built for Digital Heroes · https://digitalheroesco.com
