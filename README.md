"Will the Customer Accept the Coupon?"
---------------------------------------

Rahul Rusia

The JuPyTer notebook for this exercise can be found --> https://github.com/rahulrusia/coupon-analysis/blob/main/coupon_analysis_assignment5_1.ipynb

The data can be found here --> https://github.com/rahulrusia/coupon-analysis/blob/main/data/coupons.csv

Data Cleanup
------------

The following data cleanup operations has been performed:


Column Operations
Dropped car column as it has no value on data set and have NaN for 12576 rows which doesn't have any impact on this dataset.

Other columns like 'Bar', 'CoffeeHouse', 'CarryAway', 'RestaurantLessThan20', 'Restaurant20To50' were also had some NaN. These columns updated with most common value.


Key Observations
----------------

Key Observations Based on All Data

56.8% of total drivers accepted coupons.

This shows coupons are an effective marketing tool because acceptance rate is more than 50%.

Drivers traveling with friends or partners are more likely to accept coupons.

Drivers with kids as passengers show lower acceptance rates.

Younger drivers tend to accept coupons more often.

Older drivers are generally less responsive to coupon offers.

Drivers who frequently visit: bar, coffee house, restaurent are likely to accept coupons.

Certain coupons (like coffee) are more likely to be accepted during specific times of day (e.g., morning).

Some lower-income groups may show higher acceptance rates for certain coupons.

Coffee house coupon accepted most and costly resturants ($20-$50) was least accepted coupon.


Bar Coupon Observations
-----------------------

Drivers who visit bars more frequently (more than 3 times a month) have a higher acceptance rate for bar coupons.

Drivers who rarely or never go to bars are much less likely to accept these coupons.

Younger drivers tend to accept bar coupons more often than older drivers.

Acceptance is highest among drivers with a social lifestyle (frequent outings, no kids, active habits).

Drivers work outside farming/fishing/forestry accept bar coupons more often.

Drivers who go to bars more than once a month, had passengers that were not a kid, and were not widow.

Drivers go to cheap restaurants more than 4 times a month and income is less than 50K.


Next Steps
----------

Based on the analysis of coupon acceptance behavior, future efforts should focus on targeted marketing strategies tailored to specific customer segments.

Targeted Coupon Strategies

Mid-tier restaurant coupons:
     Should be targeted toward younger professionals (e.g., tech-savvy urban individuals) who are more likely to dine out and respond to such offers.

Bar coupons should be focused on:

     Frequent bar-goers

     Younger drivers

These groups showed significantly higher acceptance rates, indicating strong alignment with their lifestyle.

Take-out and low-cost restaurant coupons
Should be targeted toward:

    Drivers with children

    Especially during midday hours

These users are more likely to prefer convenient and quick meal options.








