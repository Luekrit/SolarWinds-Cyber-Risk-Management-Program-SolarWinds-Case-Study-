# 🧱 Component 1 – Asset Evaluation and Classification

# 🧱 Component 1.1 – Asset Inventory Creation

## 🧠 Objective
Develop a **comprehensive asset inventory** to identify all **physical, digital, and human resources** used by SolarWinds Corporation. This serves as the foundation for evaluating asset criticality, classifying risk, and aligning security measures with business priorities.

---

## 🧩 Description
A well-defined asset inventory is essential for understanding the resources SolarWinds relies on and how each contributes to operational goals. This inventory includes **physical**, **digital**, and **human assets**, each playing a vital role in service delivery, data protection, and business continuity (National Institute of Standards and Technology, 2018).

By categorizing assets into these three groups, SolarWinds can better assess their **criticality** in the risk management process and ensure that **security measures align** with each asset’s function.

---

## 📋 Asset Inventory Overview
Below is the comprehensive **Asset Inventory Table** that categorizes all **physical, digital, and human assets** within SolarWinds Corporation, detailing their purpose and description.

🖼️ *Asset Inventory Table:*  
![Asset Inventory Table](Screenshot/1.1%20Asset%20Inventory%20Creation.png)

---

## 🧠 Asset Grouping Summary
### 🔹 Physical Assets
Includes servers, networking equipment, and endpoint devices that provide the core infrastructure for connectivity and operations.

### 🔹 Digital Assets
Comprises software platforms, data repositories, configuration files, intellectual property, and digital records essential to SolarWinds’ operations.

### 🔹 Human Assets
Encompasses IT staff, vendors, contractors, and support teams responsible for maintaining and securing all operational systems.

---

## 📘 Framework References
- **NIST SP 800-30** – Guide for Conducting Risk Assessments  
- **ISO/IEC 27001** – Information Security Management Systems  
- **CIS Controls v8** – Inventory and Control of Enterprise Assets

---

✅ *This section establishes the foundation for Component 1 by identifying critical assets and preparing for their categorization, CIA evaluation, and impact analysis in subsequent sections.*

---

# 🧱 Component 1.2 – Asset Categorization

## 🧠 Objective
To **categorize SolarWinds’ assets** based on their **criticality and business impact**, ensuring that high-value and critical infrastructure assets receive prioritized protection and appropriate security controls.

---

## 🧩 Description
The **Asset Categorization Table** organizes SolarWinds’ assets by importance, aligning with operational continuity and business value. Categorization enables **effective security prioritization**, ensuring that limited resources are directed toward the **most impactful assets** (United States Government Accountability Office, 2021).

Assets are divided into three main groups:
- **Critical Infrastructure / High Value** → Core business operations and customer-facing systems.
- **Moderate Value** → Supporting or internal systems with limited external exposure.
- **Variable Value** → Assets that fluctuate in importance depending on context or usage.

---

## 📋 Asset Categorization Table
Below is the categorized list of **physical, digital, and human assets**, including their descriptions and assigned priority categories.

🖼️ *Asset Categorization Table:*  
![Asset Categorization Table](Screenshot/1.2%20Asset%20categorization.png)

---

## 🧠 Category Overview
### 🔴 Critical Infrastructure / High Value
- **Servers** – Host mission-critical applications and store operational data.  
- **Networking Equipment** – Maintain secure connectivity across enterprise infrastructure.  
- **Orion Platform** – Core SolarWinds product used for network monitoring and management.  
- **Customer Records** – Contain sensitive client data and regulated information.  
- **SIEM Tools / Antivirus Software / Threat Intelligence** – Enable real-time monitoring, detection, and defense against cyber threats.  
- **Intellectual Property** – Proprietary code and designs essential to SolarWinds’ business.

### 🟠 Moderate Value
- **Endpoint Devices** – Employee workstations and mobile devices.  
- **Third-Party Applications** – Backup and support systems for secondary operations.  
- **Internal Documentation** – Guides internal procedures and workflows.  
- **Contractors / Support Teams** – Provide temporary or operational-level support.

