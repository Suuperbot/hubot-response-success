#### How to use
Make sure you have [hubot-response](https://github.com/michaeljacobdavis/hubot-response) installed in your hubot directory.

```
npm install --save hubot-response-success
```

Under your responses directory, create an `success.js` (you can name it whatever) file with

```
module.exports = require('hubot-response-success');
```

#### Want to add more images?
In your `success.js` file, just push whatever you want to the `response` array.

```
// Import the module you want
var config = require('hubot-response-success');

// Extend whatever you wany
config.response.push('http://my-new-image-url-here');

// Export the altered object
module.exports = config;
```
