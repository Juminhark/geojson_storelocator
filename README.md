# store_locator_api
 Node.js GeoJSON API & App | Store Locator


In this project we will create a store locator API that serves GeoJSON data. 
We will also build a simple frontend using Mapbox to plot the points.

we`ve built a back-end a back-end api with express mongoose 
geocoder with MapQuest. we created Mongoose middleware
geoJason field. front-end that could consume our api using 
mapbox to display geoJason field. after fetching them using the 
fetch api


> mkdir store_locator_api
> cd store_locator_api
> npm init -y
> npm i express mongoose dotenv node-geocoder cors
> npm i -D nodemon

package.json --
"main": "server.js",
"scripts": {
   "start":"node server.js",
   "dev": "nodemon server.js"
 }

https://www.npmjs.com/package/node-geocoder
https://mongoosejs.com/docs/geojson.html
https://developer.mapquest.com
https://docs.mapbox.com/mapbox-gl-js/example/add-image
