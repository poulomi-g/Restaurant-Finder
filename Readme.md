# RESTOFINDER

Made by: Poulomi Ganguly and Charles Ancheta

## Overview

The  program  will  load  an  Edmonton  map  and  show  a  cursor  for  the  currentlocation on the map.  Using a joystick, you will be able to move the cursor around the map andpress down the joystick to select the current location.  Then, the restaurants in the order closestto that location will be displayed on the LCD. Then you will be able to select a restaurant on thescreen using the joystick.  Pushing the joystick again will return you to the map with the selectedrestaurant at the centre of the map section. 

## Features

### Mode 0:
1. Scrollable Map: When the cursor touches the edges of the screen, the corresponding adjacent patch of the map is loaded
2. Restaurant markers: Upon touching the map, dots are drawn wherever there are restaurants present in that patch of the map according to the selected rating threshold.
3. Rating filter: Allows user to select a minimum threshold of restaurants to view
4. Sort selector: Allows user to choose between insertion sort, quick sort or both to view nearby restaurants

### Mode 1:
1. When clicking at a certain point in Mode 0, Mode 1 is initiated, showing restaurants from closest to farthest that have a greater than or equal to rating as selected in Mode 0.
2. The list of restaurants can be scrolled, showing 21 restaurants at a time and flipping through pages.
