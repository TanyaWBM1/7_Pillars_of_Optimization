# ⚠️ EXAMPLES OF COMPLETED ARTIFACTS (FOR ILLUSTRATION ONLY) ⚠️

**Disclaimer:** *The following are strictly hypothetical examples designed to show how a practitioner would fill out the template documents in the real world. They are meant to demonstrate the process of practitioner optimization. The canonical authority on pillar definitions always remains the primary [7 Pillars of Optimization White Paper](../docs/7-pillars-optimization-whitepaper.md).*

---

## Background for these Examples
* **Scenario:** A B2B SaaS company is publishing a high-stakes, 2,000-word guide.
* **Content Title:** "How to Audit AI Supply Chains for Data Privacy"
* **Operating Mode:** Authority Mode

---

## EXAMPLE 1: Filled Pillar Scorecard

**Project/URL:** How to Audit AI Supply Chains for Data Privacy  
**Practitioner/Owner:** Jane Doe, Lead Content Architect  
**Date:** 2026-02-22  
**Primary Operating Mode:** Authority Mode  

| Pillar | Focus | Pass / Fail | Practitioner Notes & Adjustments |
| :--- | :--- | :--- | :--- |
| **SEO** | Findability | PASS | Added `FAQPage` schema. Images compressed to AVIF for INP compliance. |
| **GEO** | Ingestion | PASS | Added a 3-column HTML table detailing "Vendor / Risk Level / Mitigation" for easy LLM extraction. |
| **AIO** | Summarization | PASS | Formatted H2: "What is an AI Supply Chain Audit?" followed immediately by a 45-word objective definition. |
| **SDO** | Meaning | PASS | Added a "Boundary Box" explicitly stating this guide does *not* cover financial auditing, only data privacy. |
| **EEO** | Trust | PASS | Embedded screenshots of our internal audit dashboard (redacted) to prove we actually do this work. |
| **NLO** | Retention | PASS | Used the metaphor of a "water filtration system" to explain data provenance to non-technical readers. |
| **HEO** | Ethics | PASS | Added disclaimer: "This is operational guidance, not formal legal advice. Consult a data privacy attorney." |

**Final Status:** Approved for Publish

---

## EXAMPLE 2: Filled Cross-Pillar Tension Log

**Project:** How to Audit AI Supply Chains for Data Privacy  
**Date:** 2026-02-20

### Tension Record 1
* **Conflict:** Snippability (AIO) vs. Nuance (SDO)
* **Description:** The legal definition of "Data Provenance" is highly complex. If we make it short enough for an AI Overview (AIO) to grab it, we risk losing the legal nuance required for Semantic Depth (SDO).
* **Pillars at odds:** AIO vs. SDO
* **Resolution (Dual-Lane Application):** We put a strict, simplified 40-word definition directly under the H2 to satisfy AIO (Machine Lane). Immediately below that block, we added a narrative paragraph explaining the legal exceptions and gray areas to satisfy SDO (Human Lane). 

### Tension Record 2
* **Conflict:** Conversion Pressure vs. Ethics (HEO)
* **Description:** Marketing wanted the call-to-action to say: "Use our software to guarantee 100% compliance and avoid fines." 
* **Pillars at odds:** Commercial Mode vs. HEO
* **Resolution (Dual-Lane Application):** HEO Veto applied. "100% guarantee" is a manipulative claim because regulations are constantly shifting. Changed CTA to: "Use our software to automate your audit logs and reduce compliance blind spots."

---

## EXAMPLE 3: Filled Dual-Lane Publishing Spec

**Project:** How to Audit AI Supply Chains for Data Privacy  

### 1. Machine Lane (Extraction Layer)
*This content must exist on the page to satisfy SEO, GEO, and AIO.*

* **Metadata & Schema:** `TechArticle` schema, defining entities: [LLM], [Data Privacy], [SOC2 Compliance].
* **BLUF Summary:** "An AI supply chain audit evaluates the origin, security, and licensing of third-party data used to train machine learning models. It is required to ensure compliance with the EU AI Act and prevent unauthorized exposure of Personally Identifiable Information (PII)."
* **Structural Elements:** Un-nested bullet list of the 5 required audit steps. "What This Is Not" boundary box placed before the conclusion.

### 2. Human Lane (Meaning Layer)
*This content satisfies SDO, EEO, NLO, and HEO.*

* **Narrative Hook:** We open with the real-world story of a company that accidentally leaked customer data because a third-party AI vendor changed their terms of service overnight. 
* **Proof of Action:** A video walkthrough embedded showing our lead engineer conducting a live audit on an open-source model. 
* **Disclosure Block:** "AI was used to format the HTML tables in this article
