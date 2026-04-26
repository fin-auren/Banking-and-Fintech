# Banking-and-Fintech
# FinTech vs. Banking: Impact Analysis


## 1. MIT Sloan Disruptive Technology Response Matrix: Fight or Flight

The **MIT Sloan Disruptive Technology Response Matrix** categorizes responses to disruptive innovation based on **two factors**: 

- **Motivation to Respond** (high or low)
- **Ability to Respond** (high or low)

This leads to four possible strategic responses:

#### Responses in the Matrix:
1. **High Motivation, High Ability**:
   - **Adopt & Separate**: Embrace the disruptive technology but keep it separate from existing operations.
2. **High Motivation, Low Ability**:
   - **Adopt & Keep Internal**: Try to integrate the technology internally despite limitations.
3. **Low Motivation, High Ability**:
   - **Attack Back**: Disrupt the disruptor — aggressively compete back with new innovations.
4. **Low Motivation, Low Ability**:
   - **Embrace the Disruption and Scale It**: Accept the disruption and attempt to scale up the new technology.

---

## 2. Impact of FinTech on Bank Performance

### **Transmission Channels**
The following table outlines how different FinTech business models affect bank performance:

- **ROE (Return on Equity)**
- **ROA (Return on Assets)**
- **NIM (Net Interest Margin)**
- **NONIC (Non-Interest Income)**
- **CTI (Cost to Income)**

These are key financial metrics that can be positively or negatively impacted by FinTech, depending on whether FinTechs act as **complements** (beneficial to banks) or **substitutes** (take customers away from banks).

---

## 3. FinTech Models and Their Impact on Bank Performance

#### **Table: Effect of FinTech Business Models on Bank Performance**

- **FinTech**:
  - Across all sectors, FinTech businesses (like P2P lending and Balance Sheet lending) tend to **reduce ROE, ROA, and NIM**, while increasing **NONIC** and **CTI**.
  
- **P2P Lending (Peer-to-Peer Lending)**:
  - Negative impact on **ROE, ROA, and NIM**.
  - Significant increase in **CTI**, indicating high operational costs for banks in the presence of such models.

- **Balance Sheet Lending**:
  - Slightly less negative impact on **ROE and ROA** compared to P2P lending.
  - Slightly smaller effect on increasing **CTI**.

### **Key Formulae from the Model**:
- **Bank Performance Measure** (PER_b,c,t) is impacted by:
  - **FinTechBusinessModel_c,t**: This variable is the **log of country-level FinTech transaction volumes**, and the two main business models are:
    - **P2P Lending**
    - **Balance Sheet Lending**

The formula for measuring the impact of FinTech on bank performance is:

```plaintext
PER_b,c,t = α + β1 * FinTechBusinessModel_c,t + γ * X_b,c,t + δ * W_c,t + Other_b,c,t'''


| Metric                 | Payment Firms (2000s) | Payment Firms (2010s) | Payment Firms (2020/21) | Commercial Banks (2000s) | Commercial Banks (2010s) | Commercial Banks (2020/21) |
| ---------------------- | --------------------- | --------------------- | ----------------------- | ------------------------ | ------------------------ | -------------------------- |
| **Market Cap ($m)**    | 145,957               | 598,772               | 1,606,677               | 1,210,550                | 1,500,518                | 1,959,797                  |
| **Assets ($m)**        | 249,362               | 508,335               | 829,639                 | 8,497,946                | 12,992,766               | 18,198,884                 |
| **Equity ($m)**        | 37,925                | 110,937               | 225,631                 | 688,649                  | 1,298,929                | 1,579,632                  |
| **Revenue ($m)**       | 62,337                | 133,310               | 200,744                 | 604,403                  | 643,196                  | 677,937                    |
| **Net Income ($m)**    | 6,019                 | 23,237                | 36,960                  | 23,237                   | 69,626                   | 164,112                    |
| **ROA (%)**            | 2.38                  | 4.54                  | 4.44                    | 0.90                     | 0.86                     | 0.89                       |
| **ROE (%)**            | 15.99                 | 21.10                 | 16.32                   | 10.93                    | 8.58                     | 10.37                      |
| **Revenue Growth (%)** | 4.94                  | 8.84                  | 8.87                    | 8.51                     | 1.63                     | -5.11                      |
