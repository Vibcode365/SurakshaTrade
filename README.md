# FinSafe — Financial Advice Authenticity Auditor & Scam Detection Suite

A comprehensive financial investor safety platform featuring real-time verification of social media financial advice, YouTube/Instagram reels authenticity checks against regulatory heuristics, multilingual layman explanations, and broker verification.

---

##  Key Features

### 1. Finfluencer Video & Reel Authenticity Auditor
- Paste any YouTube video, Short, Instagram Reel, or social media link to audit claims in real-time.
- Evaluates content against **6 Core Statutory Regulatory Pillars**:
  1. Mandatory Disclosures & SEBI Licensing (INH/INA verification)
  2. Return Guarantees & Asymmetric Risk Disclosures (SEBI 89% retail F&O loss mandate)
  3. Manufactured Urgency & FOMO Tactics (Private VIP Telegram signal funneling)
  4. Analytical Rigor vs. Sensationalism (Financial statements vs. clickbait P&L)
  5. Pump-and-Dump & Illiquid Asset Indicators (Micro-cap & penny stock promotion)
  6. Affiliate & Brokerage Arbitrage (Unregulated offshore platforms & deposit bonuses)
- **Built-in Regulatory Violation Reporting**: Direct pre-filled escalation flow for fraudulent creators.
- **Multilingual Layman Explanations**: Plain-English definitions of complex financial jargon with regional translations in 10+ Indian languages (Hindi, Punjabi, Marathi, Tamil, Telugu, Bengali, Gujarati, Kannada, Malayalam, Odia).
- **Multilingual Video Summaries**: Structured breakdowns (Claims, Omissions, Regulatory Assessment, Action Plan) in selected languages.

### 2. Investment & Ponzi Scam Inspector
- Natural language and URL heuristics scanner for suspicious guaranteed return schemes, fake IPO allotments, and WhatsApp trading group traps.

### 3. Broker & Intermediary Verification
- Verifies registration credentials against statutory databases.

---

##  Tech Stack

- **Frontend**: React, Tailwind CSS, Lucide Icons
- **Backend**: Node.js, Express, Vite
- **Integrations**: YouTube Data & oEmbed Metadata Extraction, Web Speech API

---

##  Getting Started Locally

### Prerequisites
- [Node.js](https://nodejs.org) (v18 or higher)
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# 2. Install dependencies
npm install

# 3. (Optional) Configure environment variables
cp .env.example .env

# 4. Start the development server
npm run dev
```

The application will be live at `http://localhost:3000`.

---

##  Building for Production

```bash
npm run build
npm start
```

---

##  License
MIT License. Open for educational and investor-protection purposes.
