# Persona 5 Calendar Rainmeter addon

The GitHub repository for a Rainmeter skin inspired by Persona 5.

It started as a modification of another Persona 5 Calendar skin by DeviantArt user Dartemil, but was later rewritten.

<table>
<th>Game</th><th>Skin</th>
<tr>
    <td width="50%"><img src="Preview/game.png" width="100%"></td>
    <td width="50%"><img src="Preview/skin.png" width="100%"></td>
</tr>
</table>

## Features
- Fully Animated weather icons
- "Layered" display, just like in the game
- Scalable
- Uses OpenWeatherMap as the weather provider

## Usage
- Download the release .rmskin package and install
- (or clone the repository and put it in Rainmeter/Skins)
- Go to OpenWeatherMap.com and find the city closest to you
- Open Calendar.ini in Rainmeter/Skins and add the city ID to the Location Code variable. There are instructions in the .ini file how to do it
- Register for a free account on OpenWeatherMap.com
- Create an API key and add it to the .ini file
- Adjust the size of the skin to your liking

## Notes
I reccomend to turn on hardware acceleration for Rainmeter because it's resizing around 11 high res images every refresh. It's a bad implementation, but I want to have a resizable skin with high rez art, and I don't feel like manually resizing the 500+ images in this skin.

Originally, the skin used Weather.com as the weather provider before wxdata was deprecated, hence why there are also wxdata icons in there.

## Credits
- Dartemil for the original Persona 5 Calendar skin
- The original Persona 4 Calendar skin that started all this, I can't find it anymore
- And of course, reddit user BHDown for remaking all the Persona 5 Calendar vector graphics. Original reddit post: https://www.reddit.com/r/Persona5/comments/bjldpg/high_resolution_calendar_assets_and_rainmeter/