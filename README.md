# 📊 Marketing Mix Modeling (MMM): COVID-19 Impact Analysis  
*ROI Optimization & Media Performance Attribution (2019-2020)*

---

## 🎯 Project Overview

This project applies Marketing Mix Modeling (MMM) to analyze the impact of media channels, promotional strategies, and macroeconomic factors on sales performance during the COVID-19 pandemic for a company called Ekimetrics. The Presentation was presented to senior members in the Ekimetrics Team . Using Python for statistical modeling (statsmodels, pandas, NumPy) combined with advanced attribution techniques and Excel for visualization, we evaluated $15M+ in marketing spend across 8 media channels and 3 promotion types to deliver data-driven recommendations for budget reallocation and ROI optimization.

The analysis reveals critical insights into digital media's resilience during market disruption, the declining effectiveness of traditional channels, and strategic opportunities to maximize marketing efficiency in uncertain economic conditions.

📌 *Group project completed for MKT 6300: Advanced Marketing Analytics*

---

## 💼 Business Problem

**Context:** A consumer brand experienced a $186.6M sales decline (–34%) from 2019 to 2020 during the COVID-19 pandemic, with total 2020 sales of $641.8M (up from $189.6M in 2019 when including baseline growth).

**Challenge:** Leadership needed to understand:
- Which marketing channels maintained effectiveness during crisis conditions?
- How did promotional strategies perform pre-, during, and post-COVID?
- Where should marketing budget be reallocated to maximize ROI?
- What role did external macroeconomic factors play in performance changes?

**Objective:** Conduct comprehensive marketing mix decomposition to identify high-performing channels, quantify COVID impact, and provide actionable budget reallocation strategies.

---

## 📊 Methodology

### **Marketing Mix Modeling Framework**

**1. Performance Decomposition**
- **Baseline Sales:** Organic demand driven by brand equity and macroeconomic factors
- **Media Contribution:** Incremental sales from paid advertising across 8 channels
- **Promotional Contribution:** Sales lift from promotional tactics (Samples, GWP, Product Launches)
- **COVID Impact:** Quantified pandemic-related sales changes ($27.8M incremental, $60.2M total loss)

**2. Time Period Segmentation**
- **Pre-COVID:** 2019 baseline performance
- **COVID Period:** March–July 2020 (peak pandemic disruption)
- **Post-COVID:** August–December 2020 (recovery phase)

**3. Attribution Analysis**
- ROI calculation by channel: `(Incremental Sales - Media Spend) / Media Spend`
- Contribution percentage: Channel sales impact as % of total incremental sales
- Marginal efficiency: ROI trends with spend level changes

**4. Gap Analysis**
- Sales change decomposition: 2019 vs. 2020 waterfall analysis
- Driver identification: Media, promotions, macro factors, COVID impact
- Variance explanation: Quantifying each lever's role in –$186.6M decline

---

## 📈 Key Findings

### 🔹 Media Performance: Digital Dominance

**Top Performers (ROI > 10):**

| Channel | 2019 ROI | 2020 ROI | COVID ROI | Contribution | Status |
|---------|----------|----------|-----------|--------------|--------|
| **Social Media** | 11.6 | 11.3 | 15.4 | $16.3M → $21.5M | ⭐ Champion |
| **Search** | 10.5 | 8.3 | 8.8 | $11M+ annually | ⭐ Champion |
| **Outdoor** | 0.0 | 36.4 | — | — | 🔍 Anomaly |

**Mid-Tier Performers:**

| Channel | 2019 ROI | 2020 ROI | Trend | Insight |
|---------|----------|----------|-------|---------|
| **Online Video** | — | Declined | ↓ | Saturation concern despite higher spend |
| **Display** | 2.8 | 4.5 | ↑ | Improvement from optimization efforts |

**Underperformers:**

| Channel | 2019 ROI | 2020 ROI | Budget | Recommendation |
|---------|----------|----------|--------|----------------|
| **TV** | Low | 1.5 | High | Consider reallocation |
| **Print** | Low | Low | Substantial | Reduce investment |

