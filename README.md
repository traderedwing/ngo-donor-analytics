# NGO Donor Analytics & Retention Strategy

## Problem

The organization experiences unstable revenue driven by low donor retention and inefficient marketing allocation.

Main challenges:
- heavy dependence on one-time donations
- high acquisition costs
- lack of visibility into campaign efficiency
- weak donor retention strategy

---

## Business Goals

- Increase donor retention
- Identify the most effective acquisition channels
- Optimize campaign costs
- Improve long-term fundraising stability

---

## Key Business Questions

1. Which channels bring the most valuable donors?
2. What is the donor retention rate?
3. Which campaigns have the best ROI?
4. How do donations convert into real impact?
5. Who are our high-value donors?

---

## Methodology

### Data Processing
- Data cleaning and validation
- Missing value handling
- Feature engineering
- Date transformation
- Cohort preparation

### Exploratory Analysis
- Revenue trend analysis
- Channel performance analysis
- Donor segmentation
- Campaign ROI evaluation
- Social impact analysis

### Statistical Analysis
- Cohort retention analysis
- Donor lifetime value (LTV)
- Cost-per-person analysis
- A/B test simulation

### Dashboard Development
- Star schema data model
- DAX measures
- Interactive Power BI dashboard

---

## Key Insights

### Revenue Stability
Revenue shows strong volatility and dependence on large one-time donations.

This indicates weak recurring donor behavior and low financial predictability.

---

### Channel Performance
Google Ads generates the highest-quality donors with strong LTV performance but currently operates at low scale.

Facebook Ads brings volume but lower donor quality.

---

### Retention
Retention drops sharply after the first donation.

More than 85% of donors do not return after their initial contribution.

This suggests that the organization focuses heavily on acquisition rather than donor retention.

---

### High-Value Donors
A small segment of donors generates a disproportionate share of total revenue.

High-value donors:
- donate more frequently
- have significantly higher LTV
- are mostly acquired organically or via referrals

---

### Campaign ROI
Food campaigns demonstrate the most stable ROI.

Education campaigns produce the highest individual ROI results.

Emergency campaigns are significantly less efficient.

---

### Impact Efficiency
Most campaigns achieve strong coverage with low cost per person.

However, several campaigns show extremely poor efficiency and require audit or restructuring.

---

## A/B Testing

A simulated A/B test was conducted to evaluate the impact of a donor retention strategy.

### Results
- Repeat donation rate increased by 145%
- Strongest uplift observed among mid- and high-value donors

### Conclusion
Retention-focused engagement strategies may significantly improve fundraising sustainability.

---

## Dashboard Overview

The Power BI dashboard contains:

### KPI Layer
- Total Donations
- ROI
- People Helped
- Retention Rate

### Analytical Layer
- LTV by Acquisition Channel
- Cohort Retention Heatmap
- ROI vs Cost Scatter Plot
- Top 10 High-Value Donors

---

## Dashboard Preview

![Dashboard](screenshots/dashboard.png)

---

## Business Recommendations

### 1. Focus on Retention
Retention should become the primary growth strategy instead of aggressive acquisition.

---

### 2. Scale High-Quality Channels
Increase investment in Google Ads to acquire higher-value donors at scale.

---

### 3. Prioritize VIP Donors
Implement personalized communication strategies for high-value donors.

Examples:
- donor reports
- exclusive updates
- personalized outreach

---

### 4. Optimize Campaign Portfolio
Reduce investment in inefficient campaigns and scale successful campaign models.

---

## Tech Stack

### Python
- pandas
- numpy
- matplotlib
- statsmodels

### BI & Visualization
- Power BI
- DAX
- Data Modeling

---

## Project Structure

```bash
ngo-donor-analytics/
│
├── data/
├── notebook/
├── dashboard/
├── presentation/
├── screenshots/
├── README.md
```

---

## Outcome

This project demonstrates:
- end-to-end analytical workflow
- business-oriented thinking
- dashboard development skills
- statistical analysis
- ability to translate data into actionable recommendations

---
