# Assignment 5

This is a practical application assignment that focuses on using data analysis skills, in an effort to seek answers to the question based on survey results: **“Will a driving customer accept the coupon if offered for visiting a restaurant/bar/coffee shop on their way to a destination?”**

### Link to Explore Notebook: 
[Explore Coupon Acceptance Factors by Vehicle Drivers](https://github.com/seetharamanr86/customer_coupon_acceptance/blob/main/Explore-Coupon-Acceptance-Factors-by-Vehicle-Drivers.ipynb)

### Data Used: 
[In-Vehicle Coupon Recommendation](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation)

---

### General Findings:

A total of **13370** null values, spread across 6 columns, with the **car** column having the most number of null values:

- `car`: 12576

The remaining columns had minimal null values that can be ignored:
- `Bar`: 107
- `CoffeeHouse`: 217
- `CarryAway`: 151
- `RestaurantLessThan20`: 130
- `Restaurant20To50`: 189

---

### Bar Coupon Related Findings:

- **Acceptance Rate**: The bar coupon acceptance overall was **41%**, while non-acceptance stood at **59%**.
  
- **Frequent Bar Visitors**: The 'more frequent visitors' to the bar accepted the coupons at a rate of **~76%**, compared to 'less frequent visitors' who showed only **~37%** interest in coupon acceptance.
  
- **Age and Acceptance**: The 'frequent elderly visitors' accepted the coupons the most (**69%**), compared to 'less frequent young visitors' who showed only **33%** interest.
  
- **Occupation and Age Influence**: 
  - Frequent elderly visitors without farming/fishing/forestry jobs accepted the coupons at **70%**.
  - Less frequent young visitors with farming/fishing/forestry jobs accepted at only **30%**.
  
- **Younger Visitors vs Others**: 
  - Frequent younger visitors accepted the coupons at **39%**.
  - Frequent elder widowed visitors accepted them slightly less (**37%**).
  - Frequent visitors to cheap restaurants with low income showed even less interest (**24%**).

**In General**:
Drivers who frequently visit bars are more likely to accept the coupons, while those with low incomes or who frequent cheap restaurants care less about bar coupons, as evident from the outcomes.

---

### Coffee Coupon Related Findings:

- **Group Influence**: Coffee coupons were accepted more frequently by passengers traveling with friends, whereas those traveling alone showed comparatively less interest.
  
- **Income Influence**: Income does not significantly influence coffee coupon acceptance, with around **50%** acceptance across all income groups.
  
- **Gender Influence**: Gender also does not significantly impact coffee coupon acceptance, showing **50%** acceptance for both males and females.
  
- **Age Influence**: Young drivers below age 21 have higher acceptance of coffee coupons, while the elderly population (50+) shows slightly less acceptance. Intermediate age groups show around **50%** acceptance.
  
- **Occupation Influence**:
  - Students and unemployed drivers have high acceptance of coffee coupons.
  - Drivers in 'building/grounds cleaning/maintenance' have close to **100%** acceptance.
  - Similarly, 'farming/fishing/forestry' and 'healthcare' jobs also show high acceptance rates.
  - 'Sales' job workers show comparatively less interest in coffee coupons.
  
- **Weather Influence**: Surprisingly, the weather had no significant impact on coffee coupon acceptance. The acceptance was slightly lower in snowy conditions, likely due to driving comfort influencing the decision.

---
