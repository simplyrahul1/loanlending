# Consumer Finance Loan Default Analysis
> A data-driven approach to credit risk analysis combining traditional lending metrics with modern fintech perspectives

## Personal Context
With 25 years of technology leadership experience across global financial markets, including:
- International banks and traditional finance trading firms
- Hedge funds and cryptocurrency trading platforms (MF/HFT)
- Infrastructure, DevSecOps, and SRE leadership roles
- Global exposure: Singapore (16 years), New York (2 years), Mumbai (6 years)

## Table of Contents
* [General Information](#general-information)
* [Business Problem](#business-problem)
* [Detailed Analysis](#detailed-analysis)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
This project analyzes lending patterns and default risks for a consumer finance company specializing in urban lending. The analysis covers 39,717 loans totaling ₹445,602,650, combining traditional risk assessment with modern data-driven approaches.

### Business Problem
The company faces two critical risk types:
- **False Negatives**: Rejecting good borrowers (loss of business)
- **False Positives**: Approving high-risk borrowers (financial loss)

The analysis aims to identify patterns in consumer and loan attributes that indicate default risk, enabling better lending decisions.

## Detailed Analysis

### 1. Income and Verification Risk Patterns
```
Income Band Analysis:
              Count  Pct_Total  Avg_Loan_Amt  Default_Rate  Avg_Int_Rate
Very High    7,755     19.53    15,964.26       10.55         12.51
Very Low     7,969     20.06     6,640.28       17.87         11.69
```
Key Findings:
- Higher income bands show better repayment (Default rate delta: 7.32%)
- Verified loans show higher default rates (16.01%) than unverified (12.66%)
- DTI ratio correlates with verification level

### 2. Grade-Based Portfolio Analysis
```
Grade Distribution:
Grade  Ln_Cnt  Ln_Cnt_%  Av_L_Amt   Def_%  av_inr_r_%
A      10,085   25.39     ₹8,625     5.97     7.34   
G         316    0.80    ₹20,227    31.96    21.40   
```
Risk Progression:
- Clear risk-based pricing structure
- Higher grades get larger loans but better success rates
- Grade A-C compose 76.04% of portfolio

### 3. Purpose Risk Stratification
```
Highest Default Rates:            Lowest Default Rates:
Small business:    25.98%        Credit card:    10.57%
Renewable energy:  18.45%        Car loans:      10.33%
Educational:       17.23%        Wedding loans:  10.14%
```

### 4. Employment and Housing Impact
```
Top Employer Analysis:
Employer          Count  Default_Rate  Avg_Income
IBM                66      13.64%     115,943.95
Bank of America   109      18.35%      64,861.84
Wells Fargo        54       7.41%      70,666.67
```
- Mortgage holders show lowest default rates (13.18%)
- Technology sector employees show higher income stability
- Employment length shows mixed correlation with defaults

## Technologies Used
- Python - version 3.9
- Pandas - version 1.3.0
- Numpy - version 1.21.0
- Seaborn - version 0.11.1
- Matplotlib - version 3.4.2

## Conclusions

### 1. Risk Segmentation Strategy
- Implement stricter verification for high-risk purposes
- Consider purpose-grade combination pricing
- Focus on debt consolidation quality (46.93% of loans)

### 2. Default Risk Mitigation
- Prioritize higher income borrowers despite larger loan amounts
- Use home ownership as stability indicator
- Implement automated verification for known employers

### 3. Portfolio Optimization
- Balance grade distribution
- Purpose-specific risk limits
- Dynamic interest rate adjustment
- Real-time risk monitoring system

### 4. Process Automation
- Risk-based pricing engine
- Automated employer verification
- Purpose-specific underwriting criteria
- Portfolio risk monitoring dashboard

## Implementation Recommendations
1. **Risk Assessment Framework**
   - Multi-factor scoring system
   - Purpose-based risk weightage
   - Grade-based pricing optimization

2. **Credit Loss Prevention**
   - Enhanced verification for high-risk purposes
   - Dynamic interest rate adjustment
   - Purpose-specific loan term optimization

3. **Monitoring System**
   - Real-time portfolio risk tracking
   - Automated risk alerts
   - Performance analytics dashboard

## Contact
Created by [Rahul Sinha] - Fintech Risk Analytics Professional
- 25 years of Financial Technology experience
- Global Experience: Singapore, New York, Mumbai
- Expertise: Infrastructure, DevSecOps, SRE, Trading Systems

