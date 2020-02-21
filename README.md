# Weather


![Final App](https://derekwebdev.com/gifs/weather.gif)

Geolocation Based Weather Celsius and Fahrenheit

This project uses the following technologies:

- [JavaScript](https://www.javascript.com/) and [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API/Using_the_Geolocation_API) for finding user location
- [Skycons](https://darkskyapp.github.io/skycons/) for weather animations [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) for the linear gradient

## Configuration

Make sure to add your own `MONGOURI` from your [Cloud](https://www.mongodb.com/) database in `config/keys.js`.

```javascript
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```

## Quick Start

```javascript
// Install dependencies for server & client
npm install && npm run client-install

// Run client & server with concurrently
npm run dev

// Server will run on http://localhost:5000 and client on http://localhost:3000
