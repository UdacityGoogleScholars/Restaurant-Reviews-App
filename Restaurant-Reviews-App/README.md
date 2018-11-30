# Restaurant-Reviews-App Submission

---
#### _Three Stage Course Material Project - Restaurant Reviews_

# Live Version


## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Development Strategy
Use MapBox API key to get the map on the screen.
Create a responsive grid-based layout using CSS.
Use media queries that provide fluid breakpoints across different screen sizes
Use responsive images that adjust for the dimensions and resolution of any mobile device.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

### Additional Resources
In-depth look at responsive images
https://www.udacity.com/course/responsive-images--ud882

Use JavaScript directly to create a tab index for each element desired.
https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/tabIndex

Media Queries for Standard Devices via CSS Tricks
https://css-tricks.com/snippets/css/media-queries-for-standard-devices/

Time-saving CSS techniques to create responsive images
https://medium.freecodecamp.org/time-saving-css-techniques-to-create-responsive-images-ebb1e84f90d5

Responsive Images via Google
https://developers.google.com/web/ilt/pwa/lab-responsive-images

Service Workers: An Introduction via Google
https://developers.google.com/web/fundamentals/primers/service-workers/

###Style Guides
HTML Style Guide
http://udacity.github.io/frontend-nanodegree-styleguide/index.html

CSS Style Guide
http://udacity.github.io/frontend-nanodegree-styleguide/css.html

JavaScript Style Guide
http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html

Git Style Guide
https://udacity.github.io/git-styleguide/

###Steps to complete the project
Fork and clone the starter repository. The code in this repository will serve as your baseline to begin development.
From inside the new directory, launch a local client server using Python from your terminal:
Python 2: python -m SimpleHTTPServer 8000
Python 3: python3 -m http.server 8000
Visit the site in your browser at http://localhost:8000

Convert the provided site to use a responsive design .
Bootstrap and other CSS frameworks should not be used; all responsiveness should be done with CSS.
Use appropriate document type declaration and viewport tags
Create a responsive grid-based layout using CSS
Use media queries that provide fluid breakpoints across different screen sizes
Use responsive images that adjust for the dimensions and resolution of any mobile device
Implement accessibility features in the site HTML (most of this HTML is generated by JavaScript functions).
Add a ServiceWorker script to cache requests to all of the site’s assets so that any page that has been visited by a user will be accessible when the user is offline. Only caching needs to be implemented, no other ServiceWorker features.
Consult the rubric often to be sure you are meeting the specific project requirements.
