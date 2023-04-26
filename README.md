# Bike-Share Data Science Project

## Description
This program is an interactive console application designed to provide statistical analysis on the bikeshare data for three cities - Chicago, New York City, and Washington. It interacts with the user to filter the data by city, month, and day of the week. The program uses Pandas DataFrame to load and filter data based on user inputs. The program also provides statistics on the most frequent times of travel, the most popular stations and trips, and the total and average trip duration.

## How it works!
The program uses multiple functions and various Python libraries including Pandas, Numpy, and Time to manipulate and analyze the bikeshare data. Overall, the program is a simple but effective tool to extract insights from the bikeshare data of the three cities.
- The program starts with defining a dictionary CITY_DATA that maps the city name to the corresponding CSV file that contains the bikeshare data
- The get_filters() function is defined to get user inputs for the city, month, and day of the week. It uses a while loop to handle invalid inputs and returns these user inputs as strings.
- The load_data() function is defined to load the data for the specified city and filters the data based on the month and day of the week if applicable. It returns a Pandas DataFrame containing the filtered data.
- The time_stats(), station_stats(), trip_duration_stats(), and user_stats() functions are defined to calculate and display the corresponding statistics related to the bikeshare data. These functions use various Pandas functions to extract and calculate the required statistics and display them on the console.
- The station_stats() function includes the option of showing 5 lines of raw data at a time, a requirement of this project.
- The main() function is defined to loop through the get_filters(), load_data(), time_stats(), station_stats(), trip_duration_stats(), and user_stats() functions to analyze the bikeshare data for the specified city, month, and day of the week. It then prompts the user to restart the program or not. If the user inputs 'yes', the program starts over. If the user inputs 'no', the program exits.

## Files used
chicago.csv
new_york_city.csv
washington.csv
bikeshare3.py


## Date created
Created 4/21/2023

## Credits
Programming for Data Science with Python- Udacity NanoDegree Program
https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104