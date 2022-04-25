# Pyber Analysis Using Matplotlib

## Purpose of Review

A review was requested by the CEO of Pyber, V. Isualize, and my direct supervisor, Omar, to review the performance of the type of city. In this analysis cities were grouped by three types, Urban, Suburban, and Rural. 

With categorizing the many cities Pyber is in, it allows us to see at the high-level how the company is performing in multiple different regions. By looking at the dares and driver count per type of region an analysis can occur to see where Pyber is lacking in sales, drivers, or riders. This was done through creating a dataframe based on the type of city, and then looking at total rides, fares (sum and average fare), and drivers (sum and average fare).

### Results of Analysis January 2019 to April 2019

As stated, before this review was done from January to April 2019. During this time period, a dataframe was created to compare total rides, total drives, and total fares. From those totals an average fare revenue was created for a per ride and per driver basis. 

Reviewing the dataframe, it is clear that the urbans regions are outperforming the other two regions when it comes to total rides, drivers, and fares. 

![df_city_type](https://user-images.githubusercontent.com/100856534/165009770-0a232707-8331-4a64-860a-25ba3470dd6b.png)

Reviewing the total fares per region you can see that the Urban region makes up the majority of revenue, being more than rural and suburban combined. 

 ![fares_per_type_percentage](https://user-images.githubusercontent.com/100856534/165009801-72a7e28d-f347-4198-b9bc-08392fa6e73b.png)

However, when reviewing the other city types, rural and suburban are outperforming the urban regions in average per ride and per driver. One of those reasons is clear, the urban regions have far more rides and drivers available to customers. Again, the urban regions make up more than half of the available rides and drivers company wide. 

![drivers_rides_per region](https://user-images.githubusercontent.com/100856534/165009820-c5a5aa52-66ea-4536-ad2f-0216e36d588f.png)

#### January to April 2019: Line Chart Comparison 

![fare_by_type](https://user-images.githubusercontent.com/100856534/165009840-6c25d1f5-a446-465f-846c-23c9f8667e70.png)

When we compile the performance of each region into one chart, we can see there is no overlap. What is meant by that is that the urban regions by far produced more revenue than the suburban and rural regions. Suburban does not overpass rural at any time during this period and rural never overpasses suburban during this period. 

Keeping in mind that this chart above is showing weekly average revenue. So this is not based on how many rides were provided or how many drivers were on the roads during this time. This is showing strictly revenue per week from January to April 2019.

### Summary and Recommendations

With rural clearly making the most revenue for Pyber we can learn that more volume makes more revenue for the company. However, increasing revenue always comes with the caveat of creating more costs. So how do we increase more revenue for the company to cover any additional costs. 

1) Increase driver presence in suburban and rural areas. 

- Averages are higher in both suburban and rural areas
- Rural per ride averages are 41% greater than urban for this period. 
- Suburban per ride averages are 26% greater than urban for this period.

With increased driver presence in the rural and suburban areas, there can be an increase in revenue based on the current driver count without creating too much more costs of adding any additional drivers. 

2) Hire additional drivers for suburban and rural regions.

This would lower average fare per driver, but these two regions are doing quite well with this metrics already.

- Urban fare per driver is $16.57.
- Suburban fare per driver is $39.50 (138% greater than urban).
- Rural fare per driver is $55.49 (235% greater than urban).

3) Increase cost per ride in rural and suburban areas. 

With the on-the-road presence is less in suburban and rural areas, Pyber could raise the cost per fare charge. This could be explained by less demand and less supply of drivers being available, thus increasing the cost of providing the ride share services in these areas. 
