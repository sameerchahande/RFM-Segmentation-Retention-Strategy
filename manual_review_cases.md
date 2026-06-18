# Manual Review Cases

## Overview
This document identifies 15 specific customers where the automated RFM segmentation decision is not straightforward. Each case includes the customer's key characteristics, the automated segment assignment, and the recommended manual decision with reasoning.

---

## Case 1: CUST00005
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 38 days, Frequency: 3 orders, Monetary: $1,781.90
- Return Rate: 0%, Avg Discount: 48%, Avg Rating: 1.0
- Support Tickets: 0, Negative Ticket Rate: 0%
- Category Diversity: 2, Sessions (30d): 18

**Why Ambiguous:**  
Despite being classified as a Champion (recent, frequent, high-value), this customer has:
1. Very low average rating (1.0/5.0) - extreme dissatisfaction
2. High discount usage (48%) - may be price-sensitive rather than loyal
3. Only 1 category purchased despite high frequency

**Manual Decision:** **Downgrade to "High-Value but Unhappy"**  
**Reasoning:** The combination of high spending with terrible ratings suggests the customer is tolerating the brand out of necessity or habit, not genuine loyalty. Without intervention, this customer is likely to churn. Action: Personal outreach from customer success team to address satisfaction issues.

---

## Case 2: CUST00050
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 0 days (purchased today), Frequency: 2 orders, Monetary: $2,026.54
- Return Rate: 50%, Avg Discount: 30%, Avg Rating: 2.5
- Support Tickets: 0, Negative Ticket Rate: 0%
- Category Diversity: 2, Sessions (30d): 3

**Why Ambiguous:**  
This customer is classified as a Champion due to zero recency and high monetary value, but:
1. 50% return rate is extremely high (product mismatch or quality issues?)
2. Low rating (2.5/5.0) despite recent purchase
3. Very low engagement (only 3 sessions)

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** High return rate indicates product dissatisfaction. The customer may be ordering multiple sizes/variants and returning most, which is costly. Action: Review return patterns, offer personalized product consultation, consider excluding from automatic re-order campaigns.

---

## Case 3: CUST00016
**Automated Segment:** Lost Customers  
**Key Metrics:**
- Recency: 215 days, Frequency: 0 orders, Monetary: $0
- Return Rate: 0%, Avg Discount: 0%, Avg Rating: 3.5
- Support Tickets: 0, Negative Ticket Rate: 0%
- Days Since Signup: 413, Sessions (30d): 2

**Why Ambiguous:**  
Classified as Lost (no purchases, very high recency), but:
1. Customer has been signed up for 413 days (long-term account)
2. Recent activity (2 sessions in last 30 days) - still engaging with brand
3. No negative signals (no tickets, no returns)

**Manual Decision:** **Move to "At-Risk Customers"**  
**Reasoning:** The customer is still browsing but not purchasing. This suggests interest but barriers to conversion (price, shipping, product fit). Action: Send re-engagement email with browse-history-based recommendations and free shipping offer.

---

## Case 4: CUST00030
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 5 days, Frequency: 5 orders, Monetary: $2,819.98
- Return Rate: 0%, Avg Discount: 36.2%, Avg Rating: 4.2
- Support Tickets: 2, Negative Ticket Rate: 100% (2/2)
- Category Diversity: 4, Sessions (30d): 11

**Why Ambiguous:**  
Champion by RFM metrics, but:
1. 100% negative ticket rate (2 tickets, both negative)
2. High discount dependency (36.2% average)
3. Despite complaints, continues to purchase heavily

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** This customer is actively experiencing service issues but hasn't churned yet. The high spending makes them critical to retain. Action: Immediate service recovery call, assign dedicated support agent, review ticket history for systemic issues.

---

## Case 5: CUST00042
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 87 days, Frequency: 5 orders, Monetary: $4,306.00
- Return Rate: 0%, Avg Discount: 20%, Avg Rating: 3.4
- Support Tickets: 2, Negative Ticket Rate: 50% (1/2)
- Category Diversity: 4, Sessions (30d): 3

**Why Ambiguous:**  
Champion by RFM, but:
1. Recency is 87 days (borderline for "recent" definition)
2. Mixed support experience (50% negative tickets)
3. Low engagement (3 sessions) despite high value

**Manual Decision:** **Move to "At-Risk Customers"**  
**Reasoning:** The customer hasn't purchased in nearly 3 months despite being a high-value historical buyer. The mixed support experience may have contributed to disengagement. Action: Win-back campaign with personalized product recommendations and loyalty bonus.

---

## Case 6: CUST00067
**Automated Segment:** New Customers  
**Key Metrics:**
- Recency: 63 days, Frequency: 2 orders, Monetary: $1,246.44
- Return Rate: 50%, Avg Discount: 20%, Avg Rating: 2.5
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 2, Sessions (30d): 1

