# Persona 5 / Royal Calendar Rainmeter addon

The GitHub repository for a Rainmeter skin inspired by Persona 5.

It started as a modification of another Persona 5 Calendar skin by DeviantArt user Dartemil, but was later rewritten.


|Game|Skin|
|-|-|
|![vanillaGame](Preview/game.png)|![vanillaSkin](Preview/skin.png)|
|![royalGame](Preview/gameRoyal.png)|![royalSkin](Preview/skinRoyal.png)|

## Features
- Fully Animated weather icons
- "Layered" display, just like in the game
- Optional Inverted colors for January and February (Turned on by default)
- Scalable
- Uses OpenWeatherMap as the weather provider

## Usage
- Download the release .rmskin package and install
- (or clone the repository and put it in Rainmeter/Skins)
- Go to OpenWeatherMap.com and find the city closest to you
- Open Settings.inc in Rainmeter/Skins and add the city ID to the Location Code variable. There are instructions in the .inc file how to do it
- Register for a free account on OpenWeatherMap.com
- Create an API key and add it to the .ini file
- Adjust the size of the skin to your liking
- Optionally change the Inverted colors option to your liking

## Notes
I recommend to turn on hardware acceleration for Rainmeter because it's resizing around 11 high res images every refresh. It's a bad implementation, but I want to have a resizable skin with high rez art, and I don't feel like manually resizing the 500+ images in this skin.

## Credits
- Dartemil for the original Persona 5 Calendar skin
- The original Persona 4 Calendar skin that started all this, I can't find it anymore
- And of course, reddit user BHDown for remaking all the Persona 5 Calendar vector graphics. Original reddit post: https://www.reddit.com/r/Persona5/comments/bjldpg/high_resolution_calendar_assets_and_rainmeter/