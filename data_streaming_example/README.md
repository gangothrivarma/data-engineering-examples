# Streaming Data Pipeline Example
## Intro to Streaming Data
**Data streaming** is the process of transmitting a continuous flow of data (a.k.a. streams) typical fed into stream processing software to derive valuable insights.

**Streaming data** is data that is generated continuously by thousands of data sources, which typically send in the data records simultaneously, and in small sizes (order of Kilobytes). 

Streaming data includes a wide variety of data such as log files generated by customers using your mobile or web applications, ecommerce purchases, in-game player activity, information from social networks, financial trading floors, or geospatial services, and telemetry from connected devices or instrumentation in data centers.

### Examples of streaming data
- Sensors in transportation vehicles, industrial equipment, and farm machinery send data to a streaming application. The application monitors performance, detects any potential defects in advance, and places a spare part order automatically preventing equipment down time.
- A financial institution tracks changes in the stock market in real time, computes value-at-risk, and automatically rebalances portfolios based on stock price movements.
- A real-estate website tracks a subset of data from consumers’ mobile devices and makes real-time property recommendations of properties to visit based on their geo-location.
- A solar power company has to maintain power throughput for its customers, or pay penalties. It implemented a streaming data application that monitors of all of panels in the field, and schedules service in real time, thereby minimizing the periods of low throughput from each panel and the associated penalty payouts.
- A media publisher streams billions of clickstream records from its online properties, aggregates and enriches the data with demographic information about users, and optimizes content placement on its site, delivering relevancy and better experience to its audience.
- An online gaming company collects streaming data about player-game interactions, and feeds the data into its gaming platform. It then analyzes the data in real-time, offers incentives and dynamic experiences to engage its players

## Log Analysis - Overview
This data streaming example pipeline will be dealing with logs related to online systems.

### Use Cases of log analysis
- Improve security against threats​
- System Troubleshooting​
- Performance Optimization​
- IP Intelligence​
- Targeted Marketing Advertisements based on traffic

## Architecture
![Architecture](https://github.com/chaitanyakasaraneni/streamingDataPipeline/blob/code/imgs/architecture.png)

## Technologies Used
- Python (3.6 & above): Source Code
- GCP
	- Cloud Storage​: Storing Code and running using cloud console
	- Cloud Pub/Sub: Cloud messaging service for transforming and storing
	- BigQuery: Storing Transformed Data
	- Cloud DataFlow (with Apache Beam): Tool to create pipelines for streaming or batch processing. It is particularly useful for parallel processing and is suited to perform Extract, Transform, and Load (ETL) tasks
- Google Data Studio​: Visualization and Dashboards

## [Link to example repository](https://github.com/chaitanyakasaraneni/streamingDataPipeline)
