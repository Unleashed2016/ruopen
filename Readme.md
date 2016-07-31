## R U Open

![ru open logo](img/RU Open.png)

**An augmented reality app to locate services around you that are open.**

description

### Augmented reality based geolocation, routing and navigation:

We have developed the proof-of-concept of a browser-based Augmented Reality app to locate services which are open at the time of use (of the app) around the user. This kind of app would be normally developed using native APIs of the mobile phone OS (Android/iOS/Windows Mobile) and is extremely complex. The key concept is to use the mobile device sensors, mainly accelerometer, magnetometer, GPS, camera to establish the current location, orientation and point-of-view (in terms of camera viewport) of the device. On top, of the camera feed on the phone screen, data is superimposed in transparent/semi-transparent layers. This is done by creating virtual markers based on geolocated dataset(s) and using algorithms to determine the approximate distance and direction of heading for the marker in relation to the user's (and phone camera's) point-of-view. Navigation features can be added by using the phone's motion sensors to determine direction of movement as well.

Since our proof-of-concept has been developed within the time constraints of Unleashed 2016, Adelaide and Govhack, it has been developed using HTML5 geolocation (GPS), the orientation API (accelerometer) and WebGL (GPU). This PoC currently requires a standards compliant mobile browser (e.g. Firefox on Android). iOS does not currently support WebGL or WebRTC and has not implemented the DeviceOrientation API correctly. Please see [this post to the W3C GeoLocation Working Group link](http://http://lists.w3.org/Archives/Public/public-geolocation/2014Jan/0000.html) for more detailed information. [Awe.js link] (https://github.com/buildar/awe.js/) has been used for building the app. A transparent overlay of Google Maps has been used to display roads and locate markers on top of the camera feed for simplicity.

Team name: Bob's gang

Team members: Matt Cejko, Martin Nobis, Muhammad Pavel, Mizanur Rahman, Asheshwor Shrestha, Oshim Somers

Source repository url: https://github.com/Unleashed2016/ruopen

Video url:

Hackerspace url: https://2016.hackerspace.govhack.org/content/r-u-open

### Local Event Location:
Adelaide

### Datasets Used:

* Outdoor dining permits - Adelaide City Council data provided via data.sa https://data.sa.gov.au/data/dataset/outdoor-dining-permits This data-set provides the opening hours of dining facilities in Adelaide City. Location extracted from address and opening times extracted from 'opening times' text description.

* 3D Model of the City of Adelaide data provided by data.sa
https://data.sa.gov.au/data/dataset/3d-model This dataset provides the visualization of building heights in augmented reality view on our app.

* Hospital locations in SA (SA Public and Private Hospitals Locations): https://data.sa.gov.au/data/dataset/sa-health-hospitals-locations Location of hospitals will be used to get directions to app users using maps and augmented reality. Opening times will be added to enhance the data-set.

* RSS feed of events that are planned in the Adelaide City Council area provided by ACC https://data.sa.gov.au/data/dataset/events The events RSS feed will provide event locaiton and timings to app users.


