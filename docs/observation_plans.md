# Observation Plans

This document discusses the observions required to image the object

## Location
We plan to observe as the asteroid comes into opposition with the Earth around November 20, 2020. See 
[predicting the position](./predictions.md) for more info.

## Movement of asteroid
The [hourly ephemeris around opposition](./ephemeris_opposition_2020_hourly.md) indicates that the object will
have an apparent motion across the sky of about 105 arc seconds per hour (approximate 2 arc minutes per hour)

## Telescope selection
Requirements:

* Northern hemisphere observatory preferred (declination at oppositon is 25 degrees North)
* Largish aperture telescope (object is faint at mag. 17)
* Largish field of view (FOV) to maximise duration of timelapse (or perhaps we can 'pan' the view?)

## Field prediction

It would be nice to predict what the star field might look like in the camera -- is there software available for this or
should we roll our own.

### SkyView
One appraoch is to use the [NASA SkyView Virtual Telescope](https://skyview.gsfc.nasa.gov/current/cgi/titlepage.pl) web page
and enter the following coordinates:

``03 10 08.0, 25 25 57.0``

The centre of the resulting image represents roughly the
location of the closest approach with the asteroid on Nov 20, 2020

### Stellarium

Try this: https://stellarium-web.org/  -- Stellarium uses the [DSS](https://en.wikipedia.org/wiki/Digitized_Sky_Survey) and is pretty good -- we just have to learn how to drive it.
## Other asteriods in the area

We might encounter other asteroids in the area while making our images. Can we develop software to remove the background 
stars between two images and perhaps find minor planets in company with [7779 Susanring](https://minorplanetcenter.net/db_search/show_object?object_id=7779)