**Why Ambiguous:**  
Classified as New Customer, but:
1. 50% return rate on only 2 orders (both orders returned?)
2. 100% negative ticket rate
3. Very low rating (2.5/5.0)
4. Minimal engagement (1 session)

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** This new customer is having a terrible experience. Without intervention, they will churn and potentially damage brand reputation. Action: Immediate service recovery outreach, refund/compensation for bad experience, product fit consultation.

---

## Case 7: CUST00074
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 7 days, Frequency: 1 order, Monetary: $824.34
- Return Rate: 100%, Avg Discount: 23%, Avg Rating: 3.0
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 14

**Why Ambiguous:**  
Champion by recency, but:
1. 100% return rate (entire order returned)
2. Single category focus
3. High engagement (14 sessions) but only 1 order

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** The customer is actively engaged but experiencing product issues severe enough to return everything. The high session count suggests interest, but fulfillment is failing. Action: Review product quality/sizing, offer replacement or different product line, assign personal shopper.

---

## Case 8: CUST00083
**Automated Segment:** At-Risk Customers  
**Key Metrics:**
- Recency: 89 days, Frequency: 2 orders, Monetary: $806.87
- Return Rate: 50%, Avg Discount: 33.5%, Avg Rating: 3.5
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 9

**Why Ambiguous:**  
At-Risk by recency (89 days), but:
1. Moderate monetary value ($806.87)
2. High discount usage (33.5%)
3. Negative ticket experience
4. Still engaging (9 sessions)

**Manual Decision:** **Keep as "At-Risk" but flag for special campaign**  
**Reasoning:** This customer is price-sensitive and had a bad support experience. Standard win-back may not work. Action: Offer bundled discount (perceived higher value), address support issue proactively, emphasize quality guarantees.

---

## Case 9: CUST00090
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 80 days, Frequency: 4 orders, Monetary: $1,966.31
- Return Rate: 0%, Avg Discount: 37.5%, Avg Rating: 4.5
- Support Tickets: 0, Negative Ticket Rate: 0%
- Category Diversity: 3, Sessions (30d): 5

**Why Ambiguous:**  
Champion by RFM, but:
1. Recency is 80 days (questionable for "recent")
2. Very high discount usage (37.5%)
3. Low engagement (5 sessions) for a champion

**Manual Decision:** **Move to "Potential Loyalists"**  
**Reasoning:** This customer appears to be deal-driven rather than genuinely loyal. The 80-day recency suggests they only buy when there's a promotion. Action: Test full-price offer vs. discount to determine true loyalty. Consider moving to loyalty program that rewards engagement, not just purchases.

---

## Case 10: CUST00097
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 1 day, Frequency: 3 orders, Monetary: $2,946.09
- Return Rate: 0%, Avg Discount: 41%, Avg Rating: 2.33
- Support Tickets: 0, Negative Ticket Rate: 0%
- Category Diversity: 1, Sessions (30d): 0

**Why Ambiguous:**  
Champion by RFM (very recent, high value), but:
1. Extremely low rating (2.33/5.0)
2. High discount dependency (41%)
3. Zero digital engagement (0 sessions)
4. Single category focus

**Manual Decision:** **Move to "Discount-Sensitive Customers"**  
**Reasoning:** This customer is clearly motivated by discounts, not brand loyalty. The low rating suggests they may be dissatisfied with full-price products. Action: Exclude from full-price campaigns, include in strategic discount campaigns, monitor for churn if discounts stop.

---

## Case 11: CUST00108
**Automated Segment:** At-Risk Customers  
**Key Metrics:**
- Recency: 44 days, Frequency: 1 order, Monetary: $1,074.50
- Return Rate: 100%, Avg Discount: 22%, Avg Rating: 1.0
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 5

**Why Ambiguous:**  
At-Risk by recency, but:
1. Single order was completely returned (100% return rate)
2. Worst possible rating (1.0/5.0)
3. Negative support ticket
4. Still browsing (5 sessions)

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** This customer had a catastrophic first experience. The monetary value is misleading since all revenue was refunded. Action: Immediate executive-level service recovery, free product replacement, personal apology. Risk of negative word-of-mouth is high.

---

## Case 12: CUST00156
**Automated Segment:** Potential Loyalists  
**Key Metrics:**
- Recency: 34 days, Frequency: 2 orders, Monetary: $4,241.75
- Return Rate: 50%, Avg Discount: 14.5%, Avg Rating: 2.5
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 14

**Why Ambiguous:**  
Potential Loyalist by RFM, but:
1. 50% return rate (one of 2 orders returned)
2. 100% negative ticket rate
3. Very low rating (2.5/5.0)
4. High engagement (14 sessions) but single category

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** High monetary value is inflated by returns. The customer is engaged but experiencing product/service issues. Action: Review return reason, offer product alternatives, assign customer success manager for white-glove service.

---

