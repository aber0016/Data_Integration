# Data_Integration_Transformation

This project integrates several datasets into one single schema and finds and fixes possible problems in the data. The seven integrate datasets contain information on the features of a property listed by a real estate agency and were in CSV, XML, JSON, SHAPE and GTFS formate. The final result of this integration of different data sources is a pandas data frame, saved in CSV format and named all_data_df with the columns:

- Property_id
- lat
- lng
- addr_street
- suburb
- price
- property_type
- year
- bedrooms
- bathrooms
- parking_space
- Shopping_center_id
- Distance_to_sc
- Train_station_id
- Distance_to_train_station
- travel_min_to_CBD
- Transfer_flag
- Hospital_id
- Distance_to_hospital
- Supermarket_id
- Distance_to_supermaket
