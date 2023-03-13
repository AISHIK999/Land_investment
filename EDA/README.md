# Analysis of the House_Rent_Dataset 
## All the findings have been listed below:

**Histogram:**
* Comparing the rents with date posted, it is clear that the rent of apartments are rising with passing time.
* Most of the apartments are of 2 BHK and at ground floor and most of the rented buildings are single storied.
* 1 BHK and 2 BHK apartments are almost the same in quantity.
* The apartments are mostly under 1500 sq.ft
* Most apartments have 2 bathrooms, followed by 1 and 3 bathrooms.
* The rent column is skewed to the right, with a mean rent of Rs.35,000.

**Box plot:**
* Furnishing status vs rent:
    * It seems that there is a massive outlier in the furnished category, which is skewing the data.
    * We removed that outlier and plotted the boxplot again.
    * It is clear that the furnished apartments are the most expensive ones.
* Tenant Preferred vs rent:
    * It is clear that the rent is higher for families than for bachelors.

**Bar plot:**
* City vs rent:
  * It is very clear that the rent over at Mumbai is the highest, and by a large margin.
    * The mean rents for each city in descending order are:
      * Mumbai (45k) > Delhi(22k) > Hyderabad(17.8k) > Chennai(17.6k) > Bangalore(17.5k) > Kolkata(11.3k)
* City vs number of bedrooms and apartment size:
  * Hyderabad has the biggest number of bedrooms and biggest size of apartments
  * Mumbai has the smallest apartments and the least number of bedrooms. Yet the rent is highest there.

**Line plot:**
* Bedrooms:
  * Kolkata, Hyderabad and Chennai have the apartments with most bedrooms.
  * The price of an apartment seems to be directly proportional to the number of bedrooms. But in case of Kolkata and seemingly Chennai, the price seems to drop for 5,6 BHK apartments.
* Floors:
  * Mumbai seems to be the only city to have apartments with rent floors higher than 30 and total floors higher than 40.
* Bathrooms:
  * Initially the rent of apartments were increasing universally with the number of bathrooms. But they fell after passing a fixed threshold.
* Size:
  * The size of an apartment seems to be directly proportional to the rent.
  * In case of Kolkata, the rent seems to drop after 2000 sq.ft.

# CONCLUSION:
Rent of apartments are increasing with time. Most of them are for private use, with 2BHK rooms and 2 bathrooms.
Rent is the highest in Mumbai and the least in Kolkata. 
Hyderabad has the biggest apartments available for rent, indicating that they maybe open for commercial use. 
Rent in Kolkata seems to decrease for some reason with increasing size of the apartment. This might indicate that the bigger apartments are not being used for commercial purposes. Since commercial rent is much more than private ones.
Mumbai has small apartments and the highest rent, which might indicate that the apartments are being used for private purposes. The fact that the rented apartments are mostly single storied might also indicate that the apartments are not being used for living/private purposes .
The number of bathrooms seems to reduce the value of apartments with increase after a threshold. This maybe because no ones would rent an apartment with more bathrooms, that wil decrease the living area for the tenants.

From the study, it can be assumed that:
* The rent of apartments is increasing with time. So it is a good time to invest in real estate.
* Investing in apartments in Mumbai is a good idea, since the rent is the highest there.
* For commercial purposes, it might be a good idea to invest in apartments in Hyderabad, since it has the biggest area available for rent.
* For personal living, it might be a good idea to choose Kolkata as a place to stay because of the cheap rent.
* It is a good idea to invest in 2 BHK apartments with 2 bathrooms (preferably in Mumbai), since the rent is the highest for them.