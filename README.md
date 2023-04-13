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
    - e.g. https://qiita.com/T-ubu/items/146a86558281abac8b2e
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
    - e.g. https://qiita.com/T-ubu/items/76a60bfd4a27d11521e2 (with Docker)
- Undertanding Tippecanoe function
    - tile-join (mbtiles)
    - PMTiles export (ver 2.17 or later)
      - e.g. https://qiita.com/T-ubu/items/93d84b9d4bf5be608fda (this example worked with unvt/kata)

- Vector tile hosting
  - Static hosting with GitHub page (pbf format)
  - Hosting mbtiles with nodejs/express and deliver pbf from mbtiles
    - e.g. https://qiita.com/T-ubu/items/545d9f995ef7496a2ec4
  - (advanced) Azure AD authentication (msal)
    - e.g. https://qiita.com/T-ubu/items/f7147def371b49cb232c (I think this article was not well written.)

- Vector tile styling
  - Creating a simple style with maputnik
    - e.g. an article by smellman https://speakerdeck.com/smellman/distrubute-vector-tile
  - Understanding mapbox/MapLibre style specification
    - source
    - sprites
    - glyphs
    - style layers (understanding filter is important)
    - references:
      - https://qiita.com/T-ubu/items/961176fb92fb66a927e0
      - https://qiita.com/T-ubu/items/02a9725dd6329d35d477
  - Understanding some limitations of each libraries in style interpretation
    - e.g. Esri ArcGIS online, QGIS, etc...
    - https://qiita.com/T-ubu/items/666ffce5d00d3243e40f  
  - Use of unvt/charites for efficient style editing
    - Importing an existing style json 
    - Editing style as a series of YAML files
    - Live preview in localhost
    - Exporting json from YAML files
    - references
      - https://qiita.com/T-ubu/items/6588ebff2af537f6a9b5
      - https://qiita.com/T-ubu/items/c44cd6e079b8e1a6706f 
      - https://qiita.com/T-ubu/items/33cb4617a4db468eb208
      - https://qiita.com/T-ubu/items/e6794b81e45dea34548c
    
- Others
  - Use of Sphinx
    - e.g. https://qiita.com/T-ubu/items/1bf7514ec43a3d1c6eb4
  - Markdown writing
  - PostgreSQL/PostGIS 
    - e.g. https://qiita.com/T-ubu/items/2a097fd7e880bfbfa10c 
  - Raspberry Pi
    - e.g. https://qiita.com/T-ubu/items/f5cb639b4c337ef1050d
    - e.g. https://qiita.com/T-ubu/items/906a8970da5dbec73cec
    - e.g. https://qiita.com/T-ubu/items/ee48cfa1ef7d5fce70cc 
  - RGB Elevation tile creation for 3D terrain 
    - e.g. https://qiita.com/T-ubu/items/c7bb5697b51f245ef163
  - Text fonts
    - e.g. https://qiita.com/T-ubu/items/f2a2084778e456bc8057  
