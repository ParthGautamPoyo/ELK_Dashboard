# ELK Stack Dashboard Project
[ELK Vid.webm](https://github.com/user-attachments/assets/8580bdce-88d2-48a6-92a0-0a02821242e1)
![ELK 1](https://github.com/user-attachments/assets/0198acb0-5ee1-41bd-8def-a47937e66004)
![ELK 2](https://github.com/user-attachments/assets/a567d634-7162-4f0e-aba0-2ea20e583f18)
![ELK 3](https://github.com/user-attachments/assets/9dd93919-c9c4-4a79-9497-23de627a8594)

## Project Contributors
- Parth Gautam, PGDM-BDA, FORE School of Management (2023-25)
- Ishaan Khattar, PGDM-BDA, FORE School of Management (2023-25)
- Om Wadhwa, PGDM-BDA, FORE School of Management (2023-25)

## Project Overview
This project involved creating a dashboard using the ELK (Elasticsearch, Logstash, Kibana) stack. The dashboard visualizes and analyzes a dataset related to earthquakes from 1990 to 2023. The goal was to demonstrate data ingestion, indexing, and visualization capabilities of the ELK stack.

## Key Features
- **Dataset Used:** Earthquakes from 1990 to 2023.
- **Data Ingestion:** Data was ingested into Elasticsearch using Logstash.
- **Visualization:** Custom dashboards were created using Kibana to analyze earthquake trends, magnitudes, and geographical distributions.
- **Automation:** Configurations and scripts were used to automate the data processing pipeline.

## Technical Stack
- **Elasticsearch:** Used for indexing and storing the earthquake dataset.
- **Logstash:** Configured for data ingestion and transformation.
- **Kibana:** Used to create interactive visualizations and dashboards.

## Steps to Reproduce
1. **Setup ELK Stack:**
   - Download and set up the ELK stack.
   - Configure Elasticsearch, Logstash, and Kibana.
2. **Prepare Data:**
   - Use the provided `Earthquakes-1990-2023.csv` dataset.
   - Transform the data as necessary to ensure compatibility with Elasticsearch.
3. **Configure Logstash:**
   - Create a Logstash pipeline configuration file to ingest and parse the dataset.
   - Define the Elasticsearch index where the data will be stored.
4. **Load Data:**
   - Start the ELK stack.
   - Run Logstash to ingest the earthquake data into Elasticsearch.
5. **Create Kibana Dashboards:**
   - Connect Kibana to the Elasticsearch instance.
   - Design and configure dashboards to visualize earthquake statistics.

## Visualizations Included
- **Graph 1: Top 15 Regions with Average of Significance, Depth, and Magnitude**
- **Graph 2: Top 5 Regions Based on Average Magnitude**
- **Graph 3: Top 5 Regions Based on Number of Calamities**
- **Graph 4: Calamities Based on the Type of Records**
- **Graph 5: Top 5 Regions Based on Average Significance**
- **Graph 6: Pie of Calamities Based on Average Significance**
- **Graph 7: Top 5 Regions Based on Average Depth**
- **Graph 8: Calamities Based on the Average Depth**
- **Graph 9: Top 5 Regions Based on Average Magnitude**
- **Graph 10: Calamities Pie Chart Based on Average Magnitude**
- **Graph 11: Calamities Based on Average Depth, Significance, Magnitude**
- **Graph 12: Calamities Based on Average Depth, Significance, Magnitude (Over Time)**

## Managerial Insights

### Overall Observations
The dashboard provides critical insights into seismic activity trends, highlighting regions of interest and patterns over time. It identifies hotspots and distinguishes seismic events by type and impact. Below are the detailed insights derived from the visualizations:

**Graph 1: Top 15 Regions with Average of Significance, Depth, and Magnitude**
- The Bay of Bengal ranks highest in average significance, indicating its seismic events' critical importance.
- The South Atlantic Ocean shows the strongest earthquakes, as reflected in the highest average magnitude.
- The Peru-Ecuador border region exhibits the deepest seismic events, highlighting unique tectonic characteristics.

**Graph 2: Top 5 Regions Based on Average Magnitude**
- The South Atlantic Ocean remains the leader in average magnitude, reinforcing its reputation for strong seismic activity.

**Graph 3: Top 5 Regions Based on Number of Calamities**
- The Bay of Bengal experiences the most seismic calamities, followed by the South Indian Ocean and South Atlantic Ocean.

**Graph 4: Calamities Based on the Type of Records**
- Earthquakes are the predominant seismic events captured in the dataset.

**Graph 5: Top 5 Regions Based on Average Significance**
- The Bay of Bengal leads in average significance, contributing 18.96% of the total.
- Other notable regions include the South Atlantic Ocean (16.94%) and South Sandwich Islands (13.69%).

**Graph 6: Pie of Calamities Based on Average Significance**
- Nuclear explosions dominate the records, comprising 53.04% of the events, followed by earthquakes (17.03%).

**Graph 7: Top 5 Regions Based on Average Depth**
- The Celebes Sea registers the deepest seismic events (23.09%), with the Fiji region following (19.57%).

**Graph 8: Calamities Based on the Average Depth**
- Over time, the average depth of seismic events has shown a decreasing trend.

**Graph 9: Top 5 Regions Based on Average Magnitude**
- The Bay of Bengal also shows a high average magnitude (19.08%), alongside the South Shetland Islands and Peru-Ecuador border region.

**Graph 10: Calamities Pie Chart Based on Average Magnitude**
- Similar to significance, nuclear explosions lead in average magnitude (18.41%), followed by earthquakes (13.84%).

**Graph 11: Calamities Based on Average Depth, Significance, Magnitude**
- The "Others" category dominates in terms of average depth, significance, and magnitude.
- Explosions also score high across these parameters.

**Graph 12: Calamities Based on Average Depth, Significance, Magnitude (Over Time)**
- A decreasing trend in average depth contrasts with an increase in average significance over time, while the average magnitude remains stable.

### Key Takeaways
1. **The Bay of Bengal** is identified as a critical hotspot for seismic activity.
2. **Nuclear explosions** heavily influence data, suggesting the need for event-type-specific analysis.
3. **Shallower seismic events** are becoming more common, with implications for disaster preparedness and infrastructure resilience.

## Challenges Faced
- Optimizing Logstash pipelines for large datasets.
- Designing intuitive and effective visualizations in Kibana.
- Ensuring the scalability of the Elasticsearch indices.

## Lessons Learned
- Practical implementation of ELK stack components.
- Effective use of Kibana for data storytelling.
- Importance of preprocessing and cleaning data before ingestion.

## Future Improvements
- Include real-time data streaming for earthquake monitoring.
- Enhance visualizations with additional layers of analysis.
- Implement alerts for specific earthquake conditions using Elasticsearch queries.

---
