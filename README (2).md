Weather Data Analysis

About

Weather data plays a crucial role in our daily lives and various industries, from agriculture to transportation and emergency preparedness. Understanding and effectively utilizing weather data can help individuals and organizations make informed decisions, improve safety, and optimize operations.

Purposes Of The Project

Weather data has numerous applications across various industries and activities, including:

a. Agriculture: Farmers use weather data to schedule irrigation, plan planting and harvesting, and mitigate the impact of extreme weather on crops.

b. Transportation: Airlines, shipping companies, and road networks rely on weather data to optimize routes, avoid hazardous conditions, and ensure passenger safety.

c. Renewable Energy: Wind and solar energy generation depend on weather data to predict energy production and manage power grids efficiently.

d. Disaster Preparedness: Weather data is vital for early warning systems and emergency response planning during hurricanes, floods, and other severe weather events.

e. Tourism: Tour operators and travelers use weather forecasts to plan outdoor activities and make the most of their trips.



About Data


Weather data encompasses a wide range of information collected from various sources, including meteorological stations, satellites, weather balloons, and weather radars. The key types of weather data include:

a. Temperature: Information about the current and forecasted temperature, which impacts clothing choices, heating and cooling needs, and agricultural practices.

b. Precipitation: Data on rainfall, snowfall, and other forms of precipitation, critical for water resource management, flood forecasting, and agricultural planning.

c. Humidity: Measures the amount of moisture in the air, influencing human comfort, crop health, and weather patterns.

d. Wind Speed and Direction: Wind data is vital for aviation, renewable energy generation, and understanding weather patterns.

e. Atmospheric Pressure: Information about the pressure exerted by the atmosphere, useful for weather predictions and altimeter settings for aviation.

f. Cloud Cover: Indicates the fraction of the sky covered by clouds and helps determine potential rainfall and solar radiation.

g. UV Index: Measures the strength of ultraviolet radiation from the sun, important for skin protection and outdoor activities.



Approach Used

Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.

Feature Engineering: This will help use generate some new columns from existing ones.

Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.

The commands that we used in this project :

* head() - It shows the first N rows in the data (by default, N=5).
* shape - It shows the total no. of rows and no. of columns of the dataframe
* index - This attribute provides the index of the dataframe
* columns - It shows the name of each column
* dtypes - It shows the data-type of each column
* unique() - In a column, it shows all the unique values. It can be applied on a single column only, not on the whole dataframe.
* nunique() - It shows the total no. of unique values in each column. It can be applied on a single column as well as on the whole dataframe.
* count - It shows the total no. of non-null values in each column. It can be applied on a single column as well as on the whole dataframe.
* value_counts - In a column, it shows all the unique values with their count. It can be applied on a single column only.
* info() - Provides basic information about the dataframe.



Business Questions To Answer

Q. 1)  Find all the unique 'Wind Speed' values in the data.?

Q. 2) Find the number of times when the 'Weather is exactly Clear'.?

Q. 3) Find the number of times when the 'Wind Speed was exactly 4 km/h'.?

Q. 4) Find out all the Null Values in the data.?

Q. 5) Rename the column name 'Weather' of the dataframe to 'Weather Condition'.?

Q. 6) What is the mean 'Visibility' ?

Q. 7) What is the Standard Deviation of 'Pressure'  in this data?

Q. 8) What is the Variance of 'Relative Humidity' in this data ?

Q. 9) Find all instances when 'Snow' was recorded.?

Q. 10) Find all instances when 'Wind Speed is above 24' and 'Visibility is 25'.?

Q. 11) What is the Mean value of each column against each 'Weather Condition ?

Q. 12) What is the Minimum & Maximum value of each column against each 'Weather Condition ?

Q. 13) Show all the Records where Weather Condition is Fog.?

Q. 14) Find all instances when 'Weather is Clear' or 'Visibility is above 40'.?

Q. 15) Find all instances when :
A. 'Weather is Clear' and 'Relative Humidity is greater than 50'
or
B. 'Visibility is above 40'





