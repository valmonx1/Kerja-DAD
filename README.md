# Kerja-DAD
PROJECT DETAIL :

#TITLE	Weather Application

ABOUT PROJECT 	Application that can detect humidity in a city by input the city name in the application
LANGUAGE USE 	  Java and xml
PLATFORM USE 	  Android Studio 
API USE 	      OpenWeatherMap
                http://api.openweathermap.org/data/2.5/weather
GITHUB INK	    https://github.com/valmonx1/Kerja-DAD


#Screenshot Application :



file:///C:/Users/Nabil/Downloads/WhatsApp%20Image%202018-11-06%20at%209.38.13%20AM.jpeg













#How To Use Application :

1. Click on change city and put on your desire city name 
2. The weather application will show your city weather as shown in the screenshot 
above.


#Parameter that Api Receive : 

#Api call :
api.openweathermap.org/data/2.5/weather?q={city name}
Parameter : 
City


#Example of Api call :
http://api.openweathermap.org/data/2.5/weather?q=putrajaya&appid=70f8109bc07233e1950aedd164a172dc

Link to openweather	       http://api.openweathermap.org/data/2.5/weather
City name 	               ?q=putrajaya
Api key from openweather 	 70f8109bc07233e1950aedd164a172dc


#Responses Api that return in JSON :

{"coord":{"lon":101.68,"lat":2.91},"weather":[{"id":701,"main":"Mist","description":"mist","icon":"50n"}],"base":"stations","main":{"temp":297.64,"pressure":1008,"humidity":94,"temp_min":297.15,"temp_max":298.15},"visibility":3000,"wind":{"speed":1.5,"deg":40},"clouds":{"all":75},"dt":1541458800,"sys":{"type":1,"id":8132,"message":0.0054,"country":"MY","sunrise":1541372201,"sunset":1541415419},"id":6697380,"name":"Putrajaya","cod":200}
