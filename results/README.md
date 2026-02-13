# 🎬 Maven Movies: Insurance Underwriting Analysis

## 📌 Project Background
The insurance policy for **Maven Movies** is up for renewal. To assess risk and approve the new policy, the lead underwriter, **Joe Scardycat**, requested an updated assessment of business operations, inventory, and potential liabilities.

---

### 1. Staff Contact Information
**Request:** A list of all staff members, including first/last names, email addresses, and Store ID.

**Analysis:** Provides the underwriter with the primary points of contact for each physical location.

<img width="574" height="94" alt="image" src="https://github.com/user-attachments/assets/8d3f5fca-7cb6-44f3-971a-ce48c457cabc" />


**Insight:** There are **2 active staff members**: Mike Hillyer(Store 1) and Jon Stephens(Store 2).

---

### 2. Inventory Volume by Store
**Request:** Separate counts of inventory items held at each of the two stores.

**Analysis:** Establishes the volume of physical assets tied to each location for property insurance.

<img width="269" height="88" alt="image" src="https://github.com/user-attachments/assets/566cd747-365d-4b93-8d57-0799f9e91a0b" />


**Insight:** Inventory is split almost evenly, with Store 1 holding 2,270 items and Store 2 holding 2,311 items, showing a total inventory count of 4,581.

---

### 3. Active Customer Assessment
**Request:** A count of active customers for each store location.

**Analysis:** Helps the underwriter understand the foot traffic and active user base size.

<img width="298" height="97" alt="image" src="https://github.com/user-attachments/assets/c9ae379f-62c0-456b-8698-dc4a0fa93c25" />


**Insight:** Store 1 has **318** active customers, while Store 2 has **266**, indicating Store 1 may have higher daily operational risk.

---

### 4. Data Breach Liability (Email Count)
**Request:** A total count of all customer email addresses stored in the database.

**Analysis:** Quantifies the potential risk exposure in the event of a cyber security data breach.

<img width="122" height="66" alt="image" src="https://github.com/user-attachments/assets/e1ed6058-7466-460e-8d50-8117fc29f5b8" />


**Insight:** With 599 unique emails on file, the company has a moderate data liability footprint.

---

### 5. Inventory Diversity (Titles vs. Categories)
**Request:** A count of unique film titles at each store and a count of unique film categories.

**Analysis:** Demonstrates the breadth of the library to assess market engagement and inventory variety.

<img width="239" height="92" alt="image" src="https://github.com/user-attachments/assets/37b9d5a3-ead0-4ba4-9230-c47fa2982bfc" />
<img width="219" height="64" alt="image" src="https://github.com/user-attachments/assets/85a2b94f-758a-4c01-bac4-12f4b0b8a698" />



**Insight:** Store 1 has **759** unique titles and Store 2 has **762** unique titles. Across the entire business, there are **16 unique film categories** offered.

---

### 6. Asset Replacement Cost Analysis
**Request:** The minimum, maximum, and average replacement cost of the film library.

**Analysis:** Provides the "worst-case scenario" financial figures for total loss claims.

<img width="560" height="75" alt="image" src="https://github.com/user-attachments/assets/43e5971d-aa4a-4ab1-bebd-d67ffc6fd84a" />


**Insight:** 
* **Minimum Cost:** $9.99 
* **Maximum Cost:** $29.99 
* **Average Cost:** $19.98

---

### 7. Fraud Prevention (Payment Monitoring)
**Request:** The average and maximum payment amounts processed.

**Analysis:** Establishes a baseline for transaction monitoring and fraud detection limits.

<img width="336" height="72" alt="image" src="https://github.com/user-attachments/assets/9f6605c1-df76-4468-920a-1c6cc2b18813" />


**Insight:** The average transaction is **$4.20**, while the maximum historical payment is **$11.99**.

---

### 8. Customer Loyalty & Rental Volume
**Request:** A list of all customer IDs and their total rental counts, ranked by highest volume.

**Analysis:** Identifies the high-value customers who interact most frequently with the assets.

<img width="313" height="237" alt="image" src="https://github.com/user-attachments/assets/38bb9baa-4e24-4c5c-8b82-d5cf2e1d2f59" />


**Insight:** The top customer (ID **148**) has rented **46 films** all-time. Monitoring high-volume users helps identify potential patterns of asset depreciation.

---

## Tech Stack
* **Database:** MySQL
* **Documentation:** GitHub Markdown
* **Analysis Tool:** MySQL Workbench

---
