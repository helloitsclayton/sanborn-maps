# sanborn-maps
Using Leaflet to overlay the index page in LoC's Sanborn Maps with links to the indicated pages

This tool uses Leaflet and the Leaflet-IIIF plugin to pull the index page of a Sanborn Map in from the Library of Congress. The GeoJSON in test.js describes a feature for each page in the volume which will provide a clickable link to that page from the index.

I plan to:
* ~~Finish describing the features for ths particular index page (the 1897 edition for Detroit, volume 1)~~
* ~~Set up the links to work internally, i.e. to load the desired page in using the IIIF manifest and not to link out to the LoC page~~
* Provide links to other volumes using the map in the upper right-hand corner
* Possibly set up links in each page to the index and to any pages/volumes referenced on that page
