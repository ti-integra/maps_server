
FROM openrouteservice/openrouteservice:v9.2.0

USER root
WORKDIR /home/ors

RUN mkdir -p files 
RUN wget -O files/brazil-latest.osm.pbf \
    https://download.geofabrik.de/south-america/brazil-latest.osm.pbf

USER ors