### 🟡 Variable Value
- **Third-Party Vendors** – External service providers; criticality depends on contractual scope or system access level.

---

## 📘 Framework References
- **United States Government Accountability Office (2021)** – *Critical Infrastructure Protection: Progress and Challenges*  
- **NIST SP 800-30** – *Guide for Conducting Risk Assessments*  
- **ISO/IEC 27001** – *Information Security Management Systems*

---

✅ *This section builds upon the asset inventory by classifying assets that guide risk evaluation, control prioritization, and future impact analysis in Component 1.3 (CIA Triad Evaluation).*

---

# 🧱 Component 1.3 – CIA Triad Evaluation

## 🧠 Objective
To evaluate each SolarWinds asset across the **Confidentiality, Integrity, and Availability (CIA)** dimensions, assigning classification levels (**High**, **Medium**, **Low**) that reflect each asset’s criticality in maintaining data protection, accuracy, and uptime.

---

## 🧩 Description
The **CIA Triad** is a fundamental model in cybersecurity used to define an asset’s security requirements:
- **Confidentiality** – Ensures sensitive data is accessed only by authorized personnel.
- **Integrity** – Guarantees accuracy and consistency of data across systems.
- **Availability** – Ensures systems and information are accessible when needed.

By applying the CIA Triad, SolarWinds can tailor its controls to safeguard assets based on the **specific nature of the data and its operational role** (Shackleford, 2019).

---

## 📋 CIA Triad Evaluation Table
Below is the evaluation of **physical, digital, and human assets** based on their confidentiality, integrity, and availability requirements.

🖼️ *CIA Triad Evaluation Table:*  
![CIA Triad Evaluation Table](Screenshot/1.3%20CIA%20Trial%20Evaluation.png)

---

## 🔐 Key Insights
### 🔸 High Confidentiality Assets
- **Customer Records, Orion Platform, Intellectual Property, Threat Intelligence** – Contain sensitive data or proprietary information that must be encrypted and tightly controlled.

### 🔸 High Integrity Assets
- **SIEM Tools, Configuration Files, Servers** – Rely on accurate, untampered data to ensure consistent performance and compliance.

### 🔸 High Availability Assets
- **Servers, Networking Equipment, SIEM Tools, IT Staff** – Require continuous uptime to support operations, monitoring, and incident response.

### ⚙️ Moderate or Low-Classified Assets
- **Endpoint Devices, Internal Documentation, Contractors, Support Teams** – While essential for daily operations, their compromise has limited long-term impact on business continuity.

---

## 🧠 CIA Triad Summary
| CIA Principle | Focus | Example Assets | Key Controls |
|----------------|--------|----------------|---------------|
| **Confidentiality** | Data Protection | Customer Records, IP, Threat Intelligence | Encryption, MFA, Access Control |
| **Integrity** | Data Accuracy | SIEM Tools, Servers, Config Files | Change Management, Hash Verification |
| **Availability** | System Uptime | Servers, Networking Equipment, IT Staff | Redundancy, Backups, SLAs |

---

## 📘 Framework References
- **NIST SP 800-30** – *Guide for Conducting Risk Assessments*  
- **Shackleford, D. (2019)** – *Continuous Security Monitoring: Cybersecurity Controls for Advanced Threat Detection and Prevention (SANS Institute)*  
- **ISO/IEC 27001** – *Information Security Management Systems*

---

✅ *This section complements the asset categorization process by identifying the unique security requirements of each asset, providing a baseline for Business Impact Analysis in Component 1.4.*

---

# 🧱 Component 1.4 – Business Impact Analysis (BIA)

## 🧠 Objective
To perform a **Business Impact Analysis (BIA)** that quantifies the **potential financial, reputational, and operational consequences** of a cybersecurity incident impacting SolarWinds’ assets. The goal is to determine the **likelihood, impact severity, and overall risk level** for each asset category.

---

## 🧩 Description
The **Business Impact Analysis** identifies how disruptions to critical assets can affect SolarWinds’ business operations, customer trust, and regulatory compliance.  
By assigning **impact values** and **likelihood ratings**, SolarWinds can prioritize which assets require the strongest protection and continuity planning.