**Critical Insight:** Digital channels (Search, Social, Online Video) delivered superior ROI stability through COVID, outperforming traditional media by 3-5× in efficiency.

---

### 🔹 Promotional Strategy Performance

**Contribution Analysis (2019 → 2020):**

| Promotion Type | 2019 Share | 2020 Share | Contribution Change | Performance |
|----------------|-----------|-----------|---------------------|-------------|
| **Samples** | 64% ($9.9M) | 68% ($38.2M) | +286% | 🟢 Strong growth |
| **GWP (Gift with Purchase)** | 27% ($4.2M) | 27% ($15.0M) | +257% | 🟢 Consistent |
| **Product Launch** | 9% | 5% | Declined despite spend | 🔴 Underperforming |

**During COVID Period:**
- GWP contribution dropped from $15.0M to $2.5M (–83%) despite maintaining 24% share
- Samples maintained dominance but faced efficiency challenges
- Overall promotion-driven sales fell from 10% (2019) to 6% (2020) of total sales

**Strategic Shift:** Brand moved away from heavy discounting toward margin protection and long-term value building.

---

### 🔹 COVID-19 Impact Quantification

**Sales Decline Breakdown (–$186.6M total):**

| Factor | Impact | % of Decline | Explanation |
|--------|--------|--------------|-------------|
| **Macroeconomic Factors** | –$110.6M | 59% | Category decline, consumer behavior shifts |
| **COVID Direct Impact** | –$60.2M | 32% | Pandemic disruptions, store closures |
| **Media & Promo Changes** | –$16M | 9% | Channel reallocation, promotional retreat |

**Unexpected Positive:** COVID drove $27.8M in *incremental* sales through:
- Digital adoption acceleration
- E-commerce channel growth
- Changed consumer purchasing patterns

**Net Effect:** When considering indirect economic impacts, pandemic-driven factors explain **>90% of total sales loss**, while marketing levers remained relatively stable.

---

### 🔹 Sales Decomposition: Baseline vs. Marketing Levers

**2019 Performance:**
- **Baseline (Macro):** 78% of sales ($147.6M) — organic brand strength
- **Media Contribution:** 12% ($22.8M) — paid advertising impact
- **Promotions:** 10% ($19.0M) — tactical sales lift

**2020 Performance:**
- **Baseline (Macro):** 80% of sales ($513.4M) — strengthened organic pull
- **Media Contribution:** 14% ($89.9M) — increased paid media efficiency
- **Promotions:** 6% ($38.5M) — strategic reduction in discounting

**Key Takeaway:** The brand's strong baseline (78% → 80%) provided stability during crisis. Media growing (+2pp) and promotions declining (–4pp) signals a strategic pivot toward sustainable, margin-accretive growth.

---

### 🔹 Deep Dive 1: Pre-COVID vs. COVID Media Shift

**Digital Media Evolution:**

| Period | Digital Spend | Digital ROI | Traditional Spend | Traditional ROI |
|--------|--------------|-------------|-------------------|----------------|
| **Pre-COVID (2019)** | $5.2M | 6.8 | $8.2M | 3.6 |
| **COVID (Mar-Jul 2020)** | — | 15.4 (Social) | — | — |
| **Post-COVID (Aug-Dec 2020)** | $6.8M | 6.2 | $3.2M | 2.8 |

**Investment Efficiency:**
- Digital spend increased 31% ($5.2M → $6.8M), ROI decreased slightly (6.8 → 6.2) but remained **2.2× more efficient** than traditional
- Traditional spend decreased 61% ($8.2M → $3.2M), ROI also fell (3.6 → 2.8)
- **Social & Search achieved 15.4 and 8.8 ROI during COVID**, proving crisis resilience

**Weakest Performers Post-COVID:**
- **TV ROI: 1.5** — Lowest efficiency despite high spend
- **Online Video ROI: 2.1** — Potential saturation or targeting issues

---

### 🔹 Deep Dive 2: ROI Scorecard Analysis

