# Python API Challenge

# Project Description

## Part-One: Weather API
- Create plots to show the relationship between weather variables and latitude including variables like temperature, humidity, cloudiness, and          wind speed. 
- Compute the linear regression for each of the relationships between latitude and temperature, cloudiness, humidity, and wind speed and explain the relationships for each of the variable pairs. 

## Part-Two: VacationPy
- Create a map highlighting every city in the dataframe from Part-One. 
- Filter the dataframe to only include the ideal weather conditions.
- Create a new dataframe based on these parameters and create a blank hotel column. 
- Use Geoapify API to find hotels within 10,000 meters of the coordinates in the dataframe and populate a table with these hotels. If no hotel can be found within the radius, print "No hotel found."
- Add the functionality for users to be able to hover over the map and look at the hotel name and country for those coordinates.

# Dependencies

## Weather API
-Matplotlib \
-Pandas \
-Numpy
-Requests
-Time
-Scipy.Stats
-Citipy
-Weather API Key

## VacationPy
-CSV file from Part-One
-HVPlot
-Pandas
-Requests
-Geoapify Key

## Software
-VSCode
-Python
-PythonData 3.7 Environment

## Part-One
-Generated cities from citipy
<img width="803" alt="Screenshot 2023-02-22 at 12 54 25 PM" src="https://user-images.githubusercontent.com/119909433/220730655-74a64247-fd3a-4208-a8a8-5221b0005eaf.png">

-Used Open Weather Map to get weather data from the cities listed
<img width="755" alt="Screenshot 2023-02-22 at 12 56 49 PM" src="https://user-images.githubusercontent.com/119909433/220731160-d1882b85-00cc-48a6-b483-f4887ce568ea.png">
<img width="753" alt="Screenshot 2023-02-22 at 12 57 09 PM" src="https://user-images.githubusercontent.com/119909433/220731242-6266d9b2-601e-4661-8f0a-d12f5f5e4b6f.png">

-Converted this into a dataframe and displayed the first few rows of the dataframe
<img width="808" alt="Screenshot 2023-02-22 at 12 57 59 PM" src="https://user-images.githubusercontent.com/119909433/220731420-482da3f1-1770-4434-b7b6-4196cda341ca.png">

-Exported the dataframe into a csv file
<img width="794" alt="Screenshot 2023-02-22 at 12 58 34 PM" src="https://user-images.githubusercontent.com/119909433/220731532-b073b820-77c7-450a-b122-073e502e182a.png">

-Created the scatterplots
<img width="964" alt="Screenshot 2023-02-22 at 12 59 05 PM" src="https://user-images.githubusercontent.com/119909433/220731639-e5bcedb1-20a7-4ca8-acd2-e76c88f2aa70.png">
<img width="963" alt="Screenshot 2023-02-22 at 12 59 21 PM" src="https://user-images.githubusercontent.com/119909433/220731695-100120d1-32fe-4b10-b1fa-7a89793d06fb.png"><img width="970" alt="Screenshot 2023-02-22 at 12 59 36 PM" src="https://user-images.githubusercontent.com/119909433/220731744-96bf3f36-aaba-4246-b37d-8d8474790c18.png">

-Defined a function for the linear regression
<img width="969" alt="Screenshot 2023-02-22 at 12 59 49 PM" src="https://user-images.githubusercontent.com/119909433/220731809-47b91355-11e8-42a3-97cb-c0c2c9bd7e05.png"><img width="972" alt="Screenshot 2023-02-22 at 1 00 12 PM" src="https://user-images.githubusercontent.com/119909433/220731891-e7afab44-640b-4e5f-a4cb-a6cb8a2160ad.png">

-Separated coordinates into Northern or Southern latitudes
<img width="973" alt="Screenshot 2023-02-22 at 1 00 49 PM" src="https://user-images.githubusercontent.com/119909433/220732028-bb10588c-8412-4e51-a394-2678971016c4.png">

-Ran regressions for each of the relationships
<img width="976" alt="Screenshot 2023-02-22 at 1 04 36 PM" src="https://user-images.githubusercontent.com/119909433/220732832-cf628569-6adb-4846-bdf6-498f4038c7ed.png">
<img width="969" alt="Screenshot 2023-02-22 at 1 05 08 PM" src="https://user-images.githubusercontent.com/119909433/220732898-5c9803c8-8397-4835-948c-5fc81bbb9d4c.png">
<img width="977" alt="Screenshot 2023-02-22 at 1 05 22 PM" src="https://user-images.githubusercontent.com/119909433/220732935-b8a53323-4a92-49e6-88af-9bb1592f3f8d.png">
<img width="975" alt="Screenshot 2023-02-22 at 1 05 34 PM" src="https://user-images.githubusercontent.com/119909433/220733040-76dc448b-a374-45c3-b689-6f08947749df.png">


## Part-Two
-Created a map for each of the cities after loading in the csv file
<img width="948" alt="Screenshot 2023-02-22 at 1 06 13 PM" src="https://user-images.githubusercontent.com/119909433/220733218-d840987e-95e4-4ae5-a886-e5e87a44525f.png">

-Filtered the dataframe based on ideal weather condition 
<img width="959" alt="Screenshot 2023-02-22 at 1 07 05 PM" src="https://user-images.githubusercontent.com/119909433/220733368-38904c2d-85ee-47f8-be51-949efa36b6e3.png">

-Created a new dataframe to include hotels and then located hotels within a certain radius of each city 
<img width="958" alt="Screenshot 2023-02-22 at 1 07 46 PM" src="https://user-images.githubusercontent.com/119909433/220733508-8ae8706c-019c-424e-8eef-483ec9901dc1.png">
<img width="969" alt="Screenshot 2023-02-22 at 1 08 10 PM" src="https://user-images.githubusercontent.com/119909433/220733600-3f5bfa36-a153-4d9f-b956-1db6c6d02db7.png">

-Created a functionality to where you can hover over cities and obtain the city and hotel name for that city
<img width="969" alt="Screenshot 2023-02-22 at 1 08 45 PM" src="https://user-images.githubusercontent.com/119909433/220733727-854f051c-d633-4f6d-8dbf-a3e4c97c5271.png">

# Author 
-Brittany Wright github:brittanynicole7

