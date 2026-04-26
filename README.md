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



# FinTech vs. Banking: Impact Analysis

This document summarizes the key points and formulas from a lecture on how **FinTech** affects **traditional banking**, focusing on key financial metrics, regulatory challenges, and strategic responses to disruptive technologies. 

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

\[
\text{PER}_{b,c,t} = \alpha + \beta_1 \cdot \text{FinTechBusinessModel}_{c,t} + \gamma \cdot X_{b,c,t} + \delta \cdot W_{c,t} + \text{Other}_{b,c,t}
\]

Where:
- \(\text{PER}_{b,c,t}\) = Bank performance measure (ROE, ROA, NIM, NONIC, CTI).
- \(\text{FinTechBusinessModel}_{c,t}\) = Logarithm of the country-level fintech transaction volumes for P2P lending and balance sheet lending.
- \(X_{b,c,t}\) = Bank-specific controls (size, equity-to-assets ratio).
- \(W_{c,t}\) = Country-level controls (GDP growth, inflation, policy rate, concentration).
- \(\text{Other}_{b,c,t}\) = Bank fixed effects and error terms.

---

## 4. Summary of Key Metrics for Payment Firms and Commercial Banks

#### **Table: Market Performance and Key Metrics (2000s to 2020/21)**

| Metric | Payment Firms (2000s) | Payment Firms (2010s) | Payment Firms (2020/21) | Commercial Banks (2000s) | Commercial Banks (2010s) | Commercial Banks (2020/21) |
|--------|----------------------|-----------------------|-------------------------|--------------------------|--------------------------|---------------------------|
| **Market Cap ($m)** | 145,957 | 598,772 | 1,606,677 | 1,210,550 | 1,500,518 | 1,959,797 |
| **Assets ($m)** | 249,362 | 508,335 | 829,639 | 8,497,946 | 12,992,766 | 18,198,884 |
| **Equity ($m)** | 37,925 | 110,937 | 225,631 | 688,649 | 1,298,929 | 1,579,632 |
| **Revenue ($m)** | 62,337 | 133,310 | 200,744 | 604,403 | 643,196 | 677,937 |
| **Net Income ($m)** | 6,019 | 23,237 | 36,960 | 23,237 | 69,626 | 164,112 |
| **ROA (%)** | 2.38 | 4.54 | 4.44 | 0.90 | 0.86 | 0.89 |
| **ROE (%)** | 15.99 | 21.10 | 16.32 | 10.93 | 8.58 | 10.37 |
| **Revenue Growth (%)** | 4.94 | 8.84 | 8.87 | 8.51 | 1.63 | -5.11 |

---

## 5. Largest Firms by Subsector (2021)

- **Top Payment Firms**:  
  - **Visa**: $459 billion  
  - **Mastercard**: $352 billion  
  - **PayPal**: $220 billion

- **Top Commercial Banks**:  
  - **JPMorgan Chase**: $466 billion  
  - **Bank of America**: $359 billion  
  - **Wells Fargo**: $186 billion

These companies represent the leaders in their respective sectors, showing the scale at which both fintech and traditional banks operate.

---

## 6. Conclusion

The session emphasizes how **FinTech** disrupts **banking** by targeting specific functions such as **lending** and **payments**, often eroding **bank profitability** (via increased costs and competition). However, **collaboration** between banks and fintechs is also becoming increasingly important. The impact on **performance measures** like **ROE** and **ROA** depends on whether the fintech is acting as a **complement** or **substitute** to the bank's business model.

---

### **Important Concepts and Formulas:**

- **Complementary vs. Substitution Hypothesis**:
  - **Complementary**: Fintech attracts customers to banks, increasing bank income.
  - **Substitutes**: Fintech draws customers away, reducing bank income and profitability.
  
- **Impact of FinTech Business Models on Bank Performance**:
  - **P2P Lending**: Reduces profitability measures (ROE, ROA, NIM), but increases non-interest income.
  - **Balance Sheet Lending**: Less impactful than P2P, but still reduces key profitability measures.
  
- **Bank Performance Measurement**:
  - **Formula**:  
    
    $\text{PER}_{b,c,t} = \alpha + \beta_1 \cdot \text{FinTechBusinessModel}_{c,t} + \gamma \cdot X_{b,c,t} + \delta \cdot W_{c,t} + \text{Other}_{b,c,t}$
  - Key metrics: **ROE**, **ROA**, **NIM**, **NONIC**, **CTI**.

If you have further questions or need additional clarifications, feel free to ask!

