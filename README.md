# us-traffic
Please refer to [traffic_dataset.ipynb](https://github.com/wushennn/us-traffic/blob/main/traffic_dataset.ipynb). Analysis, description and code documentation is included in the notebook :)

# Introduction (taken from notebook)

**Background**

Traffic congestion is a condition in transport that is characterised by slower speeds, longer trip times, and increased vehicular queueing. Traffic congestion on urban road networks has increased substantially, since the 1950s.

Traffic congestion has a number of negative effects:
1. Wasting time of motorists and passengers ("opportunity cost"). As a non-productive activity for most people, congestion reduces regional economic health
2. Stressed and frustrated motorists, encouraging road rage and reduced health of motorists
3. Emergencies: blocked traffic may interfere with emergency vehicles traveling to their destinations where they are urgently needed

**Objective**

This notebook aims to help better understand the US Traffic Dataset in 2015 to help with traffic management. In this notebook, analysis is focused on traffic volume. Analysis of stations and its role in traffic management are part of possible future works.

**Dataset**: [US Traffic Dataset, 2015](https://www.kaggle.com/jboysen/us-traffic-2015)
- **Context**:
Traffic management is a critical concern for policymakers, and a fascinating data question. This ~2gb dataset contains daily volumes of traffic, binned by hour. Information on flow direction and sensor placement is also included.

- **Content**:
  - Two datasets are included:

  1. dottraffic2015.txt.gz
    - daily observation of traffic volume, divided into 24 hourly bins
    - station_id, location information (geographical place), traffic flow direction, and type of road

  2. dottrafficstations_2015.txt.gz
    - deeper location and historical data on individual observation stations, cross-referenced by station_id
