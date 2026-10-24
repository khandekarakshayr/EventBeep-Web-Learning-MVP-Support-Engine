# EventBeep Web Learning MVP & Support Engine

> **Live Production Web App:** [https://khandekarakshayr.github.io/EventBeep-Web-Learning-MVP-Support-Engine/](https://khandekarakshayr.github.io/EventBeep-Web-Learning-MVP-Support-Engine/)  
> **Source Repository:** [https://github.com/khandekarakshayr/EventBeep-Web-Learning-MVP-Support-Engine](https://github.com/khandekarakshayr/EventBeep-Web-Learning-MVP-Support-Engine)

---

## 1. The 3 Biggest Problems Students Face (Evidence-Based)

Public Play Store reviews, LinkedIn disclosures, and Reddit threads reveal three critical friction points in the existing platform ecosystem:

### Problem 1: Broken Customer Support Pipeline
- **Evidence:** Multiple Play Store user reviews cite unresolved billing issues, zero response on listed contacts, and generic bot loops when handling paid package failures.
- **Impact:** Immediate loss of brand credibility, negative app store ratings, and high student churn.

### Problem 2: Misrepresented Job Fairs & Forced Subscriptions
- **Evidence:** Public candidate testimonials (e.g., Pune Job Fair reports on LinkedIn) highlight discrepancies between advertised recruiter counts and actual ground presence, where participation was gated behind mandatory annual subscriptions.
- **Reference:** [LinkedIn Candidate Report](https://bit.ly/4i4AJTN)

### Problem 3: "Job Guarantee" Disconnect & Incomplete Course Delivery
- **Evidence:** Extended complaints on consumer and legal advisory forums (Reddit `r/pune` & `r/LegalAdviceIndia`) detailing incomplete curriculum rollouts, mentor dropouts mid-cohort, and unfulfilled placement/stipend guarantees post-payment.
- **References:** [Reddit Discussion 1](https://bit.ly/4i1Pc2J) | [Reddit Discussion 2](https://bit.ly/3UFbFtv)

---

## 2. What I Built (The Working Solution)

A fully functional, responsive client-side web application built around EventBeep's Yellow (`#FFCC00`) and Black design language. It directly resolves the support failure mode while modernizing course consumption.

### A. Strict Human-In-The-Loop (HITL) Support Desk
- **Dynamic Contextual AI Assistant:** Resolves routine platform queries instantly to offload ticket volume.
- **Staff Monitor Console (Real-Time Intercept):** Actively monitors user input for sensitive escalations (`refund`, `scam`, `fraud`, `legal`).
- **Strict Mutex Lock Override:** When an administrator clicks **Takeover Chat**, an immediate synchronous lock (`useRef`) silences the automated AI engine. The AI is completely muted, allowing 100% human agent communication without conflicting bot messages.

### B. Value-Add Multi-Modal Learning Engine
- **Dynamic 'My Desk' Architecture:** Full flexibility to search, add, and remove courses. Includes a live-calculated multi-course cart and an authentic OTP checkout verification flow.
- **Dual-Voice Audio Narration:** Browser-native Web Speech API integration with selectable Male and Female audio synthesis.
- **1-Click AI Gist:** Instant chapter distillation allowing students to review key takeaways in seconds.
- **12-Page Study Guides (PDF Export):** In-browser DOM-to-PDF compilation via `html2pdf.js` for offline reading.
- **Interactive 5-Question Evaluator:** Diagnostic module quizzes with instant color-coded Correct/Incorrect feedback and retake support.

---

## 3. AI Tools & Technical Architecture

- **Gemini 3.1 Pro (Architectural Thought Partner):** Used for architecting state flows, validating edge cases, and designing the asynchronous mutex lock mechanism to prevent AI cross-talk during manual support takeover.
- **Web Speech API:** Client-side speech synthesis providing low-latency audio accessibility without third-party API keys.
- **React 18 & Babel (Client-Side Single Page Application):** Zero-build in-browser execution ensuring high performance, rapid iteration, and direct static hosting on GitHub Pages.
- **html2pdf.js:** Client-side vector document rendering engine for dynamic PDF generation.
- **Tailwind CSS:** Custom utility layout strictly mapped to EventBeep's official visual brand assets.

---

## 4. Business Impact: 7-Day Measurable Metrics

| Target Metric | Expected Shift | 7-Day Measurement Methodology |
| :--- | :--- | :--- |
| **First Contact Resolution (FCR) Rate** | **+40% to +50%** | Monitored via Support Console Analytics. Track the ratio of self-resolved automated chats vs. flagged escalations. An automated resolution rate above 60% without user abandonment confirms positive FCR movement. |
| **Course Module Completion Rate** | **+20% to +25%** | Measured via click-through rate (CTR) telemetry on Audio Player interactions, 'AI Gist' generation, and Quiz submissions compared against legacy static text drop-off baselines. |

---

## 5. Local Setup & Verification

1. Clone repository:
   ```bash
   git clone [https://github.com/khandekarakshayr/EventBeep-Web-Learning-MVP-Support-Engine.git](https://github.com/khandekarakshayr/EventBeep-Web-Learning-MVP-Support-Engine.git)
