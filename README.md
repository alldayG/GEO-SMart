# GEO-SMart

GEO-SMart is an interactive model of the Earth system in a single web page. A 3-D globe runs from the atmosphere down to the inner core. A climate engine calibrated to the IPCC's Sixth Assessment Report (AR6) drives it. Pick a pathway, a climate sensitivity and a year, from the last ice age to centuries ahead. The globe and the readouts then show warming, sea level, ice sheets, sea ice, sea-surface temperature, ocean pH, volcanic eruptions, mantle flow and the magnetic field for that year. The physics logs check the model against observations and the IPCC's assessed ranges.

Version 6.12.

## Using it

Open `index.html` in a recent version of Chrome, Edge, Firefox or Safari. Your browser needs WebGL, which almost every computer has. The page needs an internet connection the first time it opens, to load three.js, Tailwind, Font Awesome and its Google Fonts. Everything else, including all the maps and data, is inside the file. It is about 13 MB, so it can take a few seconds to open on a slow connection.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `ATTRIBUTIONS.md` | The sources, licences and credits for the data, code, fonts and icons GEO-SMart uses from others |
| `README.md` | This page |

## Hosting

`index.html` is a static page. It has no server code and sends nothing anywhere, so it runs on any web host: GitHub Pages, Netlify, or an ordinary web server. To host it, upload it.

The page loads its libraries and fonts from public servers (cdnjs, jsDelivr, the Tailwind CDN and Google Fonts). Those servers see each visitor's IP address, as they do for any site that uses them.

## Credits

GEO-SMart uses data from NASA, NOAA, the USGS, NSIDC, Natural Earth, the IPCC, CMIP6 climate models, the Smithsonian's Global Volcanism Program and many published studies, plus open-source code, fonts and icons. [ATTRIBUTIONS.md](ATTRIBUTIONS.md) lists them all with their licences. The Smithsonian's volcano data is for non-commercial use only.
