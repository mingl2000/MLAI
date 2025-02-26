# UCI Coupon Dataset Exploratory Data Analysis (EDA) 
## Project Overview
This data analysis project investigates factors influencing customer coupon acceptance using the UCI Machine Learning dataset containing various customer attributes and coupon context information. The analysis focuses on identifying key differences between customers who accept vs decline coupons, with special emphasis on bar coupons.

This project also investigates the following topics:
- What driver specific factors are associated with coupon acceptance?
- What environmental factors are associated with coupon acceptance?
- What are the top 10 factors associated with coupon acceptance?

## Key Findings

Significant missing data in car column (99.15%) and it's dropped from the analysis

Overall coupon acceptance rate: 56.84%

### Bar Coupons:

    - Bar coupons acceptance rate for bar coupons is 41%

    - High acceptance rate of bar coupons for the following drivers:

        * Drivers visiting bars ≤3 times/month
        * Drivers with non-farming occupations with adult passengers
        * Drivers with 'Bachelors degree' or 'Some college - no degree'
        * Drivers with income less than $62,500 or more than $100,000
        * Drivers without kid

    - High acceptance rate of bar coupons for the following occassions:
        * Sunny day and 80F temperature
        * When near lunch or dinner time.
        * Coupon is expired in 1 day
    
    - Low acceptance rate of bar coupons for the following drivers:
        * Drivers who went to bar 4 or more times a month
        * Old drivers with 50+ years old
        * Drivers with income between $62500-$9999 

    - Low acceptance rate of bar coupons for the following occassions:
       * When coupon is expired in 2 hours or less.
       * When weather is not sunny or cold.

### Other coupons:
    - Very low acceptance rate for 'Coffee House' coupons









