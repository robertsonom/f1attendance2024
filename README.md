# Project Description

-----

###### Owen Robertson (*robertsonom*)

##### Project Name

F1 Track Attendance and Winners in 2024

##### Introduction

This map shows graduated symbols on top of the race tracks (with available attendance data) from the 2024 Formula 1 season, with the symbols being scaled based on how many people attended that race during the weekend. Note that the numbers are quite high because race tracks typically count attendance as ticket scans across the entire race weekend rather than unique persons in attendance throughout the weekend. This is because it is common for tracks to sell tickets individually per day and because it is common for attendees to only attend certain days of the weekend. More information about the track and who won the race is also listed. The purpose and objective of this map is to accurately display the relative attendance numbers of each F1 race of the 2024 season. In the article, the data is displayed in a simple bar graph form, but displaying the data in a geographic format with graduated symbols helps not only add context but helpful visualization to the original numbers. 

##### Functions

The map has all of the normal functionality of a normal web map (zoom, legend, sources, scale, navigation, etc.) but also has some extra features that go along with the data. These functions a mouseover interaction when you hover over a data point. The data point turns from the default F1 red color into the official team color of the team that won the respective race. Furthermore, clicking on the symbol displays a list of basic information about the symbool such as which race the symbol is associated with, the attendance numbers, and winner information. 

##### Libraries

* assets (folder)
    * f1data2.geojson (geojson file regarding the symbols and associated data)
* index.html (main code)
* README.<nolink>md (readme file)

##### Sources

* https://www.blackbookmotorsport.com/features/f1-2024-numbers-season-review-viewership-attendance-commercial/ 
(Reference article / Used for attendance numbers)
* https://en.wikipedia.org/wiki/List_of_Formula_One_circuits 
(Used for track coordinates)
* https://geojson.io/ 
(Used for processing)