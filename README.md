# Mexico Restaurant Ratings Analysis

_Uncovering consumer behavior, demand–supply gaps, and investment signals in the Mexican restaurant market._

---

## Quick Look

- **Primary Customer Segment:** Young adults (18–25), medium spenders  
- **Dominant Cuisine Demand:** Mexican cuisine (largest unmet demand)  
- **Pricing Sweet Spot:** Medium-priced restaurants outperform low and high price tiers  
- **Key Success Driver:** Operational consistency over premium features
- **Dataset:** [View Dataset](https://drive.google.com/file/d/1c1HKM8UTqwWOgexRLOtEJuxjBiA2N6xf/view)
- **Interactive Dashboard:** [View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYzNlMTExNmUtZjcyYy00MDM3LWJlOWEtY2Q2NTZkZmY2NDhiIiwidCI6IjdlMGI1ZmNmLTEyYzQtNGVmZi05NmI2LTQ2NjRmMjVkYzdkYSIsImMiOjEwfQ%3D%3D)  
- **Full Story & Deep Dive:** [Read Full Analysis on Medium](https://medium.com/@odzainab1/restaurant-rating-analysis-342424a7847c)


---

## Introduction

Behind every restaurant experience lies a set of patterns shaped by customer preferences, pricing expectations, and operational decisions. This project explores a **Mexican restaurant ratings dataset collected in 2012**, using customer survey data to uncover what separates high-performing restaurants from the rest.

Rather than treating ratings as isolated scores, this analysis connects **consumer demographics, lifestyle behaviors, cuisine demand, pricing strategy, and restaurant attributes** to answer one core question:

**If you were to invest in a restaurant, what characteristics would signal the highest chance of success?**

---

## Business Questions

This analysis focuses on four strategic questions:

- What distinguishes the highest-rated restaurants from average performers?  
- How do consumer preferences and demographics influence restaurant ratings?  
- Are there demand–supply gaps that represent investment opportunities?  
- Which restaurant characteristics signal long-term operational success?

---

## Dataset & Tools

**Key Tables:**  
- Consumers (demographics, lifestyle, budget)  
- Restaurants (pricing, features, location, cuisine)  
- Ratings & Consumer Preferences  

**Tools Used:**  
- Power Query – Data cleaning and transformation  
- Power BI – Data modeling, DAX measures, and visualization  

---

## Data Preparation & Validation

The datasets were reviewed with a focus on **preserving data integrity rather than aggressive filtering**:

- Standardized column names and verified data types across all tables  
- Replaced missing demographic and behavioral values with **“Unknown”** to retain all consumer records  
- Removed non-analytical fields (e.g., country, zip code, restaurant names)  
- Created age segments and pricing categories for meaningful comparison  
- Consolidated cuisine types into top-level categories  
- Established relationships across Consumers, Restaurants, Ratings, and Preferences tables  
- Built DAX measures for average ratings, satisfaction distribution, and demand–supply gaps  

**Outcome:** a clean, analysis-ready data model capable of supporting cross-dimensional insights into consumer behavior, restaurant performance, and market opportunities.

---

## Data Visualization

<img width="1138" height="650" alt="Screenshot 2026-01-07 121336" src="https://github.com/user-attachments/assets/bb416f43-d511-46b0-b450-8180755e7771" />
                                                    
                                                       
<img width="1137" height="639" alt="Screenshot 2026-01-07 121354" src="https://github.com/user-attachments/assets/7828eb35-7611-4d60-9cf1-bb80ca6b4b33" />


## Key Insights

The data tells a clear and practical story about how restaurants succeed in this market.

### 1. Demand is concentrated and underserved

Young adults aged **18–25** dominate the customer base, with most falling into the **medium-budget** category. Their preferences are not evenly distributed: **Mexican cuisine overwhelmingly dominates demand**, yet supply falls far short. Similar gaps appear for **Coffee Shops, Family-style restaurants, and Pizzerias**, indicating clear opportunities for new entrants or expansion.

This imbalance suggests the market is not saturated, it is **misaligned**.

---

### 2. Pricing alignment matters more than premium positioning

Medium-priced restaurants consistently outperform both low- and high-priced alternatives. Low-priced restaurants struggle to deliver perceived quality, while high-priced establishments face elevated expectations they often fail to meet.

**The result:** value alignment, not price extremes, drives satisfaction.

---

### 3. Operational simplicity outperforms feature complexity

High-performing restaurants share a surprising trait: **they do less, but do it well**.

Restaurants without alcohol service, smoking areas, franchise constraints, or complex parking arrangements consistently achieve stronger ratings. This suggests that operational complexity introduces execution risk, while simplicity supports consistency and reliability.

---

### 4. Execution beats location

Geographic analysis shows that **management quality outweighs market size**. Smaller regions like **Cuernavaca (Morelos)** outperform larger or more commercial areas, while underperformance in regions such as **Tamaulipas** points to operational gaps rather than lack of demand.

Success is driven by **how** restaurants are run, not where they are located.

---

### 5. Food and service work as multipliers

Customers do not strongly separate food and service in their evaluations. Excellence in one cannot fully compensate for weakness in the other. High satisfaction emerges when **both perform consistently**, reinforcing the importance of balanced execution.

---

## Summary

- The market is driven by **young, medium-budget consumers** with concentrated cuisine preferences  
- **Mexican cuisine and casual dining concepts** show the largest unmet demand  
- Medium pricing delivers the strongest satisfaction outcomes  
- Operational simplicity and execution consistency are stronger success drivers than premium features  
- Location matters less than management quality and service reliability  

---

## Recommendations

1. **Target High-Demand, Underserved Cuisines**  
   Focus on Mexican, Coffee Shop, and Family-style concepts aligned with medium pricing.

2. **Prioritize Operational Consistency**  
   Invest in staff training, process standardization, and service reliability, especially in underperforming regions.

3. **Keep Features Simple**  
   Avoid unnecessary amenities that increase complexity without improving customer experience.

4. **Align Pricing With Expectations**  
   Medium pricing offers the best balance between perceived value and execution capability.

5. **Exploit Demand–Supply Gaps Strategically**  
   Use data-driven analysis to guide concept selection and regional expansion decisions.

---

## Next Steps

- Validate findings across broader demographic and regional datasets  
- Pilot high-demand concepts in underserved locations  
- Track service and food quality KPIs post-launch  
- Conduct deeper segmentation to identify niche opportunities  

---

## Conclusion

The Mexican restaurant market rewards **alignment over ambition**. Restaurants that match pricing to consumer expectations, maintain operational simplicity, and focus on execution outperform those relying on premium positioning or extensive features. For investors and operators, the strongest opportunities lie in underserved cuisines, medium-priced concepts, and regions where consistent management can unlock latent demand.
