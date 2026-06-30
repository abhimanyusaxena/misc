# Indian Government Web Vendors — B2G Market-Entry Intelligence

> **Purpose.** Market and competitive intelligence for launching a **B2G (business-to-government) web / digital-services company** in India. The original framing — "find 100 poorly-built government websites" — is treated here as a *sourcing funnel*: the broken sites are the leads, but the deliverable is understanding **who builds government websites, who owns those companies, what they get paid, and how a new entrant wins this work.**
>
> **Method.** Built from a multi-agent deep-research pass: 5 search angles → 25 sources fetched → 87 factual claims extracted → 25 highest-value claims put through 3-vote adversarial verification (a claim needs 2 of 3 independent "refute" votes to be killed). **23 claims confirmed, 2 refuted.** Confidence labels and vote tallies below are from that process.
>
> **Honesty note.** Everything here uses **public** sources (government portals, corporate filings, cert transparency, press). Exact rupee figures for specific websites are the *weakest* area: only a few are public; most require drilling into individual award notices or filing an RTI. Where a "shortcut" was tested and failed, it is flagged as **REFUTED** so you don't build a plan on it.
>
> *Compiled 2026-06-30. Empanelment rosters and validity dates rotate — re-pull live before relying on them.*

---

## 0. TL;DR for the founder

1. **The incumbent you're really competing with is NIC**, the government's own in-house ICT body — it designs, builds, and hosts a large share of `.gov.in` / `.nic.in` sites for free to the department. Private vendors win the work NIC *doesn't* take, or where a department wants a turnkey/PPP build. Knowing whether a target site is NIC-built or vendor-built is the first triage question.
2. **The market is a barbell.** At the top: large system integrators (TCS, Wipro, Tech Mahindra) running flagship national platforms under PPP/BOOT contracts worth hundreds-to-thousands of crore. In the middle/bottom: e-governance specialists (Silver Touch, CMS Computers, Vayam, ABM Knowledgeware, Corporate Infotech/CIPL) and a long tail of empanelled SMEs doing state/municipal/department portals. **The SME tier is where a new entrant actually competes.**
3. **Getting work is a two-step architecture: empanelment, then tender.** You first get *listed* on the rosters that make you eligible (NICSI, NeGD, CERT-In, STQC), then you *win* published tenders on CPPP/GeM. The empanelment step is the real moat — and the realistic first target for a startup.
4. **Two tempting shortcuts don't work** (see §6): there is **no** reliable standardized "Designed/Developed by ___" footer convention across government sites, and a widely-cited vendor scale statistic collapsed under verification. Don't anchor a sourcing pipeline on footer-scraping alone.
5. **Your fastest legitimate wedge:** register on GeM as an MSME/Startup, pursue the Startup India / MSME public-procurement exemptions (EMD waiver, prior-turnover/experience relaxations), and start as a **subcontractor to an empanelled prime** while you build the credentials to bid directly. (Confidence on the *existence* of these preferences is high; the precise current thresholds need a live re-pull — see Open Questions.)

---

## 1. The competitive landscape — who builds Indian government websites

### NIC — the default, non-private incumbent  ·  *confidence: HIGH (3-0)*
The National Informatics Centre (NIC), under MeitY, self-describes as "the premier ICT Organization of Government of India" and is the **primary constructor of e-government applications**. It maintains the National Portal and a vast number of central/state/district government sites, with State Centres in all 36 states/UTs, 741 district offices, and its own National Data Centres / cloud for hosting.

**Why this matters for you:** when a department uses NIC, there is no private contract and no money to chase — NIC is the competitor *and* the reason many departments never go to market. Your addressable market is the work NIC declines, can't staff, or where a department specifically wants a private turnkey build. NIC-built sites are also disproportionately represented among the "poorly built / stale" set, but those are not commercial leads unless the department is willing to move off NIC.
*Sources: nic.gov.in/about-this-website, en.wikipedia.org/wiki/National_Informatics_Centre, digitalindia.gov.in*

### The large system integrators (top of the barbell)

