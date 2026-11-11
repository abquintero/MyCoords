# MyCoords

MyCoords is an end-to-end vehicle tracking system developed as a university project. It integrates an Android mobile application, cloud-based infrastructure, and a web mapping interface to collect, transmit, store, and visualize vehicle location and operational data.

The system uses an Android application developed in Kotlin to retrieve GPS coordinates and transmit them periodically via UDP to a Node.js backend hosted on AWS EC2. Data is stored in a MySQL database hosted on Amazon RDS and displayed through an interactive map built with Leaflet.

## Key features:
- GPS location tracking and periodic coordinate transmission.
- Cloud-based data processing and storage using AWS.
- Interactive geospatial visualization with Leaflet.
- Historical location tracking with access to the last 24 hours of records.
- Integration of vehicle operational parameters, including RPM, speed, and acceleration.

**Technologies:** Kotlin, Android Studio, JavaScript, Node.js, AWS EC2, Amazon RDS, MySQL, UDP, Leaflet.

[![Presentación de MyCoords](https://img.youtube.com/vi/_p5CVLkJtBA/0.jpg)](https://www.youtube.com/watch?v=_p5CVLkJtBA)
