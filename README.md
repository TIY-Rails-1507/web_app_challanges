# Web App Challenges

These are some ideas for web applications to build. 

Please note that we have not yet covered all the topics you would need to do these. In fact we probably won't cover all the bits that would make these work in the class. 

However, you are encouraged to give at least one these a bash. If you get stuck you could ping the class on Slack and we will point you in the right direction.

Slack Group: https://tiystudents.slack.com/messages/lon_jul2015_rails/

## The Next Big Idea&trade;

Come up with an idea that interests you... 

Anything is good, the more practice you get the better.

## Rock Paper Scissors 2.0

Due to popular demand, RPS is going onto the web!

Create a simple app that let's a user play RPS against the computer. 

Hint: After Wednesday we would have probably covered enough to get this working in a simple way. 


## A Film Site

Create a site that lists a bunch of films, as well as data for each film. 

The fun bits: 
* Show trailers via embedding the YouTube player into your sites pages 
* Get the data from: http://www.omdbapi.com/


## Online Blackjack

Use the Deck Of Cards api to create a single player game of Blackjack.

API: http://deckofcardsapi.com/

This is obviously a lot more challenging, but it can be done - (I have not actually done, but I am suer you guys can)

Hint: To get started simply display two random cards at a given page in your application.


## Where in the world?

Come up with an idea that let's you integrate with the Google Maps API.

E.g. In the 'explore' app, we can show exactly where a hotel on Google Maps.


It should also be possible to determine where the user of the site is.... 


## Other API ideas

Do something with the Trello, Twitter, or GitHub API...

Or one of these:

http://www.programmableweb.com/apis/directory

https://www.mashape.com/



## Loads more ideas...


annyang (voice control / web speech api) - https://www.talater.com/annyang/
https://www.flickr.com/services/apps/create/noncommercial/?
https://developer.foursquare.com/
https://www.yelp.com/developers/manage_api_keys
https://github.com/giphy/GiphyAPI
http://www.omdbapi.com/
http://developer.rottentomatoes.com/docs/read/JSON
http://www.bandsintown.com/api/overview
https://www.data.gov/developers/apis
http://www.meetup.com/meetup_api/
http://www.brewerydb.com/developers
http://developer.nytimes.com/docs
http://www.programmableweb.com/apis
https://api.github.com/users/matthiasak/events/public
https://www.etsy.com/developers/documentation/reference/listing
APIs provide 3 primary methods for us front-end devs to access them:

CORS - JSON (not all are CORS)
non-CORS - JSONP (not all are JSONP)
server-side proxy (our local server makes the JSON request for us, and returns it to the browser)
Methods 1 and 2 let JS developers make direct requests from the Browser.

Method 3 is a little harder for us to implement in the browser. Instead, use either a Node.js proxy (like the heroku-server.js file provided with the package.json), or try https://jsonp.nodejitsu.com/.

#### You can also host your own seperate RESTful server:

https://github.com/masondesu/tiny-server
https://github.com/matthiasak/Restly
Need to stub out some JSON data? try http://beta.json-generator.com/

#### API Search 

Engine: http://www.publicapis.com/

#### Communications (Email, SMS, Phone)

https://github.com/andris9/Nodemailer
http://www.mailgun.com/
https://www.mandrill.com/
https://www.twilio.com/
Social APIs

#### Social
connect to social APIs with http://adodson.com/hello.js/#install
meetup - http://www.meetup.com/meetup_api/
klout - https://klout.com/s/developers/v2
twitter - https://dev.twitter.com/
twitter "intents" (put interactive widgets on your page and have someone tweet/reply to you via twitter) - https://dev.twitter.com/docs/intents
twitter for websites (follow button, embed tweets on a page) - https://dev.twitter.com/docs/tfw
REST API (uses OAuth) - https://dev.twitter.com/docs/api/1.1
facebook - https://developers.facebook.com/
linkedin - https://developer.linkedin.com/apis
foursquare - https://developer.foursquare.com/
yelp - http://www.yelp.com/developers/documentation/v2/search_api
github - https://developer.github.com/v3/

#### Food-related APIs

Yummly - https://developer.yummly.com/

#### Government and Civil APIs

Capitol Words - http://capitolwords.org/term/code/?search=1
CDC - https://data.cdc.gov/ and http://wonder.cdc.gov/
Federal Data.gov project - https://www.data.gov/developers/apis
Sunlight Foundation - http://sunlightfoundation.com/api/
Weather APIs

Forecast.io - https://developer.forecast.io/

#### Google APIs

Using the Google SDK (a .js file) may be necessary and the easiest way to get started with Google APIs

- https://developers.google.com/api-client-library/javascript/start/start-js
- https://developers.google.com/apis-explorer/#p/
maps, directions, geocoder, places, etc - https://developers.google.com/maps/documentation/javascript/
feed - https://developers.google.com/feed/v1/devguide
plus - https://developers.google.com/+/web/
static maps - just a url for an image, e.g.:

http://maps.googleapis.com/maps/api/staticmap?center=Brooklyn+Bridge,New+York,NY&zoom=13&size=600x300&maptype=roadmap&markers=color:blue%7Clabel:S%7C40.702147,-74.015794&markers=color:green%7Clabel:G%7C40.711614,-74.012318&markers=color:red%7Clabel:C%7C40.718217,-73.998284

