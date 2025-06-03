# drop-model-fashion-mmm

FASHION RETAIL MMMM

## 🎯 Executive Statement

Club 1984 is a drop-based fashion brand that thrives on cultural relevance, anticipation, and tightly controlled product releases. With a growing reliance on paid channels (Meta Ads) and owned media (Klaviyo email), the business faces a critical challenge: how to attribute long-lag conversions and determine which marketing actions truly move the needle.

This project delivers a Bayesian Marketing Mix Model (MMM) to provide clear, interpretable insights into the effectiveness of marketing investments. By modeling delayed conversions, accounting for campaign buildup ahead of drops, and quantifying uncertainty, the model empowers Club 1984 to:

- Allocate media spend based on marginal ROI
- Distinguish brand-building vs. performance activity
- Forecast demand across future drops with greater confidence

---

## 🧩 Problem Statement

Marketing performance at Club 1984 is difficult to evaluate due to the brand’s unique sales model:

- Customer signups often occur **weeks before the first purchase**
- Sales are **clustered into intense drop events**
- Traditional attribution models ignore **lag, decay, and hype dynamics**

This model addresses four key problems:

1. **Attribution Lag**  
   Marketing activity must be matched to sales that occur later.

2. **Drop-Based Conversion Windows**  
   Most revenue occurs within short bursts, driven by pre-launch momentum.

3. **Channel Investment Uncertainty**  
   It’s unclear how much value is created by Meta spend vs. email flows.

4. **Scaling Risk**  
   Without marginal ROI estimates, it’s difficult to scale spend without inefficiency or waste.

The model answers:  
> *“What is the incremental return per £1 invested in each channel — and how does that change by drop?”*

