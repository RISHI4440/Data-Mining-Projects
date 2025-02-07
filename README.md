# Data Mining Vacant and Abandoned Buildings in Chicago

**Introduction:**
In any urban center across the globe, Vacant and Abandoned buildings present significant challenges, such as contributing to urban decay posing safety risks, and reducing property values. In response to these challenges, my proposed data mining project aims to unravel the complex narrative of vacant and abandoned buildings in Chicago, focusing on their impact on Housing Quality and finding Vacant properties owned by Individuals and Corporations. I am planning to do it by leveraging a comprehensive dataset provided by Chicago’s Administrative Hearings and Finance Dept.

**PART-1**

**Dataset Description and Significance:**
The dataset at the heart of this project comprises detailed records of violations related to vacant and abandoned buildings, as reported by the Chicago administration. Each record in the dataset includes several key columns including Docket and Violation Numbers, Issued Date and Last Hearing Date, Issuing Department, Property Address, Violation Type, Entity or Person(s), Disposition Description, Financial s, and Geospatial Data. This dataset is significant for its depth and breadth, offering a rich foundation for analysis.

https://data.cityofchicago.org/Buildings/Vacant-and-Abandoned-Buildings-Violations/kc9i-wq85/about_data

**Findings**

Analyzing Chicago's vacant and abandoned building dataset from 2002 to 2023 reveals significant insights into the city's urban decay and housing quality issues. The number of vacant buildings was relatively low between 2002 and 2006 but began to increase sharply after 2006, reaching a peak in 2014. Fortunately, since 2015, there has been a steady decline in these numbers, suggesting improvements in urban management or changes in economic conditions.

A noteworthy finding from the dataset is that corporate ownership dominates individual ownership in these properties, with major banks like Bank of America, US Bank, and JP Morgan Chase being the top owners. This pattern points to the possible role of financial institutions in the proliferation and management of vacant properties.

Geographically, the vacant and abandoned buildings are predominantly found in the west and south sides of Chicago. Specifically, neighborhoods such as West and East Garfield Park, Humboldt Park, and North Lawndale in the west, and areas like Chatham Park, West Englewood, and along major streets like 119th and 83rd in the south, are most affected. These regions, historically underserved, continue to face challenges that are exacerbated by the presence of neglected properties, thereby influencing the overall housing quality and contributing to the ongoing urban decay.

This comprehensive analysis underscores the importance of targeted policy interventions and community engagement to address the root causes of property abandonment and its cascading effects on community health and safety.

**PART-2**

The 2nd Dataset we are using is CDPH Environmental Complaints 

CDPH complaint types are “Abandoned Site”, “Air Pollution Work Order”, “Asbestos Work Order”, “Construction and Demolition”, “Toxics Hazardous Materials Work Order”, ”Illegal Dumping Work Order”, “Noise Complaint”, “Permits Issued by DOE Work Order”, “Recycling Work Order”, “Service Stations/Storage Tanks Work Order”, “Vehicle Idling Work Order”, and “Water Pollution.”

https://data.cityofchicago.org/Environment-Sustainable-Development/CDPH-Environmental-Complaints/fypr-ksnz/about_data



**Finding**

Through comprehensive analysis of the CDPH Environmental Complaints dataset, several significant insights have emerged. Firstly, spatial distribution analysis revealed that the majority of complaints originate from the west (120%), followed by the south (90%), north (81%), and least from the east (19%) sides of the city. Secondly, categorization by complaint type depicted air pollution as the predominant issue (46%), followed by noise complaints (23%) and construction/demolition concerns (14.5%). Lastly, examination of correlation between Vacant & Abandoned Buildings and CDPH Environmental Complaints unveiled minimal association, suggesting other factors contribute more substantially to building abandonment. Surprisingly, there was minimal correlation between vacant buildings and environmental complaints, suggesting that other factors may contribute to building abandonment. Our visualizations, including bar graphs and pie charts, vividly illustrate these trends and provide valuable insights for urban planners and policymakers.


**Correlation between Vacant & Abandoned Buildings and CDPH Environmental Complaints.**

The heatmap overlay of Vacant & Abandoned Building Violations and CDPH Environmental Complaints on OpenStreetMap revealed a surprising discovery. Despite expectations, there appears to be a minimal correlation between these datasets, OpenStreetMap distinctly illustrates the limited correlation between Vacant & Abandoned Buildings and CDPH Environmental Complaints datasets. This suggests that environmental complaints may not be the primary driver of building abandonment in Chicago, challenging conventional assumptions about urban decay. Despite prevalent environmental concerns, such as air pollution and noise complaints, their impact on building abandonment remains negligible.


**FINAL THOUGHTS**
The exploration into vacant and abandoned buildings in Chicago has been a journey of uncovering the city's urban landscape and its challenges. Leveraging a robust dataset provided by Chicago's Administrative Hearings and Finance Department, this project sought to dissect the complex narrative surrounding these neglected properties. Milestone 3 unearthed crucial insights, revealing a significant increase in vacant buildings post-2006, with corporate entities emerging as dominant property owners. Geospatial analysis pinpointed clusters of abandonment primarily in the west and south sides of Chicago, underscoring the socio-economic disparities exacerbating urban decay. These findings underscored the imperative for targeted interventions to mitigate the cascading effects of property abandonment on community well-being.

Transitioning to Milestone 4, the integration of the CDPH Environmental Complaints dataset expanded the scope of inquiry. This new dataset shed light on environmental concerns plaguing Chicago, ranging from air pollution to noise complaints. Spatial distribution analysis showcased a prevalence of complaints emanating from the west side, with air pollution emerging as the most prominent issue. However, the correlation analysis between vacant buildings and environmental complaints yielded surprising results minimal association was found, challenging preconceived notions about the drivers of urban decay. Visualizations, including bar graphs and pie charts, vividly depicted these trends, offering valuable insights for urban planners and policymakers.

The process involved in Milestone 4 encompassed meticulous data handling, from collection to cleaning and exploratory analysis. Addressing missing values, removing duplicates, and rectifying errors ensured the integrity of the analysis. Exploratory data analysis, characterized by the visualization of data using various techniques such as pie charts, bar graphs, and Folium's OpenStreet Heat Map, facilitated the extraction of meaningful insights. Documentation and reporting crystallized these findings into a coherent narrative, culminating in the unveiling of a paradigm-shifting revelation the limited correlation between environmental complaints and building abandonment.

Key findings from Milestone 4 challenged conventional wisdom, highlighting the nuanced dynamics shaping urban decay. Despite prevalent environmental concerns, their impact on building abandonment proved marginal, suggesting a more multifaceted interplay of factors. The heatmap overlay on OpenStreetMap starkly illustrated this divergence, reframing the discourse on urban decay in Chicago. This revelation underscores the need for holistic approaches to address the underlying socio-economic disparities fueling property abandonment.

In conclusion, the data mining journey through Chicago's vacant and abandoned buildings has been illuminating, revealing both the intricacies of urban decay and the limitations of conventional wisdom. From the proliferation of corporate-owned vacant properties to the surprising lack of correlation between environmental complaints and building abandonment, each milestone has deepened our understanding of the city's complex landscape. As we navigate the implications of these findings, the imperative remains clear to craft targeted interventions that address the root causes of urban decay and foster inclusive, resilient communities.




