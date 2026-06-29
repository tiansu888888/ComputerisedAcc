# 📊 ASE20095: Computerised Accounting Skills Level 2 Interactive Study Hub

A premium, interactive, and bilingual (English/Chinese) study platform designed for the **ASE20095: Computerised Accounting Skills** course. Built with a modern Macaron Glassmorphism design system, smooth keyframe animations, and zero-dependency client-side interactivity.

---

## 🎨 System Preview & Interface

![Accounting Hub Preview](assets/macaron_accounting.png)

> [!NOTE]
> The hub features a curated **Macaron Aesthetic** designed for maximum engagement and visual relief during study sessions:
> - **Dreamy Pastel Gradients:** Shifting backgrounds of Rose Pink, Lavender, Soft Blue, and Mint Green.
> - **Glassmorphic Cards:** Frosted glass blocks (`backdrop-filter: blur(40px)`) with crisp borders and deep charcoal typography (`#111111`) for perfect contrast and readability.

---

## 🚀 Key Features

### 1. 📅 14-Week Curriculum & Detailed Syllabus
Step-by-step guides covering the entire course syllabus, completely translated in both English and Chinese:
- **Week 1-2:** AIS System Intro, database parameters setup, COA grouping structure, and database restoration in SQL & Million Accounting systems.
- **Week 3-4:** Ledgers postings (invoicing sales/purchases), Malaysia SST Tax Tariffs (6% / 8% / 5% / 10% rates, tax codes SR/TX/OS, SST-02 preparation), and Salary journal accrual entries.
- **Week 5-6:** Correcting transaction errors (reversals, adjustments, audit trail logs), procurement documents (PO/GRN matching), and stock synchronization.
- **Week 7-8:** Customer & supplier aging reports (liquidity control), custom filters (filtering P&L by Date range, Project code, and Department code).
- **Week 9-10:** Cloud Accounting architecture (security role-based permissions matrix), and AI automation (Optical Character Recognition (OCR) invoice imports, automated bank feeds matching rules).
- **Week 11-12:** E-Commerce integration (Shopify api sync, Stripe credit card payment processing gateway fees posting), and AI-driven predictive cash forecasting.
- **Week 13-14:** Data governance & ethical compliance, audit trails, and Year-End Closing procedures in SQL & Million.

### 2. 🎮 Interactive Self-Assessments
Every module features a fully functional client-side practice suite:
- **Knowledge Check (Quiz):** 5 multiple-choice questions per week with instant correctness feedback.
- **Fill in the Blanks:** Inline double-entry and Malaysia SST tax calculation checking.
- **Coding Practice:** 3 interactive tasks per week with "Show Answer" toggleable SQL queries and Excel formulas.
- **Matching Game:** Interactive terms and definitions card-matching game, randomized using a seeded deterministic shuffle.

### 3. 🌐 Dual-Language Translation Toggle
A unified, zero-dependency **CSS Class-Driven Translation Engine** allows students to instantly switch the entire interface between **English** and **Chinese** (`🌐 EN / 中文`) with a single click.

---

## 📂 Project Structure

```bash
ASE20095/
└── website/
    ├── index.html            # Main Portal Dashboard (Week 1-14 navigator)
    ├── Accounting-Note.html  # Comprehensive Single-Page Application Note Hub
    ├── week1.html ... week14.html
    ├── README.md             # Repository Readme (This File)
    ├── DESIGN.md             # Design Style Tokens
    └── assets/
        └── macaron_accounting.png  # Premium 3D theme graphic (Showcased above)
```

---

## 📚 Curriculum & Chapter Outline

| Week | Chapter | Key Concepts & Takeaways | Exam Topic Hint |
|------|---------|--------------------------|-----------------|
| **WK1** | AIS Intro | Database connection settings, security user privileges, system logins. | *Detail roles of AIS database setup.* |
| **WK2** | COA Setup | RESTORE backup files (.FDB/ZIP), configure Chart of Accounts categories. | *Explain data restoration steps.* |
| **WK3** | Ledgers & SST | Post sales/purchase invoices; apply Malaysia SST (6% / 8% / 5% / 10% rates). | *Map tax codes SR/TX/OS to invoices.* |
| **WK4** | Salary Journals | Post payroll journals, compute EPF contributions (11%/13%), deduct PCB. | *Draft salary journal accrual entries.* |
| **WK5** | Error Correction| Locate errors of principle, omission, commission; audit trail, post reversals. | *Draft correction adjusting journals.* |
| **WK6** | Procurement | Generate PO, Goods Received Note (GRN); inventory update, COGS posting. | *Trace stock level decreases.* |
| **WK7** | Aging Reports | Debtors/creditors aging lists (30/60/90 days), set credit limits blocks. | *Explain aging-driven credit control.* |
| **WK8** | Custom Filters | Filter reports by Projects and Departments; query transaction logs. | *Analyze cost center segment profitability.* |
| **WK9** | Cloud Systems | Cloud vs Desktop platforms, SSL encryption, MFA login protocols. | *Draft role-based permission matrix.* |
| **WK10**| AI OCR Ingestion| Scan PDF invoices using OCR, set automatic bank feeds reconciliation rules. | *Explain bank rules matching logic.* |
| **WK11**| Integrations | Shopify sync, post payment gateway Stripe processing fees (2% net offset). | *Post e-commerce journal adjustments.* |
| **WK12**| Cash Forecast | AI cash forecasting models, calculate Current and Quick liquidity ratios. | *Evaluate company working capital health.* |
| **WK13**| Data Governance | Database lock dates, check audit logs for backdated invoice alterations. | *Enforce anti-tampering period locks.* |
| **WK14**| Year-End Close | Reset revenue/expenses accounts to zero, transfer net profit to Retained Earnings.| *Detail SQL/Million year-end closings.* |

---

## 🛠️ How to Run Locally

Since the platform is built purely with **Vanilla HTML5, CSS3, and JavaScript**, no installation or server configuration is required:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/ase20095-accounting-hub.git
   cd ase20095-accounting-hub/website
   ```
2. **Open in Browser:**
   Simply double-click `index.html` to launch the study hub dashboard in any modern web browser.
3. **Optional (Local Dev Server):**
   If you want to run a local HTTP server:
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your web browser.
