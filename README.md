<div align="center">

# Andry Corrales

**Projects Analyst · AP SME**

AP automation · agentic AI · finance ops
Costa Rica · open to international roles

[Email](mailto:candrescmo@outlook.com) · [+506 6134-7726](tel:+50661347726) · [LinkedIn](https://www.linkedin.com/in/andry-corrales-mesen) · [CV (PDF)](CV_Andry_Corrales.pdf)

</div>

---

## TL;DR

- 3+ years in AP / finance ops across **P&G, IBM, Accenture** — multi-country, multi-system, high-volume
- Built an **AI-powered AP workflow** for a data-infra client (CoreWeave / Anthropic): unified inbox + Gemini regex pre-indexing + decision-tree SOP assistant. **0 errors in 4 months**, no missed invoices
- Built the **dashboards and tools in this repo** myself. They run in production, not in a slide
- Stack: Apps Script, Gemini API, Claude Code, Python, SQL, SAP, Coupa, NetSuite, Power Apps, Power Automate

If you want the resume version, **grab my CV (link above)**. If you want to see how I think and build, keep scrolling.

---

## What's in this repo

### 1. AP Interactive KPI Dashboard

**[`Dashboards/Accounts Payable-Interactive KPI HTML Dashboard.html`](Dashboards/Accounts%20Payable-Interactive%20KPI%20HTML%20Dashboard.html)** — open in any browser, no install, no backend

A self-contained AP control tower. I built it because nobody on the team had a single view of *"what's open, what's aging, who's blocked, what's getting worse."*

- Aging buckets (0-30 / 31-60 / 61-90 / 90+)
- Open vs. closed, by vendor, by category, by owner
- Click any number → drill-down modal with the rows behind it
- One-click CSV export for the analyst working the queue
- Zero dependencies — one HTML file, runs offline

> **What it shows about me:** I don't wait for a BI ticket. If the data is in a spreadsheet or a system, I turn it into a tool the team uses today.

---

### 2. Daily Backlog Report

**[`Dashboards/Exhibition_Backlog_Report_2026-08-06_201827.pdf`](Dashboards/Exhibition_Backlog_Report_2026-08-06_201827.pdf)** — 4-page auto-generated PDF

- Aging summary + daily delta
- Owner-level accountability
- Vendor concentration risk
- Forecast of when the backlog clears at current pace

Runs on a schedule. The point isn't the report — it's that the team stops asking "where are we?" because the answer is in their inbox every morning.

---

### 3. AI Company AP Workflow — Dynamic Decision Tree

**Client:** data-infra startup (CoreWeave account), delivered under Accenture
**Folder:** [`Projects/AI Company Accounts Payable Workflow - Dynamic Decision Tree/`](Projects/)

The problem I was hired to solve: vendor inquiries about late payments were spiking. Root cause: not every invoice reaching the team by email was being captured. Some never made it to the analysts.

What I shipped in 3 months, in production:

1. **Unified inbox web app** (Apps Script + Gemini API) — every incoming document is read, regex-matched against known patterns, and either auto-indexed or flagged for human review
2. **Dynamic decision-tree SOP assistant** — analyst opens a case, answers 3–5 questions (vendor type, country, has-PO, edge case), and the tool returns the exact step-by-step procedure from the SOP for that case
3. **KPI dashboard + daily backlog report + volume forecast** — same kind of tooling as items 1 and 2 above, pointed at live client data
4. **Team training + handoff** — owned the analyst team, trained them on the tool, monitored for 2 months post-launch, kept iterating based on what the data surfaced

**Result:** 0 errors in 4 months. No missed invoices. Vendor inquiries down to baseline.

#### Screenshots

**Decision tree — case routing logic**

![Decision tree 1](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/Decision%20Tree%201.png)
![Decision tree 2](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/Decision%20Tree%202.png)

**Node-based workflow editor**

![Nodes workflow](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/Nodes%20Workflow.png)

**On-hold invoice tracker**

![On hold tracker](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/On%20Hold%20Invoices%20tracker%20task.png)

**NetSuite PO line selector with proration tool**

![PO selector with proration](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/PO%20Lines%20Selector%20with%20proration%20tool%20-%20Netsuite.png)
![Proration tool](Projects/AI%20Company%20Accounts%20Payable%20Workflow%20-%20Dynamic%20Decision%20Tree/Proration%20Tool%20assistance.png)

---

## How I work

- **Pull the data → build the tool → write the doc.** In that order.
- **Idempotent by default.** Same input, same output, every run.
- **Visible failures over silent ones.** If a script catches an error, I want to know — never swallowed.
- **Tools beat tickets.** If a process is going to run 50 times, I spend 2 hours building a tool, not 50 hours doing it manually.
- **Ownership over hand-offs.** I don't disappear after launch. I monitor, iterate, and train the team that will live with the work.

---

## Stack

**ERP & finance systems:** SAP S/4HANA · Coupa · NetSuite · Ramp
**Microsoft / Google platforms:** Power BI · Power Apps · Power Automate · SharePoint · Excel (advanced) · Apps Script
**AI & data:** Claude Code · Gemini API · Python · SQL · Knime · Tableau
**Other:** Salesforce · DocuSign · Trello · Monday.com · ClickUp
**Creative (side):** DaVinci Resolve Studio · Blender · Adobe Creative Cloud

## Languages

Spanish (native) · English (B2+) · Portuguese (B1)

---

## Get in touch

- **Email:** [candrescmo@outlook.com](mailto:candrescmo@outlook.com)
- **Phone / WhatsApp:** [+506 6134-7726](tel:+50661347726)
- **Location:** San José, Costa Rica (UTC-6)
- **LinkedIn:** [linkedin.com/in/andry-corrales-mesen](https://www.linkedin.com/in/andry-corrales-mesen)
- **CV:** [Download PDF](CV_Andry_Corrales.pdf)

---

<div align="center">

*I'm a Projects Analyst who started in invoices and ended up building the AI workflow that processes them. If that sounds like someone you want on your team, the fastest path is the email above.*

</div>
