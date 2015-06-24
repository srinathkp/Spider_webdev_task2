# Spider_webdev_task2
without using laravel

Hello!

I'm Srinath.My ROLL NO:110114084.

Since I didn't have proper internet connection for over a month, I wasn't really able to make commits for this task.I have done this 
task without using laravel as I wanted to learn procedural php .Very Soon,In 2-3 days,I'll submit the same task using the framework.

I have used the PHP+Apache server for this task.I have used the MYSQLdatabase.
The Database contains the following fields:

id
Latitude
longitude
description
time-To keep track of data's time period
I have attached the DB DETAILS named registrationspider.sql with my code files.
And I have used many script sources and URL's which are as follows:
        http://maps.googleapis.com/maps/api/js;
        http://maps.googleapis.com/maps/api/geocode/json?latlng=lat,lng&sensor=true; 
        http://api.openweathermap.org/data/2.5/weather?lat=lat&lng=lng; -To determine the weather at the given latitude and longitude.

BUILD INSTRUCTIONS:

And what I have done using these is,
Initially I have loaded the google map using the api script source,and then I have made a marker
which is draggable To get the latitude and Longitude I have used the dragstart and dragend,
which enables me to get those and applying these latitude and longitude to the geocode URL
to get the city's name and the prevailing weather corresponding to the latitude and longitude.
And then I have loaded these variables in my databse using php.
By retrieving the data I have again loaded a map in which I have attached markers
with the places that visited within an hour.

                                                                            Thank You!
