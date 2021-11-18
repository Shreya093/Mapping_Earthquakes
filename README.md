# Mapping_Earthquakes


## Project Overview 

The objective of this project is to gather earthquake GeoJSON data from the USGS API, create and explore interactive maps of earthquakes around the world. The earthquake data is represented on the maps in relation to the tectonic plates location on the earth, and according to each earthquake's magnitude.

## Main Objectives

1. Create a branch from the main branch on GitHub.
2. Add, commit, and push data to a GitHub branch.
3. Merge newly created branches with the main branch on GitHub.
4. Retrieve data from a GeoJSON file.
5. Make API requests to a server to host geographical maps.
6. Populate geographical maps with GeoJSON data using JavaScript and the Data-Driven Documents (D3) library.
7. Add multiple map layers to geographical maps using Leaflet control plugins to add user interface controls.
8. Use JavaScript ES6 functions to add GeoJSON data, features, and interactivity to maps.
9. Render maps on a local server.


## Results 

### Deliverable-1 : Add Tectonic Plate Data

Tectonic plate data was collected from a GitHub user who uploaded a GeoJSON file contining the boundaries of tectonic plates around the world. Adding this data as another layer to the earthquake map allows the user to toggle visibility of the fault lines and earthquake data. There are also three viewing layers available for the map: Street view, Satellite view, and Dark view.

<img width="1440" alt="del1" src="https://user-images.githubusercontent.com/88418201/142499305-62ac80d6-9a69-4d22-94e8-f487724b7fe0.png">


### Deliverable-2 : Add Major Earthquake Data

Using the GeoJSON Summary Feed we collected worldwide locations with major earthquakes in the past 7 days. We also created a legend at bottom right of the map which depicts the severity of the earthquake's around the world.

<img width="1440" alt="del2" src="https://user-images.githubusercontent.com/88418201/142499844-b04ffde6-a8f8-4194-b621-89d9671d6f73.png">

### Deliverable-3 : Add an Additional Map

Using Leaflet.js and Map Styles we have created an additional overlay to view our maps in "Dark mode". 

<img width="1440" alt="dark" src="https://user-images.githubusercontent.com/88418201/142505078-9622ca47-ec75-4e93-82c5-99e24042fb89.png">

Also we can switch to the Satellite view of the map.

<img width="1440" alt="sattelite" src="https://user-images.githubusercontent.com/88418201/142505086-1fa09e47-d2cb-44bf-b446-1600c5d0d434.png">

**Note** : By opening the index.html file on the command line by giving "python -m http.server" command we get the below as the default view of the webpage in the local host server.

<img width="1440" alt="default" src="https://user-images.githubusercontent.com/88418201/142505494-8424afdd-854c-45c2-86e9-1a3ba144a6a2.png">

