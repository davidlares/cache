# Express Cache work

This is to demostrate the use of the Cache-Control header
To try it out, setup the application

## How to install it

Just `npm install`

## Run the application

Run: `node server.js` or `npm start` and then, open http://localhost:3000 in a browser

Hit the "Call REST" button and based on the max-age setup when you will hit the "Call REST" Browser will refresh by fetching new counter value *or* Get the data from the browser cache

In order to understand the behavior
1. Change the MAX_AGE in server.js to different values, keep in mind value is in seconds
2. Restart the server
3. Hit the "Call REST" on browser

## Credits

 - [David E Lares](https://twitter.com/davidlares3)

## License

 - [MIT](https://opensource.org/licenses/MIT)
