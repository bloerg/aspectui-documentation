# welcome

This is the documentation to ASPECT-ui, a user interface for spectra maps computed with [ASPECT](http://www.tls-tautenburg.de/TLS/fileadmin/forschung/meus/ASPECT/ASPECT.html).

While ASPECT is a software developed to process large amounts of spectra into [Self Organizing Maps (or Kohonen Maps)](https://en.wikipedia.org/wiki/Self-organizing_map), ASPECT-ui is meant to give an easy start on working with the computed output.

To see an application of the user interface go to the [spectra map of about 1 million SDSS DR7 spectra](http://aspect-ui.de/sdssdr7/).

ASPECT-ui comprises a responsive web browser user interface, making use of [leaflet.js](http://leafletjs.com/) for visualisation of Kohonen Maps of spectra. To this end representative icons of [SDSS](http://sdss3.org/) spectra are composed and resized to different detail levels. The resulting images are then used to make a zoomable and pannable representation of the spectra Kohonen Map.

The user interface is accompanied by a set of command line tools which make it easy to generate an ASPECT-ui instance for a computed map.
