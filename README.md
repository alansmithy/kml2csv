# kml2csv
A very basic electron app for converting Google Map KML placemarks to simple CSV 

## how to install
npm install - to install the required dependencies

## how to run
npm start will launch the kml2csv application window

## how to use
Create a [Google MyMap](https://www.google.com/mymaps) and export the map to KML. Drag the .kml file onto the kml2csv application window and it will create a csv version of the data (name,longitude,latitude) in the same directory. Useful for working with apps like [maps4news.com](https://maps4news.com) which do not currently support direct KML upload but can work with CSV.
