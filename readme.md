# WTF?

Using [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js) and Mapbox Vector Tiles, you can select and print a map from the browser that is a high enough resolution to use in print.  No ArcMap, no problem.  The idea is this will give you a decent basemap quickly, you add the relevant labels and overlays and send it to the copy desk.

##You'll Need
*Source for mapbox vector tiles.  You can use mapbox or roll your own.
*Style files.  Again, use someone elses or roll your own.  I recommend building them via the GUI editor [Maputnik](http://maputnik.com/). You'll want to drop the path to them into index.html in the select option.  Best practice is to delete all labels and add them yourself later - between Open Street Map data and Mapbox wonkiness, the labels juse don't work for print production.

## License
This is a slightly modified version of print-maps by [Matthew Petroff](http://mpetroff.net/), changed just to make it work better for my workflow.
Print Maps is distributed under the MIT License. For more information, read the file `COPYING` or peruse the license
[online](https://github.com/mpetroff/print-maps/blob/master/COPYING).

## Credits

* [Matthew Petroff](http://mpetroff.net/), Original Author
* [Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js)
* [FileSaver.js](https://github.com/eligrey/FileSaver.js/)
* [canvas-toBlob.js](https://github.com/eligrey/canvas-toBlob.js)
* [jsPDF](https://github.com/MrRio/jsPDF)
* [Bootstrap](http://getbootstrap.com/)