## Case 13: CUST00163
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 70 days, Frequency: 1 order, Monetary: $2,128.34
- Return Rate: 100%, Avg Discount: 30%, Avg Rating: 1.0
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 11

**Why Ambiguous:**  
Champion by monetary value, but:
1. 100% return rate (entire order returned)
2. Worst rating (1.0/5.0)
3. Negative support experience
4. High browsing (11 sessions) but no recent purchase (70 days)

**Manual Decision:** **Move to "High-Value but Unhappy"**  
**Reasoning:** Similar to Case 11, this customer had a complete order failure. The 70-day recency means they haven't purchased since the bad experience. Action: Aggressive service recovery campaign, free product with no-strings-attached, personal call from management.

---

## Case 14: CUST00226
**Automated Segment:** At-Risk Customers  
**Key Metrics:**
- Recency: 54 days, Frequency: 3 orders, Monetary: $2,345.42
- Return Rate: 33.3%, Avg Discount: 15.7%, Avg Rating: 4.0
- Support Tickets: 1, Negative Ticket Rate: 100%
- Category Diversity: 1, Sessions (30d): 6

**Why Ambiguous:**  
At-Risk by recency, but:
1. Historically high frequency (3 orders)
2. High monetary value ($2,345.42)
3. Good rating (4.0/5.0) overall
4. But 100% negative ticket on recent support interaction

**Manual Decision:** **Move to "At-Risk" with service recovery flag**  
**Reasoning:** The recent support issue may be the reason for the 54-day gap. If unresolved, this high-value customer will churn. Action: Proactive outreach about the support ticket, resolution confirmation, compensation for inconvenience, re-engagement offer.

---

## Case 15: CUST00230
**Automated Segment:** Champions  
**Key Metrics:**
- Recency: 37 days, Frequency: 6 orders, Monetary: $6,235.96
- Return Rate: 0%, Avg Discount: 21.8%, Avg Rating: 4.17
- Support Tickets: 0, Negative Ticket Rate: 0%
- Category Diversity: 3, Sessions (30d): 17

**Why Ambiguous:**  
Champion by all metrics, BUT:
1. Exceptionally high frequency (6 orders in 180 days)
2. Very high monetary value ($6,235.96)
3. This pattern may indicate reseller/bulk buyer behavior

**Manual Decision:** **Verify customer type - keep as Champion if B2C, create "Reseller" segment if B2B**  
**Reasoning:** The purchase pattern (6 orders, $6K+ in 180 days) is unusual for a typical D2C customer. If this is a reseller, standard retention strategies won't apply. Action: Review order details (shipping addresses, bulk quantities), consider B2B pricing tier, assign account manager if wholesale.

---

## Summary of Manual Review Actions

| Customer ID | Automated Segment | Manual Decision | Primary Action |
|-------------|-------------------|-----------------|----------------|
| CUST00005 | Champions | High-Value but Unhappy | Service recovery call |
| CUST00050 | Champions | High-Value but Unhappy | Product consultation |
| CUST00016 | Lost Customers | At-Risk | Re-engagement with browse recs |
| CUST00030 | Champions | High-Value but Unhappy | Service recovery + agent |
| CUST00042 | Champions | At-Risk | Win-back + loyalty bonus |
| CUST00067 | New Customers | High-Value but Unhappy | Immediate service recovery |
| CUST00074 | Champions | High-Value but Unhappy | Product quality review |
| CUST00083 | At-Risk | At-Risk (special) | Bundled discount campaign |
| CUST00090 | Champions | Potential Loyalists | Test full-price loyalty |
| CUST00097 | Champions | Discount-Sensitive | Strategic discount only |
| CUST00108 | At-Risk | High-Value but Unhappy | Executive service recovery |
| CUST00156 | Potential Loyalists | High-Value but Unhappy | Product alternatives |
| CUST00163 | Champions | High-Value but Unhappy | Aggressive recovery |
| CUST00226 | At-Risk | At-Risk (service flag) | Proactive ticket resolution |
| CUST00230 | Champions | Verify/Reseller | Review purchase pattern |

## Key Insights from Manual Review

1. **High return rates are a red flag** - 6 out of 15 cases had 50%+ return rates, indicating product/service issues
2. **Low ratings predict churn** - Even high-value customers with 1-2 star ratings are at risk
3. **Support ticket negativity matters** - 100% negative ticket rate appeared in 8 of 15 cases
4. **Discount dependency is hidden churn risk** - Customers with 35%+ discount usage may not be truly loyal
5. **Engagement ≠ Purchase** - Several customers had high session counts but no recent purchases, indicating conversion barriers

## Recommended Process Improvements

1. **Real-time alerts** for customers with return rates >30% or ratings <2.5
2. **Automatic service recovery** triggers for negative support tickets
3. **Discount dependency tracking** - flag customers who only buy on promotion
4. **Reseller identification** - detect bulk purchase patterns early
5. **Post-return surveys** to catch product issues before churn