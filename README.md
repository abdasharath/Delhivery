# Delhivery-Feature-Engineering 

Delhivery, India's leading and rapidly growing integrated player, has set its sights on creating the commerce operating system. They achieve this by utilizing world-class infrastructure, ensuring the highest quality in logistics
operations, and harnessing cutting-edge engineering and technology capabilities.
## Business Insights:
* The data is given from the period '2018-09-12 00:00:22.88' to '2018-10-03 23:59:42.70'
* There are a total of 12,369 unique trip UUIDs created, indicating that this many trips are present in the dataset.
* There are about 32 unique destination state, 1256 unique destination city, 778 unique destination place and 27 unique destination code.
* There are about 31 unique source state, 1260 unique source city, 1177 unique source place and 24 unique source code.
* Karnataka and Maharashtra serve as primary transportation hubs in Bangalore, with a higher number of trips originating from other states. Following this, Mumbai emerges as a bustling route. In Karnataka, Nelamangala stands out as the main destination, while Mumbai Central serves as the main destination in Mumbai.
* Most of the data is for testing than for training.
* Most common route type is Carting ( Handling system consisting of small vehicles (carts)).
* Features Actual Time vs Segment Actual Time are statistically similar.
* Features OSRM Distance vs Segment OSRM Distance are statistically different.
* OSRM Time vs Segment OSRM Time there is enough evidence to say that this both are different.
* Busiest Year: The dataset primarily consists of trips from the year 2018, with all 26,222 trips recorded during that year.
* Busiest Month: September (Month 9) stands out as the busiest month, with a significant number of trips recorded (23,054 trips). October (Month 10) follows with a comparatively smaller number of trips (3,168).
* Busiest Week: Week 38 appears to be the busiest week, accounting for 8,852 trips. The subsequent weeks 39, 37, and 40 also exhibit high activity with 7,905, 6,297, and 3,168 trips, respectively.
* Busiest Day of the Week: Wednesday is identified as the busiest day of the week, with 4,819 trips. Thursday and Friday closely follow with 3,795 and 3,718 trips, respectively.
* Busiest Day: The 18th day of the month is the busiest, recording 1,373 trips. Days 21, 13, 20, and 25 also exhibit high activity with similar trip counts.

## Recommendation:
* Collect feedback from customers regarding their experience during trips. Analyze customer satisfaction metrics to identify areas for improvement and enhance overall service quality.
* Conduct a detailed analysis of routes to identify opportunities for optimization. Focus on routes with statistically significant differences in OSRM Time and Segment OSRM Time to enhance efficiency.
* Investigate the reasons behind the similarity observed in Actual Time vs. Segment Actual Time. Consider refining the segmentation process to ensure that segment-specific features contribute to better predictions.
* Look at the routes and see where we can make them more efficient. Some routes might be faster or slower than expected, so we want to make sure they are just right.
* Ask people about their trips and what they liked or didn't like. This helps us make sure our customers are happy and enjoy their rides.
* Think about going to new places where people might need transportation. Maybe there are new routes we can offer or places we can expand to.
* Most of the orders are coming from/reaching to states like Maharashtra, Karnataka, Haryana and Tamil Nadu. The existing corridors can be further enhanced to improve the penetration in these areas.
