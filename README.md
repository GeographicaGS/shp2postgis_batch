## Shapefiles to PostGIS (batch mode)
With this shell script you can import a folder with shapefiles (batch mode) to an existent PostgreSQL/PostGIS schema.

### Config file
Before execute this script you need a CONFIGFILE properly formed (See CONFIGFILE_example) in your current/working directory.

```
CRS_EPSG=4326
GEODATAFOLDER=/tmp/shp_orig
SQLFILE=/tmp/shp2postgis.sql
DATABASE=mydatabase
HOST=myhost
USER=myuser
PORT=5432
DBSCHEMA=mydbschema
ENCD='LATIN1'
```

## About author
Developed by Cayetano Benavent.
GIS Analyst at Geographica.

http://www.geographica.gs


## License
This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.
