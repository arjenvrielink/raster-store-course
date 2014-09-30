title: Raster Store Course
author:
    name: Arjen Vrielink
twitter: arjenvrielink
output: index.html
controls: false

-- 

# Raster store
## Arjan en Arjen, Nelen&Schuurmans

--

### Overview

* Examples
* Architecture
* Use
* Hands on: single date
* Hands on: multi date; time series
* Hands on: multiple stores
* Hands on: build your own API

--

### Examples

* [raster server demo](raster.lizard.net/wms/demo)
* [lizard nxt](staging.nxt.lizard.net)

--

### Architecture

* structure (pyramid)
* directory structure / metadata
* resolution
* aggregation algorithms
* Python API
* WMS layer

--

### Use

**Installation**

In a Ubuntu (12.04, 14.04) box:

```
git clone <url/to/git.repo>
cd raster-store
python bootstrap.py
bin/buildout
bin/test
```

dependencies:

```
sudo apt-get install libhdf5-serial-dev python-numpy python-gdal
```

--

### Use

**Python API**

* initialise store
* add data
* update

--

### Use

**Query**

* point / line / polygon

--

### Hands on: single date

* continuous: height
* discrete: landuse

--

### Hands on: time series

* equidistant
* resolution

--

### Hands on: multiple stores

pre-aggregate

--

### Hands on: build your own web API

lizard
