# Operational Risk Assessment: Team Morale Monitoring Framework

This repository contains a comprehensive qualitative **Failure Mode and Effects Analysis (FMEA)** and a strategic risk-tracking framework designed to address critical human-capital business liabilities—such as team morale shifts, organizational culture erosion, and downstream reputational damage.

## Executive Framework Overview
Traditional quantitative risk engines rely strictly on financial variables and hard numeric probabilities. However, qualitative vulnerabilities cannot be easily assigned an arbitrary numbers-based valuation without stripping away operational context. 

This portfolio project demonstrates how to structure, prioritize, and mitigate abstract operational constraints using a rigorous **1-to-5 Qualitative Scoring Matrix** across three core dimensions: **Severity (S)**, **Occurrence (O)**, and **Detection (D)** to calculate an actionable **Risk Priority Number (RPN)**.

---

## 1. Qualitative 1-to-5 Scoring Rubric

### Severity Scale (S)
*Measures the operational fallout of a fully realized morale failure.*
* **1 (Negligible):** Dip is isolated/temporary; zero impact on daily deadlines or output metrics.
* **2 (Minor):** Visible team frustration; minor drop in active collaboration but standard milestones remain met.
* **3 (Moderate):** Clear signs of burnout/disengagement; small errors begin surfacing, causing minor re-work.
* **4 (High):** Critical drop in engagement; key personnel voice intent to leave; productivity drop directly delays client roadmaps.
* **5 (Catastrophic):** Total operational paralysis; abrupt resignations of key staff leading to permanent brand or contractual damage.

### Occurrence Scale (O)
*Measures the probability or frequency of the underlying root cause triggering.*
* **1 (Rare):** Extremely unlikely to occur under standard operating parameters; requires a major corporate shock.
* **2 (Unlikely):** Infrequent; only occurs during rare organizational friction points (e.g., massive cross-department restructuring).
* **3 (Possible):** Occasional; tracks alongside predictable business cycles (e.g., end-of-quarter surges).
* **4 (Likely):** Regular; highly predictable based on current baseline operational realities (e.g., sustained uncompensated overtime).
* **5 (Almost Certain):** Inevitable outcome; current environment guarantees a crash within the active sprint cycle unless management intervenes.

### Detection Scale (D)
*Measures management's window of visibility to catch the threat before it impacts deliverables. (Higher = Blinder)*
* **1 (Almost Certain):** Continuous automated anonymous sentiment tracking and active 1-on-1 feedback channels flag early warnings instantly.
* **2 (High):** Reliable internal feedback loops; regular retrospectives capture team friction early.
* **3 (Moderate):** Standard monitoring relies on lagging corporate indicators (e.g., monthly project milestones missed).
* **4 (Low):** Significant visibility blind spots; intermediate friction is actively downplayed or masked by siloed leadership layers.
* **5 (Absolutely Impossible):** Zero tracking protocols established; management completely blind until high-value resignations hit production.

---

## 2. Enterprise Risk Register (FMEA Matrix)

| Failure Mode (The Threat) | Potential Effect of Failure | S | Potential Root Cause | O | Current Monitoring Controls | D | RPN |
| :--- | :--- | :---: | :--- | :---: | :--- | :---: | :---: |
| **Chronic Team Work Overload** | Severe burnout, quality drop, missed project milestones. | **4** | Unrealistic initial timelines, lack of real-time capacity tracking. | **4** | Direct reliance on end-of-cycle project completion reports. | **3** | **48** |
| **Lack of Transparent Communication** | Growing team distrust, operational friction, key staff flight risk. | **4** | Missing centralized town halls, weak vertical feedback loops. | **3** | Annual corporate climate surveys (Lagging indicator). | **4** | **48** |
| **Unclear Roles & Goals** | Duplicated efforts, scope creep, minor project friction. | **3** | Missing "Definition of Done" templates, poor sprint scoping. | **4** | Ad-hoc team meeting check-ins. | **2** | **24** |

$$\text{Risk Priority Number (RPN)} = \text{Severity (S)} \times \text{Occurrence (O)} \times \text{Detection (D)}$$

---

## 3. Actionable Strategic Mitigation Controls

### Threat 01: Chronic Team Work Overload
*   **Preventative Controls (Proactive):** Implement mandatory bi-weekly resource capacity utilization caps. Readjust downstream sprint velocity targets immediately if utilization flags pass historical baselines.
*   **Recovery Controls (Reactive):** Conduct immediate, structured stay interviews with high-risk contributors. Deploy external cross-leveled staff support or re-negotiate roadmap features with client stakeholders before delivery windows expire.

### Threat 02: Lack of Transparent Communication
*   **Preventative Controls (Proactive):** Deploy anonymous monthly pulse surveys paired with direct executive-led Q&A town halls to establish a continuous, transparent feedback loop.
*   **Recovery Controls (Reactive):** Stand up a dedicated management escalation team to address systemic friction points documented in pulse logs.

### Threat 03: Unclear Roles & Goals
*   **Preventative Controls (Proactive):** Standardize scope validation templates and formal engineering alignment sign-offs before pushing code or assignments to production tracking lines.
*   **Recovery Controls (Reactive):** Pause active sprint lines to execute immediate peer-review alignment checkpoints if task redundancies are discovered.
