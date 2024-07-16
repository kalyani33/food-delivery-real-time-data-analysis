# food-delivery-real-time-data-analysis
Process food delivery data in real time and create dashboard for stakeholders
## Data Architecture
![new_food_del_arch](https://github.com/user-attachments/assets/2a9a39f2-3dab-4379-b98b-df2132db7e9c)


## Teck Stack
- Kinesis Data Stream
- Airflow
- PySpark Streaming
- EMR
- Redshift
- S3
- CICD with CodeBuild
- Quicksight
## Data Visualization
insert insights here
## DataWarehouse Data Modeling(Star Schema)
![dm](https://github.com/user-attachments/assets/c05681a1-2786-4002-876e-b62dd8a21d61)

### Kinesis Data Stream
- Real-time data capture:Ingest and store data streams from hundreds of thousands of data sources
- Collect and store data streams:Collect gigabytes of data per second and make it available for processing and analyzing in real time.
- Here it is important to understand why only Kinesis data streams ,why not Kinesis firehose or Kinesis Analytics.Here in this project I only want to ingest and capture data so that EMR can read the data and do the processing.
## Lessons Learned
It will be good if we find the aws service that fits to our usecase
## Next Steps
If i get some time,I'm planning to expand this project ,where I want to ingest data from mutiple data sources and analysis that data in realtime.