Each asset is analyzed using:
- **Impact of Loss / Compromise** – Describes potential damage to operations or customers.
- **Likelihood of Incident** – Rated as High, Medium, or Low.
- **Overall Risk Level** – Derived from combining impact and likelihood to determine criticality.

---

## 📊 Overall Business Impact Analysis Table
🖼️ *Overall BIA Table:*  
![Business Impact Analysis](Screenshot/1.4%20Business%20Impact%20Analysis.png)

This table provides a consolidated overview of **physical, digital, and human assets** along with their assessed risk levels.

---

## 🧩 Individual BIA Summaries
### 🔹 Physical Assets
| Asset | Impact of Loss / Compromise | Likelihood | Risk Level |
|--------|------------------------------|-------------|-------------|
| **Servers** | Significant operational disruption | Medium | High |
| **Networking Equipment** | Loss of connectivity | High | High |
| **Endpoint Devices** | Data leakage due to unauthorized access | Medium | Moderate |

📈 *Insight:* Servers and networking equipment are critical for maintaining uptime. A failure could lead to major service disruptions and reputational loss.

---

### 🔹 Digital Assets
| Asset | Impact of Loss / Compromise | Likelihood | Risk Level |
|--------|------------------------------|-------------|-------------|
| **Orion Platform** | Reduced customer satisfaction and service disruption | High | Critical |
| **SIEM Tools** | Increased vulnerability to undetected threats | Medium | High |
| **Antivirus Software** | Risk of malware infection | Medium | Moderate |
| **Third-party Applications** | Operational inefficiencies and delays | Medium | Moderate |
| **Customer Records** | Loss of sensitive data; regulatory penalties | High | Moderate |
| **Configuration Files** | System misconfigurations and outages | Medium | High |
| **Intellectual Property** | Exposure of proprietary code; loss of advantage | Medium | High |
| **Threat Intelligence** | Delayed response to emerging threats | Medium | Moderate |
| **Internal Documentation** | Minor operational impact | Low | Low |

📈 *Insight:* The **Orion Platform** has the highest criticality because it directly affects customer operations. **Customer Records** also pose significant compliance and reputational risks.

---

### 🔹 Human Assets
| Asset | Impact of Loss / Compromise | Likelihood | Risk Level |
|--------|------------------------------|-------------|-------------|
| **IT Staff** | Critical operational and security functions impacted | High | High |
| **Third-party Vendors** | Dependency on external services; third-party breaches | Medium | High |
| **Contractors** | Delay in projects; operational delays | Medium | Moderate |
| **Support Teams** | Customer service continuity disrupted | High | High |

📈 *Insight:* Loss of **IT staff** or **support teams** could severely hinder incident response and system recovery, raising both operational and reputational risk.

---

## 🧮 Calculation Example
### Example: Orion Platform
**Assumptions:** Core product; a critical platform for network monitoring and IT management used by multiple clients.


**Impact Categories:** Financial Loss, Reputational Damage, Operational Disruption.


**Estimated Impact Values:**
• Financial Loss: $3,000,000 (includes potential compensation to clients and legal expenses)
• Reputational Damage: $5,000,000 (substantial impact on customer trust and potential loss of future clients)
• Operational Disruption: $1,500,000 (costs related to downtime and recovery efforts)


**Likelihood of Incident:** 10% (1 in 10 chances of a significant disruption or breach annually)


**Impact Calculation:**
• Total Impact = Financial Loss + Reputational Damage + Operational Disruption
• Total Impact = $3,000,000 + $5,000,000 + $1,500,000 = **$9,500,000**


**Annual Expected Loss Calculation:**
• Annual Expected Loss = Total Impact × Likelihood of Incident
• Annual Expected Loss = $9,500,000 × 0.10 = **$950,000**


🖼️ *Calculation Summary:*
![BIA Calculation Example](Screenshot/1.4%20Business%20Impact%20Analysis%20Digital%20Asset%201.png)

