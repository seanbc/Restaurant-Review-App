Responsive Restaurant Review App

Project Overview:
Responsive Restaurant Review App is a project required to complete the Udacity Front-End Development Nanodegree Program. The project converts a static webpage to a mobile-ready responsive web application, improves site accessibility and adds a service worker. The maps displayed in the app are from Mapbox, with the project using a Mapbox key.

How to Start the Application:
Start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this:
In a terminal, check the version of Python you have: python -V. If you have Python 2.x, spin up the server with python -m SimpleHTTPServer 8000 (or some other port, if port 8000 is already in use.) For Python 3.x, you can use python3 -m http.server 8000. If you don't have Python installed, navigate to Python's website to download and install the software.
Note - For Windows systems, Python 3.x is installed as python by default. To start a Python 3.x server, you can simply enter python -m http.server 8000.
With your server running, visit the site: http://localhost:8000 to access the site

When the application is opened, users can see a map with markers, pointing to restaurants located in various neighborhoods of NYC. Using a dropdown menu, users can choose a particular neighbourhood or cuisine. A list of restaurants available are shown in the area under the map. For more information, opening hours and reviews, users can click on "View Details".
