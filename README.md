# GinyuForce

This repository stores our code for the group project in the course AA.

The correspondig datasets are stored on sciebo: https://uni-koeln.sciebo.de/s/B7RIXQi3bXxQFlZ

## Milestone 2
Please look at the main branch for milestone 2. We have distributed the different tasks into different notebooks:

Data cleanup and preparation:
- data_prep_charging_set.ipynb
- data_prep_weather_set.ipynb

Descriptive analysis:
- visualization_charging_set.ipynb
- visualization_weather_set.ipynb

Modeling:
- modeling.ipynb (not runnable yet, currently only preparation)

Cluster analysis:
- cluster.ipynb

![WhatsApp Image 2024-12-23 at 16 05 52](https://github.com/user-attachments/assets/fb413fb5-69b4-48b7-b640-2aa242f20314)


# Current structure of data cleanup structure
- overview of raw data
- check validity of columns
    - remove "Unnamed 0" column
    - split "userInputs" columns
- check for duplicates
- check for Na-values (only non-time data, we want to treat time-data differently)
- create isRegistered
- handle time-data
- check data types of all features
- check ranges of all features
- identify outliers
- calculate utilization
    
