# Will the Customer Accept the Coupon?
 
## Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” 

There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

## Findings

By visualizing statistical summaries encompassing various contextual attribues associated with the survied drivers' trips (wheather, time of day, etc.) and attributes of the drivers themselves (marital status, income, education, profession, etc.) the following differences between drivers who accepted the coupons and those who did not accept the coupons were discovered:

1) The largest gaps between coupon acceptance and non-acceptance belonged to coupons sent to drivers for "Carry out & Take Away" and "Restaurants whose average price for a meal was less than $20".

2) Drivers who accepted coupons to visit a near by bar share the following characteristics:

- They tend to visit bars more than once a month
- They tend to fall between the ages of 25 and 30
- They tend not to have children riding with them in the car upon acceptance
- They tend to not be Fishermen, Farmers nor Foresters

Furthermore, warm tempuratures seem to persuade drivers to accept coupons versus cold tempuratures.

3) Drivers who accepted coupons for carry out from a near by restaurant share the following characteristics:

- Most of them are widowed
- They tend to not have a bachelor's degree
- They tend to make less than $50K per year and they tend to order carry out more than 4 times a month

Additionally, most coupons are accepted early in the morning presumably when most drivers are on their way to work and are trying to find carry out for breakfast. However, the biggest gap between coupon acceptance and non-acceptance was observed during the 6pm time slot. This suggest that drivers are more selective during this time of the day which would require business to build targeted marketing campaigns for this particular group.

