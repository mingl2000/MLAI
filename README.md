# Coupon Acceptance Analysis
## Project Overview
This data analysis project investigates factors influencing customer coupon acceptance using the UCI Machine Learning dataset containing various customer attributes and coupon context information. The analysis focuses on identifying key differences between customers who accept vs decline coupons, with special emphasis on bar coupons.

## Dataset Description
The dataset contains 12,684 observations with 26 features including:
- User attributes (age, gender, income, occupation)
- Contextual features (time, destination, weather)
- Coupon attributes (type, expiration time)
- Target variable (`Y` - acceptance status)

Key coupon types analyzed:
- Restaurants (<$20)
- Coffee House
- Carry out & Take away
- Bar
- Restaurants ($20-$50)

## Key anaalysis steps
Data Loading & Initial Exploration

Missing Data Handling

Overall Acceptance Rate Calculation

Visual Analysis:

Coupon type distribution

Temperature distribution

Bar Coupon Focus:

Acceptance rate comparisons

Visit frequency analysis

Demographic comparisons

Passenger/occupation relationships

## Key Findings

Overall acceptance rate: 56.84%

Bar Coupons:

41% acceptance rate

Highest acceptance from customers visiting bars ≤3 times/month

Higher acceptance from non-farming occupations with adult passengers

Significant missing data in car column (99.15%) and it's dropped from the analysis

Temperature distribution shows majority of coupons issued in sunny day and 80F