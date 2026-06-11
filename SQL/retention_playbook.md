
RETENTION PLAYBOOK
==================

1. PROMO SUNSET PLAN
---------------------
Target Segments: Low & Mid Value Tier with Promo_Dependency_Score = 1.0
- Low Tier Promo Users: 539 customers
- Mid Tier Promo Users: 590 customers

Why sunset these segments:
- Low tier customers spend only $40.92 avg even WITH promos
- Mid tier non-promo customers spend MORE ($61.70) than promo users ($58.63)
- Discounts are not converting low-value customers into high-value ones

Rollout Timeline:
- Month 1-2: Reduce promo frequency by 50% for Low tier
- Month 3-4: Replace discounts with loyalty points for Mid tier
- Month 5-6: Full sunset for Low tier, monitor Mid tier revenue

Trigger Behavior: Promo_Dependency_Score = 1.0 + Value_Tier = Low/Mid
Metric to Track: Avg_Spend per segment monthly — target 5% increase

DO NOT sunset: High tier promo users (548 customers, $78 avg spend)
Risk: ~$22K monthly revenue at risk from Low tier dropout

2. IDEAL CUSTOMER PROFILE
--------------------------
Based on High Value Tier + Satisfied + No Promo Dependency:

Demographics:
- Age: 31-55 (peak purchasing years)
- Gender: Both equally represented

Behavioral Signals:
- Previous Purchases: 37+ transactions
- Avg Spend: $78+
- Promo Dependency: 0.0 (buys without discounts)
- Satisfaction Flag: Satisfied
- Tenure: Established to Loyal

Geographic Targeting:
- Priority states: Kansas, Arizona, Alaska, Pennsylvania
  (Low promo dependency + High avg spend)

Category Preference:
- Clothing & Accessories (highest volume)
- Outerwear (high spend, low new-customer entry)

Acquisition Strategy:
- Target 26-55 age group in organic states
- Lead with Clothing/Accessories as entry category
- Upsell to Outerwear once 10+ purchases reached
- Never offer promo at first purchase — test organic conversion
