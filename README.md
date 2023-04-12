# training4unvt
List of the basic trainings for UNVT beginner 

# List
- GitHub
  - Creating an account
  - Creating a repository
  - Use of GitHub Desktop
  - Editing contents and push them
  - Trying ".gitignore" 
  - Cloning a repository with git

- nodejs
  - Installing nodejs in windows PC
  - Running a simple script with nodejs
  - Installing some npm modules
  - Checking package.json

- nodejs (advanced)
  - Use of pg module to access PostgreSQL/PostGIS database
  - Use of childprocess module
  - Use of better-queue module

- Docker
  - Understand the overview of Docker
    - Docker can provide virtual linux environment in Windows PC that can run tippecanoe
  - Checking the Docker license
  - Pulling the unvt/nanban image
    - Ubuntu based container with necessary GIS tools
    - felt/tippecanoe is included
  - Creating a container from unvt/nanban

- Vector tile production (data conversion)
  - Simple data conversion from shape file
    - Use of gdal to convert shape files into geojson
    - GeoJSON files are converted into vector tile with tippecanoe
  - Undertanding Tippecanoe function
    - tile-join (mbtiles)
    - PMTiles export (ver 2.17 or later)

- Vector tile hosting
  - Static hosting with GitHub page (pbf format)
  - Hosting mbtiles with nodejs/express and deliver pbf from mbtiles
  - (advanced) Azure AD authentication (msal)

- Vector tile styling
  - Creating a simple style with maputnik
  - Understanding mapbox/MapLibre style specification
    - source
    - sprites
    - glyphs
    - style layers (understanding filter is important)
  - Understanding some limitations of each libraries in style interpretation
    - e.g. Esri ArcGIS online, QGIS, etc...
  - Use of unvt/charites for efficient style editing
    - Importing an existing style json 
    - Editing style as a series of YAML files
    - Live preview in localhost
    - Exporting json from YAML files
    
- Others
  - Use of Sphinx
  - Markdown writing
  - PostgreSQL/PostGIS 
  - Raspberry Pi