**TCS — the flagship exemplar.**  ·  *confidence: HIGH (3-0)*
TCS runs the **Passport Seva Project** for the Ministry of External Affairs under a **PPP / BOOT model**: TCS builds and operates the IT and non-IT infrastructure, the core application, the citizen portal, the data centre and DR site, while the government retains all sovereign functions (granting passports, verification). MSA signed Oct 2008; Phase 2 re-awarded to TCS in Jan 2022, so the arrangement is current. This is the template for how a large national citizen-facing platform gets delivered by a private vendor.
*Sources: tcs.com case study, IMPRI India, Amrita University case study, Business Standard (Jan 2022)*

Wipro, Infosys, and Tech Mahindra play in the same large-SI tier (Tech Mahindra and Wipro both appear on NICSI's "Application & Website Development" empanelment — see §2). They are the natural **primes you might subcontract under**, not firms you beat head-to-head early.

### The e-governance specialists (the tier you'll actually compete in)

| Vendor | What they build | Named government clients | Verification |
|---|---|---|---|
| **Silver Touch Technologies** | Turnkey e-governance portals/apps; CMMI L5, ISO 9001/27001/20000 | Ministry of Textiles (GoI), Ministry of External Affairs (web portal), National Skill Development Agency, Gujarat Transport Dept (ADTT), Rajasthan PSC (online application/results), Maharashtra "Aaple Sarkar" grievance portal | HIGH (3-0); client list is vendor-self-published but cross-corroborated for Textiles & MEA |
| **CMS Computers** | State citizen-service / Common Service Center platforms | AP **MeeSeva** (live footer: "Designed and Developed by CMS Computers India Pvt. Ltd."), plus claimed UP Jan Seva, MP Lok Sewa, Rajasthan eMitra, Maharashtra Maha Seva | MEDIUM (3-0 / 2-1); MeeSeva confirmed by live portal + 2026 migration record; the other four and the "150+ utilities / 12 ICS projects" counts are self-reported and likely multi-vendor programs |
| **Vayam Technologies** | Urban/rural e-gov, e-office, citizen-identity; defence web software | SECC census as implementation partner to PSUs (ECIL-Bihar, ITI-MP & UP, BEL-Rajasthan); Bihar e-District; UP CSC (6,000+ centres); Directorate General of Artillery, Ministry of Defence (web app + DMS) | HIGH (3-0); the PSUs held prime contracts, Vayam was implementation partner/subcontractor — a concrete example of the subcontracting path |
| **ABM Knowledgeware** (BSE-listed) | e-Municipality / urban local body software | 1,500+ municipal bodies, 750+ urban local bodies claimed; ~30 smart cities | Secondary source (financial profile); listed-company status makes ownership and financials publicly checkable |
| **Corporate Infotech Pvt. Ltd. (CIPL)** | Unified state digital-governance platforms | **Bihar "BiharOne"** unified citizen-services platform | HIGH (3-0) on the contract; see §3 for the ₹87 cr value |

**Reading the table:** this middle tier is reachable. They win by being empanelled + credentialed (CMMI/ISO) + having reference projects. None of these are unbeatable national champions; they're the realistic peer set for a focused new entrant — especially if you specialize (e.g. municipal portals, or accessibility/GIGW-compliant rebuilds).

---

## 2. Vendor attribution — figuring out WHO built a given site

Goal: take a poorly-built government site and identify the private company behind it. Use these signals in order of reliability.

### ⚠️ The footer shortcut is NOT reliable — *REFUTED (0-3)*
A tempting plan is to scrape the "Content Owned by… / Designed & Developed by…" footer. **Verification killed the claim that this is a standardized, canonical convention across government sites.** NIC's *own* site does carry such a footer, but there is no proven government-wide standard that every site (especially vendor-built or neglected ones) follows. **Use footers as a weak hint, never as your system of record.** Many of the worst sites have no attribution at all, or attribute to NIC even when a vendor did the work.

### Reliable attribution sources (use these instead)

1. **NICSI empanelled-vendor database** — *confidence: HIGH (3-0)*
   NICSI (NIC Services Inc., a 1995 Section-8 company under NIC/MeitY) publishes a **208-record** empanelled-vendor database with a literal **"Application & Website Development"** category (sub-categories: Tier 1, UI/UX, Startup, National e-Vidhan), alongside Cybersecurity & Audits, Consulting, Infrastructure. A dedicated category PDF names firms including **Tech Mahindra, Wipro, Silver Touch, Indus Net**. Each record carries empanelment number, tender reference, and validity period.
   *Where: nicsi.nic.in/nicsi/empanelled-vendors-classic/ — caveat: this shows who is **eligible**, not who built a specific live site.*

2. **NeGD (MeitY) empanelments** — *confidence: HIGH (3-0)*
   National e-Governance Division runs rate contracts directly relevant to web work: a **UI/UX Designers + UX Engineers + Frontend Developers** deployment rate contract (valid to 2027-05-06), and an **On-Premises Security Audit** rate contract restricted to CERT-In-empanelled agencies (valid to 2028-04-07). These are staff-augmentation/rate contracts, not turnkey-build empanelments — useful both as a credential to chase and as an attribution signal.
   *Where: negd.gov.in/empanelment-by-negd/*

3. **CERT-In empanelled security auditors** — *confidence: HIGH (3-0)*
   CERT-In publishes the authoritative roster of **~235–237** empanelled Information Security Auditing Organisations (official ~996-page PDF), each with company name, registered address, website, phone, and a named contact (entry #1: M/s AAA Technologies Ltd, Mumbai — Mr. Anjay Agarwal, CMD). Only CERT-In-empanelled vendors can issue the Safe-to-Host / IT Security Audit certificates required for NIC-hosted / MeitY projects. This roster is a goldmine: it's a *named, contactable list of credentialed competitors and potential partners.*
   *Where: cert-in.org.in/certEmpanelment.jsp → PDF*

4. **STQC "Certified Quality Website (CQW)" records** — *confidence: HIGH (3-0)*
   STQC (under MeitY) is the **sole authority** that issues the CQW mark certifying GIGW 3.0 compliance (empanelled labs/SETLs only test; they cannot issue). Sites that *are* certified vs. the vast majority that are *not* is itself a quality-screening and lead-generation signal — uncertified, non-compliant sites are exactly your "poorly built" funnel.
   *Where: stqc.gov.in/en/website-quality-certification-0*

5. **CPPP / eprocure.gov.in tender + award archive** — *confidence: HIGH (3-0)*
   The Central Public Procurement Portal (NIC-maintained, spanning 31 States/UTs and 700+ central entities) is the **primary place to find which vendor won a contract**. Its "Bid Awards" / "Results of Tenders" section and the Tender Status **AOC (Award of Contract)** filter publish — with no registration — bidder names, L1/L2 rank, contract date, and contract value. Central ministries/autonomous bodies are *mandated* to publish award details here.
   *Where: eprocure.gov.in/eprocure/app → search the department + "website"/"portal"/"web development"; filter to AOC.*

6. **RTI (Right to Information)** — the fallback when the portal is silent. File with the department's PIO asking for the vendor name, contract copy, and amount for a named project. (Mechanics in §3.)

---

## 3. Payment / contract value — how much the government paid

### The structural reality — *confidence: HIGH (3-0)*
The CPPP landing page is **only a navigation hub** — it shows categories and summary counts, **not** specific amounts or vendor names. Real figures live inside individual **AOC award notices** you reach by searching. So:
- **Where a contract was openly tendered and awarded** → the value is usually retrievable from the CPPP/state-portal AOC notice.
- **Where it wasn't itemized publicly** → you need **CAG audit reports** or an **RTI**. Most exact website/portal payment figures fall here.

### Concrete, citable contract values

| Project | Vendor | Value | Confidence |
|---|---|---|---|
| **Passport Seva — Phase 1** (2008) | TCS | **~₹1,000 crore** (₹10,000 million) | HIGH (3-0) — TCS release + Tata/press corroboration |
| **Passport Seva — Phase 2** (2022) | TCS | **₹6,000–8,000 crore** (analyst estimate; *not officially disclosed*; a competing ₹2,000 cr figure exists via IBTimes) | HIGH on the estimate's existence; the figure itself is an estimate, treat as a range |
| **BiharOne** unified digital governance platform (2026) | Corporate Infotech (CIPL), via BELTRON | **₹87 crore** | HIGH (3-0) across DD News, Statesman, Tribune, ThePrint/ANI — caveat: much coverage traces to one ANI press release |
| Goa Labour Welfare Board turnkey e-governance | RailTel | ₹27.06 crore | secondary (Trade Brains) — illustrative of mid-size state e-gov values |

**CAG audit reports** — *confidence: HIGH (3-0)* — are a searchable database (cag.gov.in/en/audit-report; 2,705 reports, filterable by Union/State/Local, report type, sector including a dedicated **"IT Audit"**, and year). This is the authoritative place to find scrutinized e-governance spend, cost overruns, and performance failures — and, usefully, audit reports often *name vendors and amounts* that never surfaced cleanly on the procurement portal.

**RTI mechanics:** address the department's Public Information Officer, ₹10 fee, ~30-day statutory response, ask specifically for (a) the awarded vendor, (b) the signed contract/work order, (c) the total amount paid to date. This is the only universal route to the figures that aren't published.

> **Bottom line for your business model:** you can *reliably* reconstruct values for big, openly-tendered platforms and many state projects; you *cannot* assume you'll get a clean public number for every small website. Budget RTI time into any serious competitive-pricing analysis.

---

## 4. Ownership — who owns the vendors  ·  *the thinnest verified area — see caveat*

The research pass confirmed the **methodology** but did **not** surface verified promoter/owner names for most vendors (those claims didn't reach the verified set). Treat this section as a **research playbook to execute**, not settled facts:

- **MCA21 Master Data (mca.gov.in)** — the authoritative *free* primary source. Search a company's CIN, incorporation date, status, registered office; the **Director Master Data / DIN lookup** maps directors to the companies they sit on. This is your ground truth for ownership and directorships.
- **Listed companies** disclose promoters, shareholding, and financials in BSE/NSE filings — **ABM Knowledgeware** (BSE 531161) and **Silver Touch Technologies** (CIN prefix L72200GJ1995PLC024465 — a listed entity) are directly checkable this way. Start with these because the data is richest and free.
- **Paid aggregators** — Tofler, Zauba Corp, Probe42 — repackage MCA filings with financials and charts. Convenient, but **treated as low-reliability in this pass** (they're secondary scrapes; verify against MCA itself before quoting).

**To do (high-value):** run MCA21 + DIN lookups for Silver Touch, CMS Computers, Vayam, CIPL, ABM Knowledgeware, Allied Digital to extract promoters, directors, incorporation, and authorized capital. I can execute this as a follow-up.

---

## 5. The B2G business-development playbook for a new entrant

The structure of §2–§4 *is* the playbook: **empanel, then tender.** Concrete path:

1. **Incorporate + register on GeM** (Government e-Marketplace) as the baseline selling channel. GeM is where sub-tender-threshold service buys and many product/service contracts flow; it's the lowest-friction first channel for a small firm.
2. **Claim MSME + Startup India preferences.** Public-procurement policy provides MSMEs and DPIIT-recognized startups with advantages — **EMD (earnest money) waivers** and **relaxation of prior-turnover / prior-experience eligibility** that otherwise lock out new firms — plus the Public Procurement (Make in India) Order's domestic-supplier preferences. *Confidence: the existence of these preferences is well-established (Startup India's official "Guide to Public Procurement"); the exact current thresholds and which buyers honor them need a live re-pull — flagged in Open Questions.*
3. **Get empanelled where it's reachable.** Realistic early targets: **STQC GIGW testing**-adjacent work, **NeGD UI/UX & frontend** rate contracts (staff augmentation — a lower bar than turnkey), and **state IT-corporation panels** (BELTRON, etc.). CERT-In empanelment is a strong differentiator but has a higher bar.
4. **Subcontract under a prime first.** The Vayam-SECC example (Vayam as implementation partner to ECIL/ITI/BEL) is the template: large SIs and PSUs hold the prime contract and farm out build work. Getting onto a prime's subcontracting chain is often the *only* way to clear the experience/turnover gates before you can bid directly.
5. **Understand L1 dynamics.** Historically government selection defaulted to **L1 (lowest bid)**, which favors incumbents who can underprice. Policy has been revised to allow quality-cum-cost selection in some categories (ThePrint, 2021) — meaning a differentiated, quality-led pitch (accessibility, security, GIGW compliance, modern UX) can win where the buyer is allowed to weigh quality. Target buyers and tenders that use QCBS, not pure L1.
6. **Pick a wedge specialization.** The funnel of poorly-built sites points to an obvious one: **GIGW-3.0-compliant, accessible, secure rebuilds of neglected state/municipal/PSU sites.** It's underserved, the quality bar is visibly low, STQC certification gives you a credential to sell, and CAG audit findings give you a "your peer department was flagged for this" sales hook.

---

## 6. What was REFUTED — don't build on these

1. **"Government sites carry a standardized builder-attribution footer."** *(0-3)* No proven government-wide convention. Footer-scraping is an unreliable sole basis for vendor attribution — use NICSI/CPPP/AOC instead.
2. **"CMS Computers operates 16,780 common service centers across 100,000+ villages serving millions monthly."** *(0-3)* This widely-circulated vendor statistic failed verification. Don't cite it; don't size the market off it.

---

## 7. Open questions / recommended next steps

The research deliberately flagged gaps. The highest-value follow-ups:

1. **Ownership deep-dive (do this next):** MCA21 + DIN lookups for Silver Touch, CMS, Vayam, CIPL, ABM, Allied Digital → promoters, directors, financials.
2. **Exact, current procurement preferences:** the live EMD-waiver / turnover-relaxation / L1-preference thresholds for MSMEs and Startup-India firms, plus a documented case of a startup winning a government *web* tender via these — to validate the wedge.
3. **GeM vs CPPP for small web jobs:** which platform actually surfaces website/web-development service contracts below tender thresholds, and which is the better attribution/value source for the small jobs a new entrant can win.
4. **Subcontracting chains:** which primes (TCS/Wipro/Tech Mahindra) routinely farm out web/portal builds, and the concrete mechanics of getting onto those chains.
5. **The actual 100-site funnel:** if you want it, a separate scaled pass can screen for poorly-built sites at volume (cert-transparency via crt.sh for `gov.in` subdomains, TLS/HTTPS checks, archive.org staleness, CERT-In defacement history, GIGW/accessibility scans, uptime/performance) and rank them — then attribute the worst via CPPP/AOC.

---

## Appendix — source list

**Primary (government / vendor official):**
- NIC — nic.gov.in/about-this-website
- NICSI empanelled vendors — nicsi.nic.in/nicsi/empanelled-vendors-classic
- NeGD empanelment — negd.gov.in/empanelment-by-negd
- STQC website certification — stqc.gov.in/en/website-quality-certification-0
- CERT-In empanelment — cert-in.org.in/certEmpanelment.jsp
- CPPP / eProcurement — eprocure.gov.in/eprocure/app ; gem.gov.in/cppp
- CAG audit reports — cag.gov.in/en/audit-report
- MCA21 Master Data — mca.gov.in (Master Data Services)
- Startup India — Guide to Public Procurement (startupindia.gov.in)
- TCS Passport Seva case study — tcs.com (public services)
- Silver Touch — silvertouch.com/e-governance
- CMS Computers — cms.co.in ; apmeeseva.cms.co.in
- Vayam — vayamtech.com/eGovernance.html
- DD News — BiharOne ₹87 cr / CIPL

**Secondary (press / analyst):**
- Business Standard (Passport Seva Phase 2), IMPRI India, Amrita University (PPP/BOOT), The Statesman / The Tribune / ThePrint-ANI / OneIndia (BiharOne), Trade Brains (RailTel-Goa), ThePrint (L1 policy revision), financialcontent/PredictStreet (ABM profile).

**Low-reliability / verify-before-citing:** Tofler, Zauba Corp, Probe42, assorted compliance blogs.

*Verification record: 23 of 25 high-value claims confirmed (3-0 or 2-1), 2 refuted (0-3), 0 left unverified.*