**Consistent Champions (2019 & 2020):**
- **Search & Social:** ROI >10 both years with moderate spend = exceptional cost efficiency
- Combined delivered $32.5M+ contribution with <30% of media budget

**Dramatic Turnaround:**
- **Outdoor:** 0.0 ROI (2019) → 36.4 ROI (2020)
- ⚠️ Anomaly warrants data verification — potential measurement error or true breakthrough

**Budget vs. Performance Mismatch:**
- **TV & Print:** Absorbed substantial budgets, delivered low ROI both years
- Traditional channels no longer justify investment without stronger returns

**Improvement Story:**
- **Display:** 2.8 ROI (2019) → 4.5 ROI (2020) = +61% efficiency gain
- Suggests optimization efforts (targeting, creative, programmatic) are working

---

## 💡 Strategic Recommendations

### **1. Media Budget Reallocation (Immediate Priority)**

**Increase Investment:**
- ✅ **Social Media:** Scale from current to capture full demand (11+ ROI justifies expansion)
- ✅ **Search:** Maintain/grow investment (proven 8-10 ROI stability)
- ✅ **Display:** Continue optimization momentum (improving 2.8 → 4.5 ROI)

**Reduce/Reallocate:**
- ❌ **Print:** Consistent underperformance — redirect 50-75% of budget
- ❌ **TV:** Low ROI (1.5) despite high spend — reduce by 30-40%
- ⚠️ **Online Video:** Monitor saturation — freeze spend until efficiency improves

**Investigate:**
- 🔍 **Outdoor:** Verify 36.4 ROI anomaly — if real, significant opportunity

**Projected Impact:** Reallocating $2-3M from traditional to digital could yield $20-30M incremental sales based on current ROI differentials.

---

### **2. Promotional Strategy Optimization**

**Double Down on Winners:**
- 📦 **Samples:** Prioritize investment (68% contribution, strong consumer response)
  - Scale sampling programs in high-conversion markets
  - Integrate with digital acquisition funnels
  - Target new customer acquisition vs. retention

**Maintain Strategic Investment:**
- 🎁 **GWP:** Contribution tripled YoY despite stable share
  - Test higher-value gift tiers to boost AOV
  - Align GWP with product launches for amplification
  - Monitor COVID-period 83% decline to understand drivers

**Reevaluate or Redesign:**
- 🚀 **Product Launch Promos:** Share declined (9% → 5%) despite spend
  - Audit execution effectiveness (timing, channels, messaging)
  - Consider shifting to awareness-focused media vs. promotional discounts
  - Test product launch bundled with samples instead of standalone promos

---

### **3. COVID-Era Learnings Integration**

**Institutionalize Crisis Response Playbook:**
- 📱 **Digital Acceleration:** Social ROI jumped to 15.4 during COVID — maintain agile channel mix
- 🏠 **E-commerce Enablement:** $27.8M incremental sales show opportunity — invest in owned digital
- 🎯 **Targeted Promotions:** Adapt promo formats for changing consumer contexts (stay-at-home, value-seeking)

**Build Macro Monitoring Capability:**
- 📊 Establish cross-functional forecasting team tracking:
  - Employment rates, inflation, consumer confidence indices
  - Category growth trends and competitive dynamics
  - Scenario planning for recession/recovery cycles
- 🔄 Quarterly reviews to adjust promotional intensity and channel mix proactively

**Prepare Contingency Budgets:**
- Allocate 10-15% of annual media budget as "flex reserve"
- Pre-approved scenarios for rapid reallocation during market shifts
- Test-and-learn frameworks for emerging channels/tactics

---

### **4. Long-Term Strategic Priorities**

**Strengthen Baseline (Currently 80% of Sales):**
- Brand-building campaigns to sustain organic pull
- Customer retention programs to protect loyal base
- Product innovation to maintain category leadership

**Optimize Marginal Efficiency:**
- Conduct diminishing returns analysis on Search & Social (where to cap spend?)
- Test incrementality with geo-holdout experiments
- Build proprietary MMM capability for ongoing optimization

