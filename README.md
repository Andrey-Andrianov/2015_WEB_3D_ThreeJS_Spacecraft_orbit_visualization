# 2015_WEB_3D_ThreeJS_Spacecraft_orbit_visualization
Visualization of the Millimetron spacecraft orbit around the Lagrange point L2, java script, ThreeJS

The program is written for viewing in a browser, the language is java script, the display of 3D graphics is implemented through WebGL using the ThreeJS framework.

* Read in other languages: [English](README.md), [Russian](README.ru.md)

Screenshot:

![Screenshot](screenshots.gif)

# Table of contents
- [Installation](#Installation)
- [Short description](#Short-description)
- [Try in browser](#Try-in-browser)


# Installation

To use it, just download the MM_orbit.zip file, unpack the archive and upload it to the hosting (when you open the html page localy, it will not work - at least in Google Chrome - due to WebGL security restrictions, because resources must be taken from one domain)
Then refer either to the webgl_orbit.html to view the orbit or to the webgl_mm_model.html to view the space radio telescope model.

# Short description

This visualization demonstrates the operation of the Millimetron space telescope in orbit around the L2 libration point of the Earth-Sun system. The libration point L2 is a point of unstable equilibrium, around which, nevertheless, circular orbits are possible. This point is always in the opposite direction to the Sun and makes a yearly movement around the Earth. Therefore, in the coordinate system associated with the Earth, the orbit of the spacecraft will have a complex shape. At the same time, in the frame of reference around the libration point L2, the orbit has the usual elliptical shape.

The Coord button switches the coordinate system between coordinate systems in which either the Earth or the libration point L2 is considered fixed.

The Labels button enables or disables the display of the planes of the ecliptic, the celestial equator, and the Milky Way.

The Spacecraft/Orbit button switches between displaying the orbit and the space radio telescope model.

The rotation of the scene is carried out either by moving the mouse or by swiping on touch screens. Zoom in/out with the mouse wheel or swipe.

# Try in browser

Click the link below to see how it works in a browser:

[Orbit](https://andrey-andrianov.github.io/sites/MM_orbit/webgl_orbit.html)

[Model](https://andrey-andrianov.github.io/sites/MM_orbit/webgl_mm_model.html)

You can also watch from mobile devices. In this case, it is convenient to add the page to the home screen of the device.
