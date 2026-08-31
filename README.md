# 📊 Business Analytics & Data Visualization — Unit 1

### 🏦 Analytics Process & Data Quality in BFSI

> **From Raw Data → Insights → Decisions 🚀**

Welcome to **Unit 1 of Business Analytics and Data Visualization**, designed for students exploring the intersection of **Data Analytics, Business Decision-Making and the BFSI industry**.

This unit focuses on understanding how financial institutions transform raw data into meaningful insights and business decisions.

---

## 🎯 What Will You Learn?

By the end of this unit, you will understand:

* 📊 What is **Business Analytics**?
* 🧠 Difference between **Analytics & Business Intelligence**
* 🔍 Types of Analytics
* 🔄 Data Analytics Lifecycle
* 🏦 Major Data Sources in BFSI
* ✅ Data Quality Dimensions
* ⚠️ Common Data Quality Issues
* 🛡️ Data Governance
* 🗂️ Data Management Frameworks
* 💼 Real-world BFSI Analytics Applications

---

# 🧠 01 — Business Analytics

### What is Business Analytics?

Business Analytics combines:

```text
📊 Data
   +
🧮 Methods & Techniques
   +
🏦 Business Domain Knowledge
   ↓
💡 Insight
   ↓
🎯 Decision
```

### Key Concept

> **Analytics = Data + Method + Business Question + Decision**

Business Analytics helps answer:

| Question              | Analytics    |
| --------------------- | ------------ |
| 🤔 What happened?     | Descriptive  |
| 🔍 Why did it happen? | Diagnostic   |
| 🔮 What will happen?  | Predictive   |
| 🎯 What should we do? | Prescriptive |

---

# 📈 02 — Four Types of Analytics

### 1️⃣ Descriptive Analytics

**Question:** What happened?

Examples:

* 📊 KPIs
* 📈 Dashboards
* 📉 Trend analysis
* 🏦 NPA reporting

---

### 2️⃣ Diagnostic Analytics

**Question:** Why did it happen?

Examples:

* 🔎 Drill-down analysis
* 🔗 Correlation
* 🧩 Root-cause analysis
* 👥 Cohort analysis

---

### 3️⃣ Predictive Analytics

**Question:** What will happen?

Examples:

* 🤖 Machine Learning
* 📈 Regression
* 🎯 Classification
* ⏳ Time-series forecasting

---

### 4️⃣ Prescriptive Analytics

**Question:** What should we do?

Examples:

* ⚙️ Optimisation
* 🧪 Simulation
* 🎯 Decision rules
* 🔮 What-if analysis

---

# 🔄 03 — Data Analytics Lifecycle

A complete analytics project follows an end-to-end lifecycle:

```text
🎯 Problem Definition
        ↓
📥 Data Collection
        ↓
🧹 Data Processing
        ↓
🔍 Analysis / Modelling
        ↓
📊 Visualisation
        ↓
💡 Decision & Action
        ↓
📈 Monitoring & Feedback
        ↺
```

### 🏦 BFSI Example

**Problem:** Reduce car-loan defaults.

**Data:**

* Loan information
* EMI repayment history
* Credit/Bureau score
* Customer KYC
* Dealer information

**Analysis:**

* Data cleaning
* Feature creation
* Statistical analysis
* Predictive modelling

**Output:**
📊 Dashboard + Model + Business Recommendation

**Decision:**
🎯 Modify lending policy based on risk.

---

# 🏦 04 — Data Sources in BFSI

Financial institutions generate and consume different types of data.

| Data Source           | Examples                 | Major Uses                           |
| --------------------- | ------------------------ | ------------------------------------ |
| 💳 Transactional Data | UPI, NEFT, IMPS, EMI     | Fraud, spending, credit scoring      |
| 📈 Market Data        | Equity, NAV, FX, yields  | Valuation, risk, portfolio analysis  |
| 👤 Customer Data      | KYC, income, behaviour   | Segmentation, churn, personalisation |
| 🏛️ Regulatory Data   | RBI, SEBI, IRDAI reports | Compliance, audit, reporting         |
| 🌐 Alternative Data   | GST, telecom, e-commerce | Credit scoring                       |
| 📄 Unstructured Data  | Emails, calls, documents | NLP, sentiment, insights             |
| 🚗 IoT / Machine Data | Telematics               | Insurance risk & pricing             |

### 💡 Remember

> **Data is the raw material of analytics.**

---

# ✅ 05 — Data Quality

Good analytics requires good-quality data.

### Five Core Data Quality Dimensions

```text
✅ Accuracy
✅ Completeness
✅ Consistency
✅ Timeliness
✅ Validity
```

### ➕ Additional Dimensions

* 🔑 Uniqueness
* 🔗 Integrity
* 🧭 Traceability / Data Lineage

---

# ⚠️ 06 — Common Data Quality Issues

### 🔴 Missing Values

Types:

* MCAR — Missing Completely At Random
* MAR — Missing At Random
* MNAR — Missing Not At Random

Common treatments:

```text
Delete
  ↓
Impute
  ↓
Group-based Imputation
  ↓
Missing Flag
  ↓
Re-collect from Source
```

> ⚠️ In BFSI, regulatory and identity fields should not simply be imputed.

---

### 🟠 Duplicate Data

Examples:

```text
Ram Gopal Prajapati
R. G. Prajapati
Ramgopal Prajapati
```

Possible solutions:

* 🔑 Golden Key
* 🔍 Entity Matching
* 🧹 Remove Duplicates
* 🗂️ Master Data Management

---

### 🟡 Outliers

Outliers may be:

**❌ Data Errors**

or

**✅ Genuine Business Signals**

