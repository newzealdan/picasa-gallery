What is it?
===========

A good-looking frontend for Google's Picasaweb photo galleries, with nice transitions,
mobile device support, and full-screen photo browsing with quick loading (prefetching).

For all those who wish their Picasaweb gallery had black background!

See example gallery: http://photos.azib.net/ - use the link at the bottom to try it with your own gallery!

How does it work?
=================

It's a small Java application made to be hosted for free on Google App Engine.
It uses Google Data API to fetch and display your albums and photos, so whenever you change anything
on Picasaweb, it will become visible in this gallery.

How to use it for your own photos
=================================

- Clone this repository as described on Github
- Specify your Picasaweb username in src/config.properties
- Specify your AppEngine application ID in web/WEB-INF/appengine-web.xml
- Download AppEngine SDK from Google
- Use AppEngine SDK / Eclipse / IntelliJ IDEA to deploy your application
  Details here: http://code.google.com/appengine/docs/java/gettingstarted/uploading.html

P.S. the app is a standard Java Servlet-based application, so it will work without AppEngine as well.
