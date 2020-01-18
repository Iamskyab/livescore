# Live Score

[![Netlify Status](https://api.netlify.com/api/v1/badges/adf5bd69-3409-4a8e-8e10-ca71c91d8806/deploy-status)](https://app.netlify.com/sites/livecri/deploys)

A Simple Scrape Method to Fetch the Live Cricket Score from espncricinfo.com

## For Education Purpose only ✍

> We are not Responsible for any future damage use at your own risk.if you want to use this on Production Read the ESPNcricinfo Terms and use.

## Methods Used

- Cheerio.js for scrape the content
- axios - HTTP Client
- Bundle the Package using browserify.JS

## usage

- Download and Upload the `public` Folder on your server or localhost

> Still Many Features are Missing I will Updating one by one based on user Suggestion -  if you have any ideas your PR's are always welcome.

## Development

- Clone this respo and install the Modules via yarn

```bash
yarn
```

- All changes and Updates are done via `main.js` file
- Front-end File on `public` Folder `index.html`
- Get Live Match Score URLS from `espncricinfo.com` XML Feed - `http://static.cricinfo.com/rss/livescores.xml` - you need the Update Live Match URL - <https://github.com/mskian/livescore/blob/master/main.js#L4> Don't Remove the `https://cors-anywhere.herokuapp.com` it helps us to Bypass the Cors Blocking - <https://medium.com/@dtkatz/3-ways-to-fix-the-cors-error-and-how-access-control-allow-origin-works-d97d55946d9>
- After the changes Generate bundle file

```bash
yarn build
```

- Test the site on local server

```bash
yarn live
```

## LICENSE

MIT
