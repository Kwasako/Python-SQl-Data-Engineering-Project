# Python-SQl-Data-Engineering-Project
10Alytics Data Engineering Capstone Project Part 3

In this project, a data pipeline for the migration of the World Port Index data from an old Access database to the modern relational database management system (PostgreSQL) for GoFrieghts, a leading logistics company. From the analysis of the data, some data marts were also created. 
Project3_EL_Pipeline.ipynb is the Extract Load (EL) pipeline Python script. 
Nearest_port_jurong_island.ipynb is the Python script that creates a table in PostgreSQL database. The table contains the 5 nearest ports to Singapore's JURONG ISLAND port? (country = 'SG', port_name = 'JURONG ISLAND'). The table include the columns port_name and distance_in_meters.
country_largest_number_port.ipynb is the Python script that creates a table for the country that has the largest number of ports with a cargo_wharf? the table include the columns country and port_count.
Distressed_call_distance.ipynb is the Python script that creates a table for the nearest port with provisions, water, fuel_oil and diesel. The table contains columns country, port_name, port_latitude and port_longitude.
