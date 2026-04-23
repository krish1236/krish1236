<h1 align="center">Krishna</h1>
<p align="center">
  <strong>Solo founder building <a href="https://runforge.sh">RunForge</a> — deploy agents, not infrastructure.</strong>
</p>
<p align="center">
  <a href="https://runforge.sh">runforge.sh</a> · <a href="https://adshield.dev">dashboard</a> ·  <a href="https://app.runforge.sh">dashboard</a> . <a href="https://www.kircle.app">kircle.app</a>
</p>

---

### 🔧 RunForge — AI Agent Marketplace

A platform where developers deploy autonomous agents from GitHub and subscribers run them. I built the entire stack solo.

```
Developer pushes repo → RunForge scans + deploys → Subscriber triggers run
                                                          ↓
                                          managed browser · tool vault · approvals
                                          crash recovery · billing · observability
```

<table>
  <tr>
    <td><code>agent-platform-api</code></td>
    <td>Python · FastAPI · Postgres · Redis · S3</td>
  </tr>
  <tr>
    <td><code>agent-platform-dashboard</code></td>
    <td>TypeScript · Next.js · Vercel</td>
  </tr>
  <tr>
    <td><code>agent_runtime_platform</code></td>
    <td>Python · systemd workers · crash recovery</td>
  </tr>
  <tr>
    <td><code>agent_runtime_typescript</code></td>
    <td>TypeScript SDK</td>
  </tr>
</table>

> Managed Chromium (Browserbase) · Telegram approval bots · encrypted OAuth vault (Gmail, Calendar, Sheets, Slack, Salesforce) · Stripe Connect · per-customer credential routing · step timeline observability

---

### 🤖 Agents

**[Pattern Discovery Engine](https://github.com/krish1236/pattern-discovery-agent)** — graph-first pattern discovery from research literature. Builds 1000+ node knowledge graphs from 5 APIs. Runs Louvain community detection, NLI cross-encoders, HDBSCAN temporal clustering. Tested on Bitcoin L2 scaling: found the TPS measurement discrepancy (3–7 vs ~13 TPS) and Lightning Network centralization tension across 122 documents.
`Python` `NetworkX` `NLI` `HDBSCAN` `Claude`

**Deal Hunter** — browser-based price comparison across 7 retailers (Amazon, Best Buy, Walmart, Target, Costco, B&H, Newegg). Seller trust scoring + automated cart.
`Python` `Playwright` `Browserbase`

**[Email Digest](https://github.com/krish1236/email-agent)** · **[Price Monitor](https://github.com/krish1236/test-price-monitor)** — inbox summarization via Gmail API. Product price tracking with alert thresholds.

---

### 📱 Products

**[Kircle](https://www.kircle.app)** — rotating savings circles for friends. Automated Stripe payments, real-time tracking, native iOS. 100+ active savers, $50K+ saved through the platform. Currently in TestFlight beta.
`Python` `TypeScript` `Swift` `Stripe`

**SwipeIQ** — credit card recommendation engine with swipe-based UX. Backend API + web app + Chrome extension.
`Python` `TypeScript` `Chrome Extension`

**Faxly** — iOS fax application.
`Swift`

---

### 📊 Other Projects

| | Project | What it does |
|---|---------|-------------|
| 📈 | [**stock-sentiment-analyzer**](https://github.com/krish1236/stock-sentiment-analyzer) | Sentiment analysis on financial news for stock signals |
| 🔍 | **AEO-ENGINE** | Answer engine optimization research pipeline |
| 🎬 | [**netflix-movie-recommender**](https://github.com/krish1236/netflix-movie-recommender-2025) | Movie recommendation engine |
| 📦 | [**package-sorter**](https://github.com/krish1236/package-sorter) | Package routing and sorting |

---

### 🛠️ Tech

```
Languages       Python · TypeScript · Swift · SQL
Backend         FastAPI · Postgres · Redis · S3 · Nginx · systemd
Frontend        Next.js · React · Tailwind · Vercel
Mobile          Swift · iOS · TestFlight
Infra           AWS (EC2 · RDS · ElastiCache · S3) · Let's Encrypt
AI/ML           Claude · sentence-transformers · NetworkX · HDBSCAN
Payments        Stripe · Stripe Connect
Auth            Google OAuth · Slack OAuth · Salesforce · AWS SES
Agents          Browserbase · Playwright · Telegram Bot API
```
