# Timer for Websites That Steal Your Time

This project helps to control time was spent on sites. It requires special extension for Chrome browser.

# Installing

Install extension for Chrome browser [Custom JavaScript for websites](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija).

Open configuration of [cjs](https://chrome.google
.com/webstore/detail/custom-javascript-for-web
/poakhlngfciodnhlhhgnaaelnpjljija) browser extension on the site you want to 
controll. Click on the link "your own external scripts", add [https://a-savinov.github.io/34_timemachine/index.js]
(https://a-savinov.github.io/34_timemachine/index.js)  Don`t forget to press "enable cjs for this host" to enable custom JS.

After that you will see countdown timer in the up right corner. By default 
timer is set to 3 minutes. After the end of the countdown, you will see an alert with a motivating message in your browser every 30 seconds

For faster development you can use JS code hosted on localhost. Simple web server can be used for that, run:

```bash

python3 -m http.server
```

Add path `http://localhost:8000/index.js` to [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension. Done.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
