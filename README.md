# GearBest copy short url
Adds a copy short url button to GearBest item page. Copies a nice link instead of a long one. You can find the button just next to "Add to Favorites" button.

This userscript requires [Tampermonkey](https://tampermonkey.net) extension to work which is available for all popular browsers including Chrome, Firefox, Edge

## Changelog

### 1.1.0
- now uses canonical url as primary to prevent 404 urls
- if canonical url is not available, uses old method of parsing address bar url

### 1.0.1
- fixed appending of warehouse ID which is required in url

### 1.0.0
- initial release
- Public @ https://openuserjs.org/scripts/moped/GearBest_copy_short_url_button