---

## 🧠 Key Insights
- **High-priority focus:** Orion Platform, Servers, Networking Equipment, IT Staff, and Customer Records.
- **Risk drivers:** Operational continuity, customer trust, and regulatory compliance.
- **Mitigation strategy:** Implement redundancy, enforce access control, enhance vendor security, and establish strong incident response planning.

---

## 📘 Framework References
- **NIST SP 800-30** – *Guide for Conducting Risk Assessments*  
- **ISO/IEC 27005** – *Information Security Risk Management*  
- **SANS Institute (2021)** – *Critical Security Controls for Effective Cyber Defense*  
- **Gordon, Loeb, & Zhou (2011)** – *The Impact of Information Security Breaches*

---

✅ *This section quantifies the potential impacts of cyber incidents across all asset categories, providing the foundation for cost-effective risk treatment strategies in Component 1.5.*
---

# 🧱 Component 1.5 – Data Sensitivity and Value Assessment

## 🧠 Objective
To evaluate and classify SolarWinds’ data assets based on their **sensitivity, value, and potential business impact** in the event of compromise. This ensures that security measures are prioritized according to the **criticality of the data handled** by each asset.

---

## 🧩 Description
This assessment determines how valuable and sensitive each data type is to SolarWinds’ business operations, compliance obligations, and reputation. Assets handling highly sensitive information, such as **customer records** or **intellectual property**, are identified for enhanced security protections including encryption, data loss prevention (DLP), and strict access controls.

Data is evaluated using four key dimensions:
- **Data Type:** Category of information being stored or processed.
- **Sensitivity Level:** Importance of data confidentiality (Very High, High, Medium, Low).
- **Description:** Context of how the data supports operations or compliance.
- **Value Assessment:** The potential financial, reputational, or operational impact if compromised.

---

## 📋 Data Sensitivity and Value Assessment Table
🖼️ *Data Sensitivity Table:*  
![Data Sensitivity Table](Screenshot/1.5%20Data%20Sensitivity%20and%20Value%20Assessment.png)

---

## 🔐 Sensitivity Analysis Summary
### 🔴 Very High Sensitivity
- **Customer Records** – Contain personally identifiable information (PII) and client details; high regulatory and reputational risk if exposed.

### 🟠 High Sensitivity
- **Intellectual Property** – Proprietary code and trade secrets critical for competitive advantage.  
- **Threat Intelligence** – Informs proactive defense; exposure could compromise detection capabilities.  
- **Financial Data** – Required for compliance and business decisions; loss can result in penalties.  
- **Incident Response Logs** – Contain forensic data; exposure may reveal internal weaknesses.  
- **Employee Records** – Contain personal and professional information subject to privacy laws.

### 🟡 Medium Sensitivity
- **Configuration Files** – Misconfigurations could disrupt operations.  
- **Vendor Agreements** – Affect continuity and third-party compliance.  
- **Network Traffic Logs** – Valuable for monitoring but less sensitive.

### 🟢 Low Sensitivity
- **Internal Documentation** – Internal policies and manuals with minimal confidentiality requirements.

---

## 📈 Value Assessment Highlights
- **High-Value Data:** Customer Records, Financial Data, Intellectual Property, and Threat Intelligence are prioritized for protection under ISO 27001 Annex A controls.  
- **Moderate-Value Data:** Network and Vendor information require secure management but limited investment compared to mission-critical data.  
- **Low-Value Data:** Operational documents are protected under general access controls without advanced encryption.

---

## 📘 Framework References
- **NIST SP 800-60** – *Guide for Mapping Types of Information and Information Systems to Security Categories*  
- **ISO/IEC 27001 Annex A** – *Information Classification and Handling*  
- **GDPR (2016)** – *General Data Protection Regulation*  
- **Australian Privacy Principles (APPs)** – *Privacy Act 1988*

---

✅ *This final component concludes the asset evaluation phase by mapping each data type’s sensitivity and value, forming the foundation for cost-effective risk treatment strategies and control prioritization in the next phase of the Cybersecurity Risk Management Program.*
