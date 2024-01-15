# GEOG486: Flow Maps and Projections

<b>Assignment Objectives:</b>
1. Create three advertisements for London Heathrow Airport (LHR) using flight origin-destination data.
2. Select and customize map projections based on each map’s purpose and overall design.
3. Use appropriate visual variables to symbolize background data and flowlines.
4. Create well-designed layouts with appropriate legends and text elements.

<b> Map 1</b><br>
The purpose of Map 1 was to visualize flight paths based on length. All flight paths arrive or depart from London Heathrow Airport and have worldwide destinations. I sought a projection that minimizes distortions to both area and distance, so I chose to utilize the Winkel Tripel projection for this first assignment and customized the standard parallel from 60 to 50 in an attempt to decrease some of the distortion affecting South America and North America. This also reduced the overall “compression effect" on the entire map. The Winkel Tripel attempts to minimize three kinds of distortions including area, direction, and distance which can make it a good choice for visualizing f light paths with destinations in different regions of the world. This projection is also well suited for world maps and provides an adequate representation of the whole world. Although it does display moderate distortion (specifically in polar regions), it minimizes distortions in middle latitudes including North America, Europe, Asia and parts of Africa, South America, and Australia. These regions are where we can see flight paths beginning or ending from. The visual differences in length remain distinct between flight paths; however, it is important to note that distance distortion does still occur. Thus, the Winkel Tripel projection should not be used if distance accuracy is the main priority of the map. <br>
<center>
![image](https://github.com/bec-in-tech/GEOG486-Flow-Mapping/assets/120440399/2476af4c-8c88-46dd-8855-738cabc5a327)</center>

<b>Map 2 </b><br>
The main objective of the second mapping activity was to highlight the abundance of flights and flight availability at LHA - no matter what time of the day, there’s a flight for you! Here, I wanted to preserve areas (but not so much distance). Thus, I chose a projection that minimizes distortion of geographic areas: the Robinson projection. The Robinson projection is designed to minimize distortion of both shape and size throughout most of the map, making it an effective projection to use for visualizing global flight paths. One of the main purposes for the Robinson projection is to create a visually appealing map of the world, so it’s a good choice for an advertisement flow map. This projection was applied to all four maps in Part 2 of the lab, and I kept the default parameters because these settings portrayed the map adequately. <br>

<center>![image](https://github.com/bec-in-tech/GEOG486-Flow-Mapping/assets/120440399/e5df4e5d-79f6-4b9f-9565-6a77bc4e3599)</center>

<b>Map 3</b><br>
For the final map, I wanted to show a unique perspective of the earth. Instead of a flat projection, I wanted to visualize the flight paths on a sphere. The Azimuthal Equidistant projection was a good choice for this because it provides a “globe-like” projection, resulting in the map’s spherical appearance while still maintaining the relative sizes of the landmasses. Although this projection results in distortions to areas, shapes, distances, and directions, the spherical projection allows the reader to grasp the geographical context of the flight paths being displayed on a “globe.” I think this projection makes the map look interesting, giving it a unique “fish-eye” appearance at first glance while simultaneously portraying London Heathrow’s worldwide reach. I discovered that making a large change to the central meridian rotated the map in a way that resulted in removing London as the central point. This also resulted in little to heavy distortion of the flight paths, with heavy distortions creating confusion and ambiguity to the map. On another note, small changes to the false easting, false northing, central meridian, and latitude of origin didn’t seem to change the projection significantly, with some of the change being either gradual or unnoticeable. In the end, I decided to maintain the default parameters for this map because the default settings visualized the map and its flight paths in a more pleasant and aesthetic manner. <br>

<center>![image](https://github.com/bec-in-tech/GEOG486-Flow-Mapping/assets/120440399/c0d6bfe2-8f34-44b7-8585-b140793e18b5)</center>


