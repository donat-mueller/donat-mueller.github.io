# Craft Zürich in 3D
This is an exploration project about how to build a virtual Zürich in 3D.

## Goals
Access open data to rapid prototype terrain and buildings. We need the height for the ground and for the highest point such as the roof of a building. At least one measurement point per square meter. In Switzerland we can use [LiDAR](https://www.swisstopo.admin.ch/de/wissen-fakten/geoinformation/lidar-daten.html) which provides very accurate data. Then we need the shapes for buildings and streets and a some more terrain information to layout rivers, parks and forests for example. With [OpenStreetMap](https://www.openstreetmap.org/relation/1690227#map=10/47.4276/8.6713) and [Google StreetView](https://www.google.ch/maps/@47.3860662,8.5342101,121a,35y,39.37t/data=!3m1!1e3?hl=de) we have all we need to recreate any city we want. 

![open-street-map](https://user-images.githubusercontent.com/11026671/47834795-3399f100-dda1-11e8-84ae-d2ef7fba653e.png) ![streetview](https://user-images.githubusercontent.com/11026671/47835080-7b6d4800-dda2-11e8-8b9a-1e436f9a289a.png)


The administration of Zürich provides even more accurate geometer measurements as open data. With the provided [GIS-Browser](https://maps.zh.ch) we can check what data could be useful to create the city. Then we have to extract and transform the data so that we can use it in a game engine such as Unit5 or UE4. 
But once done that our city still looks very ugly just grey blocks and roads. Most roofs can be automatically generated coz we have geometer data. But still we see no colors, materials, windows, doors, fences, balcony, water tubes. So we are missing all the details. We have neither time nor budget to let craft all that tiny stuff in 3D. 

![maya](https://user-images.githubusercontent.com/11026671/47834942-f6822e80-dda1-11e8-980c-832891336d0f.png)

But we can do better construct kind of Lego assets for typical assets found in this historical city. It is not the goal to create a 1:1 copy of Zürich. For this there are better approaches. The most striking buildings and the areas I love we craft by hand with love and in detail. But for the rest we have to develop a technique to generate facades of typical buildings for a City. I am quite sure that this mixed approach delivers a very nice and unique user experience.
