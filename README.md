# NASADataViewer
This is a mendix based application that consumes REST APIs published by NASA. This app is created to view the data from NASA servers.

This App is hosted on Mendix Cloud.
https://nasadataviewer-sandbox.mxapps.io/

Usage of this app to just view the data published by NASA. Details of the published APIs - https://api.nasa.gov/ > BrowseAPI

Currently implemented APIs in this project
APOD - Astronomy Picture of the Day
Mars Rover Photos - Image data gathered by NASA's Curiosity, Opportunity, and Spirit rovers on Mars

# Navigation
Clicking on the image of the homepage will take you to different options available in the App.
Click on Mars Rover Photos option

For Example put the below query:
Sol (Mars Day) = 1000
Earth Date = Blank
Rover Name = Curiosity
Camera = Front Hazard Avoidance Camera
Page = 1

Some results will be shown. This basically shows Photos taken by Curiosity Rover by Front Hazard Avoidance Camera on 1000th day after landing on Mars.

Now change Sol(Mars Day) = 100 and keep everything as it is. This will show Photos taken by Curiosity Rover by Front Hazard Avoidance Camera on 100th day after landing on Mars.

All other options are still in progress.
