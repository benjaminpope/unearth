# unearth

### Can we see the Earth in K2 Data?

Under GO Program [GO16905](https://keplerscience.arc.nasa.gov/data/k2-programs/GO16905.txt), Van Cleve proposed looking at the Earth occulting the Moon in K2 Campaign 16. 

Looking at these raw data with [k2mosaic](http://k2mosaic.geert.io/index.html), we've made a [video](https://github.com/benjaminpope/unearth/blob/master/data/mosaic/k2earth.mp4) of this - and it's gnarly! There is a very narrow trail and Earth moves along it *very* fast, with some seriously brutal saturation and a very weird pattern of stray light. 

There is something corrupted after cadence 143 that breaks k2mosaic - I will try and fix this - but when I skip cadences it actually seems nothing from Earth comes back after this point anyway (see [here](https://github.com/benjaminpope/unearth/blob/master/data/k2earth_pixels/k2earth_long.mp4)), so perhaps we'll just be hacky. 