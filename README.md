# Chunren Lian

**Full-Stack Engineer · React · Next.js · TypeScript · Node.js · Python · Applied AI**

I build products end-to-end and hold them to production standards — numbers computed in tested code, AI constrained to narrate those numbers, performance enforced by CI, not promised in a README.

Computer Science graduate from Alma College · Based in Southern California · Open to Software Engineer & Full-Stack roles

[LinkedIn](https://www.linkedin.com/in/chunren-lian-631856365/) · [Portfolio](https://my-portfolio-acme307.vercel.app/) 

---

## 🚀 Shipped Projects

| Project | What it does | Stack | Status |
| ------- | ------------ | ----- | ------ |
| [Smart Money Decoder](https://github.com/LianCr/smart-money-decoder) | Paste a Polymarket wallet → finds its largest political bet, reconstructs the news around entry, and issues an AI verdict card — then backtests that verdict against how markets actually resolved. [Video demo](https://youtu.be/egFu1kzgWrs) | Python · FastAPI · React · Claude · Polymarket APIs · Tavily | ✅ [Live](https://smart-money-decoder.onrender.com/) |
| [DealLens](https://github.com/LianCr/deallens) | Enter a dealer quote for a real vehicle → see where it lands in the market distribution, 24-month price history with pinned events, and a grounded AI negotiation brief. Verdicts render without JavaScript. | Next.js · TypeScript · GraphQL · D3 · Claude API · Vitest · Playwright | ✅ [Live](https://deallens-xi.vercel.app/) |

---

## 🧠 Technical Stack

```text
Frontend        React · Next.js · TypeScript · Tailwind CSS · D3.js
Backend         Node.js · Express · FastAPI · REST APIs · GraphQL
Data & AI       Python · LLM APIs · Structured Outputs · Backtesting Pipelines
Testing & CI    Vitest · Playwright · pytest · Lighthouse CI · GitHub Actions
Deployment      Vercel · Render
```

---

## 📌 What Makes These Projects Different

* **Backtested, not vibes-tested** — Smart Money Decoder replays its own verdicts at T-7 and T-1 before each market resolved and scores them against real settlement outcomes, with a difficulty metric so a near-settled call isn't mistaken for a brilliant one.
* **Anti-fabrication enforced in code, not prompts** — outputs that tamper with a verdict, invent a news catalyst, or compute dates the data never provided are rejected before rendering.
* **Math decides; AI narrates** — every price, percentile, and verdict is computed server-side in zero-dependency pure functions; the LLM only writes the story around numbers it's handed.
* **Performance is a CI gate** — DealLens scores Lighthouse 100 across all pages, backed by 89 unit/contract tests and 56 E2E runs (including a dedicated no-JS browser project), and a budget regression fails the build.
* **Honest about limits** — true wallet win rates aren't computable from public APIs, so the backtest measures the decoder's accuracy, not the wallet's P&L — labeled, not hidden.

---

## 📈 Currently Building Toward

* [ ] **Smart Money Decoder — production gateway**: migrating the LLM gateway to AWS Bedrock for provider-managed auth, rate limiting, and cost control
* [ ] **Smart Money Decoder — wider coverage**: expanding the backtest beyond politics markets and growing the multi-wallet sample for statistically stronger accuracy numbers
* [ ] **Polymarket iOS (React Native)**: porting the prediction-market experience to a native iOS app — extending the same data pipeline from web to mobile
* [ ] **Real-time monitoring**: from "paste a wallet" to alerts when tracked smart-money wallets open new positions

---

## ⚙️ Engineering Principles

* Build the smallest complete product loop
* Keep business logic outside UI components
* Prefer explicit data contracts over hidden assumptions
* Design failure states before adding polish
