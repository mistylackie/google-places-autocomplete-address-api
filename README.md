# Google Places Autocomplete Address API

Use the Google Places Autocomplete Javascript API to show matching addresses near your location based on what is typed in the input field.

## How To Use

- The [demo.html](demo.html) file has 1 address field that when typed into will show matching addresses to select from.

- The address input field has an id of 'address' which is used to bound to the 'autocomplete' object in the autocomplete.js file.

- The 'initializeAutocomplete' method has to be called when google is ready, not just when the DOM is ready.

## Get API Key

1. Create a new project under the [Google API Console](https://code.google.com/apis/console) and enable the Google Maps Javascript API v3:

2. Create a new "Browser Key" and place that API key in your page like show in the bottom  of the the demo.html file.

3. Don't forget to set your referrers field in the Google API credentials. You are limited to a certain amount of calls per day and you don't want others to be able to use your API key.

[See Demo](https://www.realshout.com/listing/378515/)

[Google API Reference](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-addressform)

[Original Repo] (https://github.com/lewagon/google-place-autocomplete)
