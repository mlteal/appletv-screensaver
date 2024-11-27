# appletv-screensaver
An experiment to get AppleTV to play Screen Saver videos I've selected instead of the only available options of Aerial or static photos.

## Inspiration

This is based off of the following Stackoverflow/Apple Support threads:

- https://forums.developer.apple.com/forums/thread/25982
- https://forums.developer.apple.com/forums/thread/25982

## Instructions

Once you've got some sort of public GET endpoint that will serve a simple JSON response, utilize the template found at http://a1.phobos.apple.com/us/r1000/000/Features/atv/AutumnResources/videos/entries.json to create your own set of videos that can be used as a screensaver. 

To enter the URL on your Apple TV, go to Settings->General and then click the Play/Pause button four times: this will take you to the Retail Demo Configuration screen. In the Configuration URL field, enter the full URL to the endpoint that serves the raw JSON (ie https://mlteal.github.io/appletv-screensaver/orca2.json). 

## Important notes

Apple TV will only read .MOV video files. 
