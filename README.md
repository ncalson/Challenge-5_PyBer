# Module 5 | Assignment - PyBer

Analyze and visualize ride-sharing data using Python, Pandas, and the Matplotlib library.

## Overview
The goals of this analysis include:
- Create a summary DataFrame of the ride-sharing data by city type (i.e. urban, suburban, and rural).
- Use Pandas and Matplotlib to make a multiline graph displaying total weekly fares organized by city type.

## Results
### Fare Summary Table:

![this is an image](https://github.com/ncalson/Challenge-5_PyBer/blob/main/analysis/Fare%20Summary%20Data%20Table.png)

Because there are significantly less drivers in the suburban and rural areas compared to the urban areas, the average fare per ride and average fare per driver fares are both significantly higher for suburban and rural areas vs. in urban areas.

### Fare Summary Multiline Graph:

![this is an image](https://github.com/ncalson/Challenge-5_PyBer/blob/main/analysis/PyBer_fare_summary.png)

 - Rural Areas: Peaks in total fares in late February and early April.
 - Suburban Areas: Peaks in total fares in late February and trending upwards in late April.
 - Urban Areas: Peaks in total fares in late February and throughout March, while steadily staying up in April.
 
These busier times generally follow the same trends, inferring as the weather gets nicer as the season transitions from winter to spring, there are more ride requests for drivers in all three types of areas. I would suspect if this data continued to show results into the summer, the total fares in all three areas would continue to increase.

## Summary
Because urban areas have significantly larger populations, they have a higher demand and generally bring in significantly higher earnings. However, because there is a lower supply of drivers in rural and suburban areas, the fares charged to riders are significantly higher compared to urban areas. Therefore, drivers in suburban and rural areas can hypothetically provide the same number of rides as a single driver in an urban area, but because the rate will be much higher in suburban and rural areas due to a lower supply of drivers, these drivers will make significantly more than a single driver in an urban area.

My recommendations in addressing any disparaties amongst the three city types are:

1. Offer incentives like covered moving costs or a bonus to encourage drivers to relocate from urban areas to suburban and rural areas. This will increase the supply of drivers, maybe balancing out the disparity of fare pricing between city types.
2. Offer surge pricing when the demand for rides is higher (i.e. during busy days and time frames) in urban areas to help individual drivers earn a higher fare amount while completing a typical number of rides.
3. In urban areas, offer riders a discount to ride to popular pick-up/drop-off points rather than a specific location. This scenario allows drivers to automatically start a new ride as soon as their current ride ends since they will be in an area with an abudance of ride requests.