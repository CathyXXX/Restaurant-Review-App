# Restaurant Review App Project

## Table of Contents

* [Project Overview](#project-overview)
* [Tasks](#tasks)
* [How to run the application?](#how-to-run-the-application)
* [Leaflet.js and Mapbox:](#leaflet.js-and-Mapbox)
* [Note about ES6](#note-about-es6)


## Project Overview: Stage 1

In this project we were given a **Restaurant Reviews** application. The started code was provided and had a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. The task was to update the code to resolve these issues while still maintaining the included functionality.

## Tasks
- Take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. 
- Integrate a Map API using Google Maps or Mapbox.
- Add a service worker to begin the process of creating a seamless offline experience for users.

## How to run the application?

1. Clone or download the repository.

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000`

4. Open your browser inspector to view the different responsiveness ratio's of the application

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code.