streetview api - again just a url, e.g.: http://maps.googleapis.com/maps/api/streetview?size=400x400&location=40.720032,-73.988354&fov=90&heading=235&pitch=10

tasks - https://developers.google.com/google-apps/tasks/v1/reference/tasks/update
Google custom search engine - https://developers.google.com/custom-search/json-api/v1/overview

#### Music and Video APIs

Spotify - https://developer.spotify.com/
Soundcloud - https://developers.soundcloud.com/
Deezer - http://developers.deezer.com/
Grooveshark - http://developers.grooveshark.com/
Rdio - http://www.rdio.com/developers/
YouTube - https://developers.google.com/youtube/v3/getting-started
Vimeo - https://developer.vimeo.com/
BandsInTown - http://www.bandsintown.com/api/overview
Dolby Audio - http://developer.dolby.com/
Image APIs

Flickr - https://www.flickr.com/services/api/
PlaceKitten - http://placekitten.com/
PlaceBacn - http://placebacn.com/
LoremPixel - http://lorempixel.com/
File and Data Storage APIs

#### Other 

Dropbox - https://www.dropbox.com/developers/datastore

also, embeddable JS widgets on your page -> https://www.dropbox.com/developers/dropins
AWS - http://aws.amazon.com/sdk-for-browser/

Firebase - https://www.firebase.com/how-it-works.html

User Auth with Firebase - http://jsfiddle.net/firebase/a221m6pb/
Parse - https://parse.com/docs/js_guide#javascript_guide - https://parse.com/downloads/javascript/parse-1.2.19.js

Meteor (has a deploy tool just like heroku, comes with front end and back end code) - http://docs.meteor.com/#top

#### Payments, Credit Card Processing, and Shopping Carts

Stripe - https://stripe.com/docs/api - https://stripe.com/docs/stripe.js
Braintree - https://developers.braintreepayments.com/javascript+node/start/overview
Paypal - https://developer.paypal.com/docs/api/
Snipcart - https://snipcart.com/
Gumroad - "Buy button right on your site" - https://gumroad.com/overlay

also, embed a product widget right on site - https://gumroad.com/embed
https://gumroad.com/api
Helium - https://gethelium.com/

#### Retail

BestBuy - https://developer.bestbuy.com/

#### Other / HackerNews / Startup-y APIs

Producthunt - https://github.com/karan/Hook
Trello - https://trello.com/docs/
Wunderlist - https://developer.wunderlist.com/documentation/tools/wunderlist.js
HackerNews - http://api.ihackernews.com/
https://github.com/HackerNews/API
Track Ships / Vessels - http://www.fleetmon.com/faq/public_api
Wikipedia - http://www.mediawiki.org/wiki/API:Main_page
Untappd - https://untappd.com/api/docs
BreweryDB - http://www.brewerydb.com/developers
23andme - https://api.23andme.com/
NYT - http://developer.nytimes.com/docs
NPR - http://dev.npr.org/
EasyPost - Shipping integration and postage ordering with FedEx/UPS/USPS/DHL - https://www.easypost.com/
Wit - natural language processing - http://labs.wit.ai/demo/index.html
Nest - https://developer.nest.com/documentation/control
FlightAware - http://flightaware.com/commercial/flightxml/
IMDB / OMDB - http://www.omdbapi.com/
Rotten Tomatoes - http://developer.rottentomatoes.com/docs/read/JSON
Hipchat API - https://www.hipchat.com/docs/apiv2
Zapier - https://zapier.com/developer/documentation/getting-started/
Evernote - https://dev.evernote.com/doc/
Marvel - http://developer.marvel.com/docs

#### Dictionary / Words / Thesaurus APIs

DictionaryAPI - http://dictionaryapi.com/ - example at http://whispering-island-7828.herokuapp.com/#magic
GIFs

https://github.com/giphy/GiphyAPI

#### Real Estate APIs

Trulia - http://developer.trulia.com/
Zillow - http://www.zillow.com/howto/api/PropertyDetailsAPIOverview.htm
http://www.getziptastic.com/

#### Job APIs

USA jobs - http://search.digitalgov.gov/developer/jobs.html
current API you're using: http://www.authenticjobs.com/api/documentation/
possible XML API: http://www.indeed.com/jsp/apiinfo.jsp
JS-based API for LinkedIn Jobs: https://developer.linkedin.com/documents/getting-started-javascript-api
Stack Overflow XML feed: http://careers.stackoverflow.com/jobs/feed?searchTerm=javascript&location=tx&range=160&distanceUnits=Miles
Transportation APIs

Uber - https://developer.uber.com/

#### Real Devices

The LEAP Motion - https://www.leapmotion.com/ - https://developer.leapmotion.com/documentation/skeletal/javascript/index.html
Oculus - http://www.oculus.com/dk2/ - https://github.com/Instrument/oculus-bridge
Tessel - https://tessel.io/ - https://tessel.io/docs
Nest - https://nest.com/ - https://developer.nest.com/documentation/control - https://developer.nest.com/documentation/alert
Large Databases of APIs

https://www.mashape.com/explore

#### Native Apps

nwjs
https://www.nativescript.org/
appcelerator
react native