Detection methods:

* 📦 Box Plot
* IQR
* Z-Score
* Percentile Analysis
* Scatter Plot
* Isolation Forest

> 🚨 In fraud and AML analytics, an outlier may actually be the signal we are looking for.

---

### 🔵 Format Inconsistencies

Common examples:

```text
01/02/2026
2026-02-01
01-02-26
```

Other issues:

* 💰 Currency/unit mismatch
* 🔤 Different category names
* 📱 Different mobile formats
* 🆔 Identifier formatting
* 🧹 Extra spaces
* 🔠 Uppercase/lowercase differences

Tools:

**Excel → Power Query → SQL → Python**

---

# 🛡️ 07 — Data Governance

### What is Data Governance?

Data governance defines:

```text
👤 Ownership
📋 Policies
📐 Standards
🔐 Access Controls
🧹 Data Quality
🧭 Data Lineage
⚖️ Accountability
```

### Key Roles

| Role                     | Responsibility          |
| ------------------------ | ----------------------- |
| 👨‍💼 Chief Data Officer | Data strategy           |
| 👤 Data Owner            | Business accountability |
| 🧑‍💻 Data Steward       | Definitions & quality   |
| 🖥️ Data Custodian       | IT systems & access     |
| 📊 Data Consumer         | Uses certified data     |
| 👥 Governance Council    | Governance decisions    |

---

# 🏗️ 08 — Data Management Frameworks

Important frameworks covered in this unit:

* 🏛️ **DAMA-DMBOK**
* 🏦 **BCBS 239**
* 💻 **COBIT**
* ⚙️ **ITIL**
* 📋 **ISO 8000**
* 📊 **ISO 25012**
* 🧠 **DCAM**
* 📈 **CMMI-DMM**

### BFSI Regulatory Environment

* 🏦 RBI
* 📊 SEBI
* 🛡️ IRDAI
* 🔐 DPDP Act
* 💰 Basel III

---

# 🏢 BFSI Applications

Business Analytics is used across:

### 🏦 Banking

* Credit scoring
* Fraud detection
* Collections analytics
* Cross-selling
* Customer churn
* Branch optimisation
* Risk reporting

### 🛡️ Insurance

* Risk-based pricing
* Claims fraud detection
* Policy renewal prediction
* Reserving
* Customer lifetime value

### 📈 Asset Management

* Portfolio analytics
* AUM analysis
* Risk analytics
* Robo-advisory

### 💳 FinTech

* Growth analytics
* CAC vs LTV
* Alternative-data credit scoring
* Personalisation

---

# 🧰 Tools & Technologies

This unit connects business concepts with practical analytics tools:

```text
📗 Excel
      ↓
🧹 Power Query
      ↓
🗄️ SQL
      ↓
🐍 Python
      ↓
📊 Power BI
      ↓
🤖 Machine Learning
```

---

# 🧪 Practical Lab

### Mini Project — BFSI Data Quality Analysis

Take a raw loan dataset and perform:

```text
📥 Load Data
     ↓
🔎 Data Profiling
     ↓
⚠️ Identify Quality Issues
     ↓
🧹 Clean Data
     ↓
🔁 Remove Duplicates
     ↓
📅 Fix Formats
     ↓
📊 Create Data Quality Scorecard
     ↓
📈 Publish Dashboard
```

### Expected Output

📊 **One-page Data Quality Scorecard**

with metrics for:

* Accuracy
* Completeness
* Consistency
* Timeliness
* Validity
* Uniqueness

---

# 📝 Practice & Exam Preparation

Topics for revision:

* Business Analytics vs Business Intelligence
* Four types of Analytics
* Data Analytics Lifecycle
* BFSI Data Sources
* Data Quality Dimensions
* Missing Values
* Duplicates
* Outliers
* Format Inconsistencies
* Data Governance
* BCBS 239
* Data Management Frameworks

---

# 📚 Unit Structure

```text
UNIT 1
│
├── 📊 Business Analytics
│
├── 📈 Types of Analytics
│
├── 🏦 BFSI Applications
│
├── 🔄 Analytics Lifecycle
│
├── 💾 Data Sources
│
├── ✅ Data Quality
│
├── ⚠️ Data Quality Issues
│
├── 🛡️ Data Governance
│
├── 🏗️ Data Management Frameworks
│
└── 🧪 Practical Lab
```

---

# 🎯 Learning Philosophy

> **Don't just learn the definition.**
>
> **Understand the business problem.**
>
> **Work with real data.**
>
> **Find the insight.**
>
> **Visualise it.**
>
> **Make a decision. 🚀**

---

## 👨‍🏫 Course Information

**Course:** Business Analytics and Data Visualization
**Course Code:** MS5070T
**Unit:** Unit 1 — Analytics Process and Data Quality in BFSI
**Credits:** 4
**Total Learning Hours:** 9 Hours
**Institution:** Medicaps University

---

## ⭐ Quick Revision

```text
Business Analytics
        ↓
Data
        ↓
Method
        ↓
Insight
        ↓
Decision
```

### Remember:

**Good Data → Good Analytics → Better Decisions → Better Business 🚀**

---

## 📌 Repository Purpose

This repository is created for **learning, revision and practical exploration of Business Analytics in the BFSI domain**.

The objective is to connect:

**📚 Academic Concepts + 💼 Industry Use Cases + 🧪 Practical Analytics**

---

### 🚀 Keep Learning. Keep Analysing. Keep Building.

**#BusinessAnalytics #DataAnalytics #BFSI #DataVisualization #FinTech #PowerBI #Python #SQL #Excel #DataQuality #DataGovernance**