**Reduce Traditional Dependency:**
- Phase out low-ROI channels over 12-18 months
- Reinvest savings in digital testing (TikTok, Podcasts, Influencers)
- Monitor brand metrics to ensure awareness doesn't decline

---

## 📊 Executive Summary: By the Numbers

### **Marketing Performance Snapshot**

| Metric | 2019 | 2020 | Change |
|--------|------|------|--------|
| **Total Sales** | $548.7M | $362.1M | –$186.6M (–34%) |
| **Media Contribution** | 12% ($22.8M) | 14% ($89.9M) | +2pp, +$67.1M |
| **Promo Contribution** | 10% ($19.0M) | 6% ($38.5M) | –4pp, +$19.5M |
| **Baseline Sales** | 78% ($147.6M) | 80% ($513.4M) | +2pp, +$365.8M |

### **Channel Efficiency Leaders**

**Digital Channels:**
- Social: 11.6 → 11.3 ROI ($16.3M → $21.5M)
- Search: 10.5 → 8.3 ROI ($11M+ annually)
- Combined ROI: **6-7× higher than traditional media**

**Traditional Channels:**
- TV: High spend, 1.5 ROI (post-COVID)
- Print: Consistently low ROI both years

### **Promotional Winners**

- **Samples:** 68% share, $38.2M contribution (+286% YoY)
- **GWP:** 27% share, $15.0M → $2.5M (COVID volatility)
- **Product Launch:** 5% share, declining effectiveness

### **COVID Impact**

- **Direct Sales Loss:** –$60.2M (32% of decline)
- **Incremental Sales Gain:** +$27.8M (digital acceleration)
- **Macro Factors:** –$110.6M (59% of decline)
- **Net Marketing Stability:** Maintained relative effectiveness despite crisis

---

## 🛠️ Tools & Techniques

**Jupyter Notebook - Interactive development and analysis**

**Analytical Methods:**
- Marketing Mix Modeling (MMM)
- Sales Decomposition Analysis
- ROI & Contribution Attribution
- Time-Series Performance Tracking
- Waterfall Gap Analysis
- Scenario Modeling (Pre/During/Post COVID)

**Data Processing:**
- Weekly sales data aggregation (Jan 2019 – Dec 2020)
- Media spend normalization across 8 channels
- Promotional effectiveness measurement (3 types)
- Macroeconomic factor integration

**Visualization:**
- Performance scorecards
- ROI trend analysis
- Sales decomposition charts
- Gap analysis waterfalls


---

## 👥 Team Members

**Group Contributors:**
- Minh Phan
- Levi Delaney
- Christopher Ogunbufunmi
- Olabanji Dodo
- **Talha Gulzar**

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

✅ **Marketing Mix Modeling:** Multi-channel attribution and ROI optimization  
✅ **Crisis Analytics:** Quantifying pandemic impact on business performance  
✅ **Budget Allocation:** Data-driven investment recommendations across media/promos  
✅ **Time-Series Analysis:** Performance tracking across multiple time periods  
✅ **Strategic Synthesis:** Translating analytics into executive recommendations  
✅ **Business Storytelling:** Presenting complex findings to senior leadership


---

## 💼 Business Impact

### **Recommended Budget Reallocation**

**Current State (Estimated):**
- Traditional Media: ~$8M (Low ROI)
- Digital Media: ~$6M (High ROI)
- Total: ~$14M

**Optimized Allocation:**
- Traditional Media: ~$5M (–$3M, –38%)
- Digital Media: ~$9M (+$3M, +50%)
- Total: ~$14M (budget neutral)

**Projected Outcome:**
- Incremental sales: +$20-30M from reallocation
- ROI improvement: 3.5 → 5.2 blended portfolio ROI
- Efficiency gain: +$1.4-$2.1 return per marketing dollar

---

## 👤 Author

**Mohammad Talha Gulzar**  
*Marketing Analytics | MMM & Attribution | Strategic Planning*


---

**Course:** MKT 6300 - Marketing Analytics  
**Institution:** Babson College  
**Date:** April 2025

---

*⭐ If this project helped you understand marketing mix modeling or media attribution, please consider giving it a star!*
