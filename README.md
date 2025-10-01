# Uber_Taxi_Data_Warehouse(Star Schema)

<img width="1194" height="666" alt="Screenshot 2025-10-01 110342" src="https://github.com/user-attachments/assets/1bbed8d7-bc8b-404d-9fb8-a135e6e97fd3" />

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai

## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

<img width="499" height="436" alt="Screenshot 2025-10-01 104544" src="https://github.com/user-attachments/assets/621e9746-51c4-4dc2-ab99-583f8ff51728" />

## Data Model (Star Schema Design)

- Fact Table: Trip-level transactions (measures like fare, tips, tolls, total).
- Dimensions: datetime_dim, passenger_count_dim, trip_distance_dim, rate_code_dim, pickup_location_dim, dropoff_location_dim, payment_type_dim.

<img width="1000" height="620" alt="Screenshot 2025-10-01 105514" src="https://github.com/user-attachments/assets/898e91f9-fe7f-42f4-85d7-19ebda56edab" />

## Creating Storage Bucket in GCP 

<img width="1230" height="208" alt="Screenshot 2025-10-01 113319" src="https://github.com/user-attachments/assets/740d1250-70d3-4356-b482-32e7673eef29" />

## Virtual Machine Instance in GCP

<img width="1562" height="209" alt="Screenshot 2025-10-01 112947" src="https://github.com/user-attachments/assets/fe76b550-3c21-452d-8134-c902bd9bb2d4" />

## Pipeline Using Mage.ai

- Data Loader
- Data Transformer
- Data Extractor

<img width="1755" height="636" alt="Screenshot 2025-10-01 111710" src="https://github.com/user-attachments/assets/3b7356fb-3221-4323-9983-4d960ed56185" />


