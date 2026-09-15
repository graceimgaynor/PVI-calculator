<div align="center">

# 🚀 PVI 360 Performance Advisor

https://img.shields.io/badge/Cisco-PVI-blue?style=for-the-badge
![TD SYNNEX](https://img.shields.io/badge/TD%ner%20Success-green?style=for-the-badge
![AI](https://img.shields.io/badge/AI-Assisted%20Insightse?style=for-the-badge
![Forecasting](https://img.shields.io/badge/Forecasting?style=for-the-badge

### 📊 Transform Cisco Partner Value Index Data Into Actionable Insights

**Analyze. Forecast. Plan. Improve.**

</div>

---

# 🌟 Overview

The **PVI 360 Performance Advisor** is an interactive performance intelligence application built to help Cisco stakeholders understand current Partner Value Index (PVI) results, rebate status, performance drivers, future projections, and improvement opportunities.

Instead of manually reviewing complex DPV exports and calculator worksheets, this application translates partner assessment data into:

✅ Interactive dashboards

✅ Portfolio-specific analytics

✅ Strength and weakness assessments

✅ Hypothetical scenario planning

✅ Gap-to-tier analysis

✅ Fiscal month comparisons

✅ AI-assisted insights

✅ Historical trend forecasting

---

# 🎯 Business Objectives

The application answers the most important partner questions:

### 📍 Where are we today?

Current official PVI score

### 🤔 Why are we here?

Identify strengths and weaknesses

### ⚡ What drives improvement?

Weighted metric analysis

### 📈 Where are we heading?

Historical trends and forecasting

### 🏆 Can we reach the next rebate tier?

Gap-to-threshold modeling

---

# 🧭 Application Workflow

```text
DPV Export
    │
    ▼
Upload CSV / XLSX
    │
    ▼
Portfolio Selection
    │
    ▼
Fiscal Month Selection
    │
    ├── Official PVI
    ├── Strength Assessment
    ├── Weakness Assessment
    ├── Metric Analysis
    ├── Scenario Planning
    ├── Forecasting
    └── Recommendations
```

---

# 🏗️ Architecture

```text
Frontend
│
├── HTML
├── CSS
├── JavaScript
├── SheetJS
└── Dashboard UI

Backend
│
├── Cloudflare Workers
├── Forecasting API
├── PVI Forecast Engine
└── AI Integration Layer

Data Sources
│
├── CSV
├── XLS
├── XLSX
└── DPV Exports
```

---

# 📂 Supported File Types

| File Type | Supported |
|------------|-----------|
| CSV | ✅ |
| XLS | ✅ |
| XLSX | ✅ |

---

# 🧩 Supported Cisco Portfolios

| Portfolio | Description |
|------------|------------|
| 🌐 Networking | Networking portfolio metrics |
| ☁️ Cloud + AI Infrastructure | Cloud and AI metrics |
| 🔒 Security | Security portfolio analysis |
| 🤝 Collaboration | Collaboration portfolio analysis |
| 🛠️ Services | Services portfolio analysis |
| 📊 Splunk | Splunk portfolio analysis |

Each portfolio has its own:

- Weight structure
- Metric structure
- Category calculations
- Performance requirements

---

# 📅 Fiscal Month Analysis

Users can analyze data by:

✅ Fiscal Month

✅ Partner

✅ Portfolio

This enables trend analysis instead of relying on a single point-in-time assessment.

---

# 🎯 Current PVI Intelligence

## Official PVI

Displays the official score loaded from the assessment file.

```text
Overall Category
+
Overall Measurement
=
Official PVI
```

### Example

```text
6.84
```

---

## Gap To Next Tier

Shows how many points remain before reaching the next rebate threshold.

Example:

```text
Current PVI: 6.84

Preferred Threshold: 7.50

Gap = 0.66
```

---

## Tier Classification

### 🔴 Below Threshold

```text
PVI < 5.0
```

---

### 🟡 Portfolio Partner

```text
5.0 ≤ PVI < 7.5
```

---

### 🟢 Preferred Partner

```text
PVI ≥ 7.5
```

---

# 💪 Strength Assessment

The application automatically identifies the strongest scoring areas.

Examples:

✅ Black Belt Certifications

✅ Career Certifications

✅ Practice Maturity

✅ Buying Program Penetration

✅ Customer Success Metrics

Purpose:

```text
Protect what is already working.
```

---

# ⚠️ Weakness Assessment

The application highlights:

- Lowest scoring metrics
- Largest gaps
- Potential rebate risks
- Improvement candidates

Purpose:

```text
Focus effort where impact is highest.
```

---

# ⚖️ Weighted Metric Calculator

Each portfolio follows approved Cisco weighting structures.

Calculation logic:

```text
Metric Index
×
Category Weight
×
Metric Weight
=
Weighted Contribution
```

All contributions are summed into the portfolio PVI.

---

# 📊 Calculation Audit

The dashboard exposes the math.

Instead of:

```text
PVI = 6.74
```

Users can see:

✅ Category contribution

✅ Metric contribution

✅ Metric weighting

✅ Portfolio weighting

Making calculations fully transparent.

---

# 👕 T-Shirt Sizing

Partner bands are determined using TCV.

| Band | TCV |
|--------|--------|
| XS | ≤ $2M |
| S | $2M–$10M |
| M | $10M–$25M |
| L | $25M–$100M |
| XL | > $100M |

The selected band impacts threshold calculations.

---

# 🧪 Hypothetical Scenario Planner

One of the most powerful capabilities.

The planner allows users to model:

```text
What happens if certifications improve?

What happens if adoption increases?

Will this partner reach Preferred?

What is the fastest path to 7.5?
```

---

## Scenario Example

Current:

```text
Networking
Current PVI = 6.40
```

Changes:

```text
Black Belt Certified
6 → 8

Career Certifications
5 → 7
```

Projected:

```text
Scenario PVI = 7.12
```

---

# 🔮 Historical Forecasting Engine

The forecasting module evaluates:

✅ Historical monthly PVI

✅ Portfolio trajectory

✅ Month-over-month change

✅ Trend direction

✅ Expected year-end positioning

---

## Forecast Inputs

```text
FY26M1 = 4.8
FY26M2 = 5.1
FY26M3 = 5.3
FY26M4 = 5.5
```

---

## Forecast Outputs

```text
FY26M5 = 5.64
FY26M6 = 5.81
FY26M7 = 5.97
FY26M8 = 6.10
```

Also includes:

✅ Confidence bands

✅ Trend interpretation

✅ Risk indicators

✅ Threshold projections

---

# 🤖 AI Intelligence Layer

The AI layer is intended to provide explanations, not official calculations.

---

## AI Can Explain

✅ Why scores changed

✅ What metrics moved

✅ Forecast interpretation

✅ Potential risks

✅ Improvement opportunities

✅ Executive summaries

---

## AI Cannot Do

❌ Create official PVI scores

❌ Override Cisco calculations

❌ Change approved weights

❌ Invent missing metrics

❌ Replace PXP

---

# 🔒 Security Principles

## Official Source of Truth

```text
PXP
```

Always remains the official source of truth.

---

## Forecasts

Forecasts are:

```text
MODELED OUTPUTS
```

Not official Cisco scores.

---

## Credential Management

Never place API credentials inside:

❌ HTML

❌ JavaScript

❌ GitHub

❌ Shared spreadsheets

❌ Frontend code

Use:

✅ Server-side secrets

✅ Secure secret stores

✅ Cloudflare Worker secrets

✅ Enterprise key management

---

# ☁️ Cloudflare Worker Forecast API

Endpoint:

```text
POST
/api/pvi/forecast
```

Payload:

```json
{
  "portfolio": "Networking",
  "history": [
    {
      "fiscal_month": "FY26M1",
      "official_pvi": 4.2
    }
  ],
  "remaining_periods": [
    "FY26M2",
    "FY26M3"
  ]
}
```

Response:

```json
{
  "portfolio": "Networking",
  "forecast": [
    {
      "fiscal_month": "FY26M2",
      "forecast_pvi": 4.35
    }
  ]
}
```

---

# 🧰 Technology Stack

## Frontend

```text
HTML
CSS
JavaScript
SheetJS
```

---

## Backend

```text
Cloudflare Workers
REST APIs
JSON
```

---

## Forecasting

```text
Linear Trend Analysis
PVI Time Series
Confidence Bands
```

---

## AI

```text
LLM Integration
Executive Summaries
Forecast Explanations
Recommendation Narratives
```

---

# 🚀 Local Development

## Prerequisites

✅ Windows

✅ Git

✅ Node.js LTS

✅ Visual Studio Code

✅ Cloudflare Account

---

# ▶️ Start Frontend

Use Live Server:

```text
http://localhost:5500
```

---

# ▶️ Start Backend

```powershell
npm install

npm run dev
```

Worker endpoint:

```text
http://localhost:8787
```

---

# 📈 Future Roadmap

## Phase 1

✅ Dashboard

✅ Uploads

✅ Scenarios

✅ Forecasting

---

## Phase 2

🚧 Forecast visualization

🚧 Trend charts

🚧 Historical comparisons

🚧 Portfolio benchmarks

---

## Phase 3

🚧 AI executive summaries

🚧 Natural language insights

🚧 Recommended actions

🚧 Automated reporting

---

## Phase 4

🚧 CRM integration

🚧 PXP integration

🚧 Power BI integration

🚧 Copilot integration

🚧 Multi-partner benchmarking

---

# 🎉 Success Criteria

The application should allow every user to answer:

✅ What is the current PVI?

✅ What drives that score?

✅ What are my strengths?

✅ What are my weaknesses?

✅ What should improve next?

✅ Can I reach Preferred status?

✅ What happens if I improve key metrics?
