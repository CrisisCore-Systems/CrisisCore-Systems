<h1 align="center">CrisisCore-Systems</h1>
<p align="center"><strong>Security-hardened, trauma-aware software.</strong><br/>
We build tools that keep sensitive data <em>local</em>, verifiable, and useful.</p>

<p align="center">
  <a href="https://github.com/sponsors/CrisisCore-Systems">
    <img alt="Sponsor" src="https://img.shields.io/badge/Sponsor-CrisisCore--Systems-ff4da6?logo=githubsponsors">
  </a>
  <a href="https://ko-fi.com/crisiscoresystems">
    <img alt="Ko-fi" src="https://img.shields.io/badge/Ko%E2%80%91fi-crisiscore-29abe0?logo=kofi">
  </a>
  <img alt="Open Source" src="https://img.shields.io/badge/License-MIT-222">
  <img alt="Security Posture" src="https://img.shields.io/badge/Security-Zero%20Cloud%20%7C%20CodeQL%20%7C%20CSP-2b9348">
</p>

---

## Mission
**Build humane systems under pressure.**  
Software that transforms lived pain into actionable signal—without surrendering privacy.

- **Privacy by design:** local-only storage, no accounts, no trackers.  
- **Security by default:** CodeQL/SAST, CSP hardening, typed inputs, dependency hygiene.  
- **Clinical utility:** exports and workflows that actually help patients & practitioners.

---

## Current Focus — 🩺 Pain Tracker
A security-first chronic pain & injury platform.

- 7-step assessments • **25+ body locations** • nerve symptoms • QoL metrics  
- Heatmaps • longitudinal trends • treatment-effect overlays  
- **WorkSafe BC** reports + clinician-grade CSV/JSON exports  
- **Local-only**: data never leaves your device unless you export it

Repo → **https://github.com/CrisisCore-Systems/pain-tracker**

---

## Roadmap (90 days)
1. **Analytics v2** — comparisons, location heatmaps, treatment overlays  
2. **Clinician Export Pack** — printable visit summary + structured CSV/JSON  
3. **A11y + i18n** — keyboard/reader paths, high-contrast themes, translation scaffold  
4. **Data resilience** — encrypted local backups + import/restore flows  
5. **Template library** — WorkSafe BC variants & clinic presets

---

## Security Posture (non-negotiables)
- **Zero cloud by default** · no hidden analytics · no ad tech  
- **Typed boundaries** with Zod · strict **CSP** · sanitized flows  
- **CodeQL/SAST** in CI · custom **pre-commit gates** (secrets/types/conflicts)  
- **OpenSSF Scorecard goals** · weekly dependency reviews

> We **never** gate critical health or security fixes behind sponsorship.

---

## How to Support
If this work helps you or your patients, fuel the next release cycle:

- **GitHub Sponsors** (monthly tiers, sustainable perks):  
  https://github.com/sponsors/CrisisCore-Systems  
- **Ko-fi** (one-time boosts): https://ko-fi.com/crisiscore  
- **Orgs / Clinics** (invoices & receipts): https://crisiscore.systems/support

**Goal:** first **10 monthly sponsors** → funds CodeQL/SAST time, device testing, and the Clinician Export Pack.  
All sponsors join the README **Security Acknowledgments** and get **priority triage** on one issue/month.

---

## Operating Rules
- Ship small, audited increments.  
- Treat data like a living patient, not a product.  
- Document the edge cases; test the worst paths first.  
- Elegance is empathy made executable.

---

## Stack
**Frontend:** React 18 · TypeScript · Vite · Tailwind  
**Testing:** Vitest · Testing Library · jsdom  
**Viz:** Recharts · Chart.js  
**Security/CI:** CodeQL · npm audit · custom gates · OpenSSF targets

---

## Tree-of-Thought (working map)

Root: Privacy-first Healthcare OSS ├─ Utility → pain maps, timelines, clinician exports ├─ Security → local-only, CodeQL/SAST, CSP, typed inputs ├─ Quality → device testing, perf on low-end hardware, E2E └─ Sustainability → sponsors (briefs, acknowledgments, priority triage)

---

## Contact
- Security & disclosures: **crisiscore.systems@proton.me**  
- Issues / feature requests: open them in **pain-tracker**

<sub><em>Medical disclaimer: Pain Tracker is informational and not a substitute for professional medical advice.</em></sub>
