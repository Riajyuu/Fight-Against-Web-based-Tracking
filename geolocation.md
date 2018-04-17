#### W3C Geolocation API

This HTML5 JavaScript API requires users permission but can be **really high accuracy** (less than 10 meters). It is really useful sometimes, finding nearest restaurant for example, but can still be an issue if you keep using such accurate info.



Recommended solution: [Location Guard](https://github.com/chatziko/location-guard), it is recommended to reduce accuracy of the API with this extension, 200~500 meters can be enough to find your favorite restaurant.



#### Timezone JavaScript API

Timezone is not that accurate but can still show some of indenfication info, your probable nationanlity for example.



Recommended solution: [Spoof Timezone](https://github.com/joue-quroi/spoof-timezone)



#### IP Address

Your IP address also shows timezone where you live despite the JavaScript API. Use proxy if this is a concern to you.