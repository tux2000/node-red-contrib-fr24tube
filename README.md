node-red-contrib-fr24tube
=========================

> Based on zuhito node-red-contrib-flightradar24

Node-RED node to retrieve plane locations from flightradar24 service, but only in a square tube based on coordinates and radius

## Ph Koenig addendum:
- set a square distance around lat/long to get a specific number of plane.
        - this add geolib dependencies
- return only plane in this tube.
- add bot informations to msg.
- protect the "non payload" of original msg.

## Install
-------
Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install @avoit/node-red-contrib-fr24tube


