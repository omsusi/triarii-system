# 🔱 TRIARII: Tactical Performance Hub

### *Advanced Performance Monitoring & Mission Deployment System*

**Live System:** [triarii.qzz.io](https://triarii.qzz.io)

---

## 🏗 System Architecture

TRIARII is architected as a high-performance **Serverless Web Application**, optimized for low-latency data synchronization and high-density information display. The system bridges the gap between traditional fitness tracking and enterprise-grade resource management.

### **The Intelligence Stack**

* **Frontend Engine:** [React 18](https://react.dev/) + [Vite](https://vitejs.dev/) for near-instantaneous state hydration and brutalist UI rendering.
* **Real-Time Backbone:** [Firebase Firestore](https://firebase.google.com/docs/firestore) NoSQL database utilizing **Snapshot Listeners** for live "Unit Comms" and mission updates.
* **Authentication & RBAC:** Firebase Auth implementing **Role-Based Access Control**, separating standard Athlete accounts from Command-level administrative privileges.
* **Design System:** [Tailwind CSS](https://tailwindcss.com/) with a custom "Volt-Tactical" configuration, utilizing CSS variables for high-visibility performance monitoring.

---

## ⚡ Key Technical Showcases

### **1. Temporal Access Control (TAC) Logic**

The core innovation of the platform is its dynamic content lifecycle. Instead of static public or private flags, visibility is driven by a time-based state machine:

* **Unit Exclusive:** Missions are encrypted and visible only to assigned units/fleets during the operational window.
* **The Archive Rule:** Once an operational date passes, the system automatically triggers a **"Declassification"**, moving the mission into a searchable public archive.
* **Predictive Navigation:** Authorized units can "look ahead" into future deployments assigned to their specific UID, while guests are restricted to historical data.

### **2. Command & Dispatch Interface**

A comprehensive administrative console designed for rapid-fire operational management:

* **Batch Deployment:** 7-day mission queueing with automated release scheduling.
* **Live Overrides:** The ability to modify any component of a broadcasted mission (Modality, Description, or Assignment) with real-time propagation to all unit devices.
* **Personnel Management:** Full-spectrum oversight of "Centuria Units" (Groups), handling inductions, detachments, and performance monitoring.

### **3. Tactical UX Design**

* **Horizontal Date Scroller:** A custom-engineered timeline allowing users to swipe through operational history.
* **Integrated Themed Calendar:** A deep-archive navigation system utilizing a customized date-picker skin to maintain the ecosystem's aesthetic.
* **Responsive Grid:** A 12-column adaptive layout that scales from a high-speed mobile logging interface to a broad desktop Command Center.

---

## 📈 ERP Potential & Scalability

TRIARII is designed with an **Enterprise Resource Planning (ERP)** mindset. The data structures are prepared for massive horizontal scaling:

* **Workforce Optimization:** The system functions as a specialized HR module for training, tracking "Readiness Heatmaps" across entire organizations.
* **Asset Management:** Potential for a "Gear Inventory" module to track physical training equipment (DIY or Commercial) across different geographic sectors.
* **Data Liquidity:** Every field report and performance metric is stored in a queryable format, ready for integration into Big Data pipelines for long-term health and performance analytics.
* **Monetization Ready:** Built-in hooks for unit-tier subscriptions, allowing private organizations to host exclusive training protocols on a secure, white-label basis.

---

## 🚀 Operational Roadmap

* **[ ] Tactics Database:** Searchable video library for movement standards with an autocomplete mapping engine.
* **[ ] Biometric Sync:** Direct API integration with wearable sensors for real-time RPE and physiological data.
* **[ ] Offline Operations:** Progressive Web App (PWA) implementation for logging missions in remote, low-connectivity field environments.
* **[ ] Automated Intelligence:** Integrating LLMs to generate weekly performance summaries and readiness recommendations based on user "Feeling" scores.

---

## 📊 System Performance & Security Audit

TRIARII is benchmarked using industry-standard tools (**Google Lighthouse** and **Mozilla Observatory**) to ensure the ERP backbone meets production requirements.

### **1. Web Vitals & Frontend Performance**

The system is optimized for "Tactical UX," prioritizing low execution time to ensure athletes can log data during high-intensity sessions.

| Category | Score | Status |
| --- | --- | --- |
| **Performance** | **86/100** | 🟠 Optimizing |
| **Accessibility** | **89/100** | 🟠 High |
| **Best Practices** | **96/100** | 🟢 Excellent |
| **SEO** | **91/100** | 🟢 Excellent |

#### **Technical Deep Dive (Desktop vs. Mobile)**

* **Total Blocking Time (TBT):** Maintained at **120ms** across all platforms. This ensures the UI remains responsive and "jank-free" during complex state updates.
* **Cumulative Layout Shift (CLS):** **0**. The UI is rock-solid; no elements jump around during loading, preventing accidental "mis-clicks".
* **The "Speed Index" Bottleneck:**
* **Desktop:** 4.7s.
* **Mobile:** 8.4s.
* *Analysis:* The high mobile Speed Index is likely due to the initial Firebase handshake and heavy tactical CSS variables. Current roadmap includes implementing **PWA caching** to bring this under 3s.
---

### **2. Security Posture (Mozilla Observatory)**

**Current Grade:** `C (50/100)` — *In-Progress Hardening*.

While the system handles basic security well, the ERP nature of the app requires moving toward an **A+** rating.

| Test Category | Result | Impact |
| --- | --- | --- |
| **HSTS** | ✅ Passed | Forced HTTPS for all Unit Comms. |
| **CORS** | ✅ Passed | Blocked unauthorized cross-origin requests. |
| **CSP** | ❌ **Failed** | No Content Security Policy implemented. |
| **X-Frame-Options** | ❌ **Failed** | Vulnerable to clickjacking via framing. |
| **X-Content-Type** | ❌ **Failed** | Risk of MIME-type sniffing. |

#### **Security Hardening Roadmap**

1. **CSP Implementation:** Deploying a strict policy to prevent unauthorized script execution.
2. **Anti-Clickjacking:** Setting `X-Frame-Options: DENY` to ensure the Command Console cannot be embedded in malicious sites.
3. **Referrer Policy:** Implementing `strict-origin-when-cross-origin` to protect internal route data during navigation.

---

### **3. Operational Significance**

By tracking these "raw" metrics, the TRIARII project maintains a **Transparent Engineering Log**. A 50/100 security score isn't a failure—it's a prioritized backlog. The focus remains on maintaining the **120ms TBT** to ensure the app stays "Tactical" while we incrementally harden the Firebase hosting headers.

---

### **System Credentials**

* **Lead Developer:** [omsusi](https://www.google.com/search?q=https://github.com/omsusi)
* **Build Version:** 2.6.4 (Declassified)
* **Security Protocol:** AES-256 (Equivalent) Encryption on Auth
* **Status:** **FULLY OPERATIONAL**
