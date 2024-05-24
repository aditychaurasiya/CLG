Landslides pose a significant threat to lives and infrastructure in India. To address this challenge, our project focuses on identifying optimal facility locations to mitigate the impact of landslides via response center. By strategically placing facilities in vulnerable areas, we aim to minimize the damage caused by landslides and improve disaster response efforts.
## Objective
The primary objective of our project is to minimize the cost of establishing facilities while maximizing the coverage of landslide-prone areas in India.So,I determine the locations of p facilities and their assigned clients in order to minimize the total cost of demand weighted distance between demand node and facilities. p -center problems have a specific objective function to minimize the maximum distance between each client and its assigned facility.
## Assumption
•	Despite having 1227 demand nodes, constraints have led us to focus our efforts on establishing facilities at just 15 locations. This strategic decision prioritizes quality over quantity, ensuring that each chosen site receives the attention and resources necessary for maximum impact. While we acknowledge the inability to cover all potential sites, our commitment to efficiency and excellence drives us to make a significant difference in the communities we serve. Through careful deliberation, these 15 locations have been identified as key hubs.
•	Approximate the distance between two locations on a spherical surface using the Haversine formula
## Implementation
•	NumPy, Pandas for data manipulation.
•	math for specific mathematical functions.
•	GeoPandas for geospatial representations.
•	Matplotlib for data visualization.
•	PuLP for MIP optimization.
•	Dataset is available on @data.world
## FACILITY LOCATION
The Facility Location Problem (FLP) is a classic optimization problem that determines the best location for a factory or warehouse to be placed based on geographical demands, facility costs, and transportation distances so that the demand at different demand zones is fulfilled by various facility centres with the aim with “to Minimize demand weighted distance between customers and facilities”.
A p-Median facility problem applies constraints to the limited number of facility centres out of possibles location of facilities, say p and demands of each demand zone is served by only one facility centre. As a result, customers may not be supplied by the most immediate facility, since this facility may not be able to satisfy the given customer demand.
