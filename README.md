FrontEnd Web App Application Challenge


Run by cding into folder, where app.js
and typing node app.js, then visit localhost:3000 on your browser

Main problem I had was with cors request.
Especially with distance API(which I didn't have time to figure out)
Since the Yelp API didn't provide a direct distance measurement, and determining distance just based of latitude/longitude isn't that reliable I decided to use the google's distance matrix api to get distance values, but that didn't work out too well, as I kept meeting cors request,possibly because I might have been doing too many requests at once? Preferably I would've tried to just estimated the distnaced based of latitude/longitude, and would've foregone the need for all those api requests. I could also have waited for  apage to load, stored all that data, then make a single request for all that data after everything else is done.
