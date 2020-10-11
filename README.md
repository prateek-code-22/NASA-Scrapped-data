# NASA Scrapped data
In this repository I have used six different NASA Open APIs to collect data and images.

## [NASA Open APIs used](https://api.nasa.gov/):
1. Astronomy Picture of the Day(APOD)
2. MARS ROVER PHOTOS
3. Earth Polychromatic Imaging Camera (EPIC) 
4. Insight (MARS WEATHER REPORT)
5. Asteroids-NeoWs (Near Earth Object Web Service)
6. EARTH API


## 1. [Astronomy Picture of the Day (APOD)](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/scrap(APOD).ipynb)
With the help of this api I have retrieve the data like **date** of image taken ,**Title** of image , **Explanation/details** about image and downloaded the images of 21st june of last two decades View [here](https://github.com/prateek-code-22/NASA-Scrapped-data/tree/master/APOD%20(images)).

Output:
![Alt apod result](/Output_images/Apod.jpg)


## 2. [Mars Rover Photos](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/Curiosity_Sol.ipynb)
Using this api I have retrieve the images from three different cameras **NAVCAM** , **MAST**, **MAHLI** of Curiosity rover.

Images:
![alt curiosity](/Output_images/20201011_120047.jpg)


## 3. [Earth Polychromatic Imaging Camera (EPIC)](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/EPIC_api.ipynb)
This api returns daily images taken by DSCOVR's Earth Polychromatic Imaging Camera (EPIC) instrument.

![alt epic](/Output_images/epic.jpg)


## 4. [Insight (MARS WEATHER REPORT)](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/Insight_api.ipynb)
This api return the wheather report of mars.This API provides per Sol summary data of last one week.

sample image:
![alt weather](/Output_images/weather.jpg)


## 5. [Asteroids-NeoWs (Near Earth Object Web Service)](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/Neows_Scrap.ipynb)
Using NASA NEOWS API we can Extract Links , **Number of elements passed** , **Near earth object** like informations for particular Asteroids passed near earth.

Output:
![alt img](/Output_images/neows.jpg)

## 6. [EARTH API](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/Earth_api.ipynb)
This api gives informations like **date**, **id**, **resource**, **service_version**, **url** for your input data (latitude and longitude cordinates , date , dimension of image).

![alt earth](/Output_images/earth.jpg)


## Conclusion:
   Using these APIs large text data which are in json format can be converted into csv files and the images can be used to create datasets for exploration.
   for more [Reference](https://github.com/prateek-code-22/NASA-Scrapped-data/blob/master/More_info.md)

If you finds this repository helpful then add a :star: to it. 

Thanks :smiley:
