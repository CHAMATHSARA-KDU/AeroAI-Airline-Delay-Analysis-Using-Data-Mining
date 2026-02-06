# AeroAI-Airline-Delay-Analysis-Using-Data-Mining
AeroAI: Airline Delay Analysis Using Data Mining
Overview

AeroAI is a data mining project that explores flight delays across U.S. airlines during December 2019 and 2020. Using real-world data from the Bureau of Transportation Statistics, this study applies K-Means clustering to identify patterns and classify airlines based on their delay performance.

The analysis helps uncover key causes of flight delays, including weather, air traffic congestion, and operational inefficiencies. Insights from this study can assist airlines, policymakers, and airport authorities in improving flight scheduling and reducing delays.

Objectives

Identify the principal causes of airline delays.

Cluster airlines based on delay characteristics.

Provide data-driven recommendations to enhance punctuality.

Research Question:

“What were the principal factors that contributed to airline delays during December 2019 and 2020?”

⚙️ Methodology
1. Data Preparation

Imported and inspected dataset in R

Removed missing values using na.omit()

Normalized numerical variables using Min–Max scaling

2. Data Mining Techniques

Distance Matrix Computation using Euclidean distance

K-Means Clustering to group airlines

Elbow Method to determine optimal clusters (K = 3)

Cluster Visualization with ggplot2, pheatmap, and factoextra

📊 Results
Identified Airline Clusters
Cluster	Characteristics	Delay Causes
Cluster 1	High-delay airlines	Late aircraft & NAS delays
Cluster 2	Best on-time performance	Minimal delays
Cluster 3	Moderate-delay airlines	Weather & NAS delays
Key Findings

Late Aircraft Delays were the most common cause.

Carrier-Related Issues (crew & maintenance) significantly contributed to delays.

NAS Delays affected most airlines but to varying degrees.

💡 Insights & Recommendations

Cluster 1 Airlines: Improve turnaround and crew scheduling.

Cluster 2 Airlines: Maintain existing efficiency — benchmark for others.

Cluster 3 Airlines: Optimize scheduling and monitor weather-based disruptions.

Future improvements may include:

Incorporating real-time flight and weather data

Testing hierarchical or DBSCAN clustering for better segmentation

Expanding dataset across multiple years

🌍 Impact
Airline Industry

Reduced financial losses through optimized operations.

Improved customer satisfaction via timely flights.

Public Sector

Enhanced air traffic management and policy development.

Community

More reliable travel experiences and reduced carbon emissions.

🧠 Tools & Technologies

Language: R

Libraries: ggplot2, pheatmap, factoextra, cluster

Techniques: Clustering, Normalization, Distance Matrix, Visualization

📈 Conclusion

The K-Means clustering model effectively categorized airlines into three performance groups, revealing that late aircraft and carrier-related delays were the primary causes of disruptions.
This data-driven approach demonstrates how data mining can enhance airline operations, reduce delays, and improve passenger satisfaction.

🔗 Reference

OpenIntro:[ Airline Delay Data](https://www.openintro.org/data/index.php?data=airline_delay)
