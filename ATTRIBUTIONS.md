# Credits and licences

GEO-SMart is a single web page, `index.html`. This file lists everything in it, or loaded by it, that was made by someone else: where it comes from, its licence, and the credit it asks for. Each layer card in the app also names its sources.

**In short:** all of it may be used on a free, ad-free website. One source, the Smithsonian's catalogue of volcanic eruptions, is licensed for non-commercial use only (see [Volcanic eruptions](#volcanic-eruptions)). Some licences ask for their text to go with every copy. That text is in a comment at the top of `index.html` and at the [end of this file](#licence-texts).

## Loaded from other sites when the page opens

These are not inside `index.html`. Visitors' browsers fetch them from public servers.

| What | From | Licence |
|---|---|---|
| three.js r128 and its OrbitControls (3-D graphics) | cdnjs.cloudflare.com, cdn.jsdelivr.net | MIT |
| Tailwind CSS (Play CDN) | cdn.tailwindcss.com | MIT |
| Font Awesome Free 6.4.0 (interface icons) | cdnjs.cloudflare.com | Icons CC BY 4.0, fonts SIL OFL 1.1, code MIT. The credit is in the CSS file it serves |
| IBM Plex Sans, Plus Jakarta Sans, Sora, Tektur and Pirata One (fonts) | Google Fonts | SIL Open Font License 1.1 |

## Inside index.html

### Imagery, terrain and coastlines

| What | Source | Licence and credit |
|---|---|---|
| Land colours | NASA Blue Marble Next Generation (Stöckli et al. 2005), NASA Earth Observatory. Ice, snow and water were removed and filled in for the app | NASA imagery is not copyrighted. Credit: NASA Earth Observatory |
| Clouds | The "fair weather" cloud map `fair_clouds_4k.png` from Bjørn Sandvik's webgl-earth project. It appears to be Tom Patterson's Natural Earth III "Fair weather" cloud map, which is made from the cloud image of NASA's Blue Marble (2002) | Natural Earth III and the NASA image are public domain. Credit (optional): Tom Patterson, www.shadedrelief.com |
| Relief of the land and the sea floor | Mapzen / Tilezen Terrain Tiles at zoom 5 (about 4 km), which take land heights from GMTED2010 and the sea floor from ETOPO1 | Public domain. Credit: GMTED2010 data courtesy of the U.S. Geological Survey; global ETOPO1 terrain data, U.S. National Oceanic and Atmospheric Administration |
| Bedrock near the poles | CRUST1.0 (Laske, Masters, Ma & Pasyanos 2013) | Free to download; no licence stated. Cite Laske et al. (2013) |
| Coastlines, lakes, glaciers and ice shelves | Natural Earth 1:10m | Public domain |
| Ice-sheet surface and thickness | ETOPO1 ice surface (NOAA) | Public domain |

### Ocean and ice

| What | Source | Licence and credit |
|---|---|---|
| Sea-surface temperature, 1991–2020 baseline | NOAA ERSSTv5 (Huang et al. 2017), doi:10.7289/V5T72FNM | Public domain (U.S. Government). Cite Huang et al. (2017) |
| Sea ice, observed 2005–2024 mean | NOAA/NSIDC Climate Data Record of Passive Microwave Sea Ice Concentration, Version 4 (Meier et al. 2021), doi:10.7265/efmz-2t65 | Free to use. Cite the data set |
| Ice Age ice-sheet outlines and retreat ages | Drawn for the app, to about 50–100 km, from published reconstructions: Dyke 2004; Hughes et al. 2016 (DATED-1); Ehlers & Gibbard 2011; Batchelor et al. 2019; Glasser et al. 2008; Ivy-Ochs 2015; Dalton et al. 2020; Stroeven et al. 2016 | Cited as references |
| Ocean carbonate chemistry | The constants used by CO2SYS: Lueker et al. 2000, Dickson 1990, Weiss 1974, Mucci 1983 | Published formulas |

### Climate data and models

| What | Source | Licence and credit |
|---|---|---|
| Climate patterns, aerosols, sea-ice thresholds, the sea-surface temperature pattern and the Last Glacial Maximum | CMIP6 model output from MPI-ESM1-2-LR, GFDL-ESM4 and MIROC-ES2L, read from the Pangeo CMIP6 archive on Google Cloud | CC BY 4.0 (all three models moved from CC BY-SA 4.0 to CC BY 4.0 in June 2022). See the [CMIP6 acknowledgement](#cmip6-acknowledgement) |
| Effective radiative forcing, 1750–2500 | IPCC AR6 Working Group I, Chapter 7 data (Smith et al. 2021, doi:10.5281/zenodo.5211357) | MIT ([licence text](#licence-texts)) |
| Greenhouse-gas concentrations and emissions for the SSP pathways | RCMIP v5.1 (Nicholls et al. 2020; Meinshausen et al. 2020) | Openly published. Cite the papers |
| Observed CO₂, CH₄ and N₂O, 2020–2024 | NOAA Global Monitoring Laboratory, global annual means | Public domain. Credit: NOAA GML |
| Ice-core greenhouse gases and past sea level | Bereiter et al. 2015 (CO₂), Loulergue et al. 2008 (CH₄), Schilt et al. 2010 (N₂O), Law Dome and EPICA (Holocene); Lambeck et al. 2014 and Spratt & Lisiecki 2016 (sea level) | Published data. Cited as references |
| Assessed numbers and benchmarks | IPCC (2021), Climate Change 2021: The Physical Science Basis, Working Group I contribution to the Sixth Assessment Report | Cited in the app's logs |

The climate engine's other physics references are listed in its physics logs and in the comments of its source.

### Solid Earth

| What | Source | Licence and credit |
|---|---|---|
| Plate boundaries and motions | PB2002 (Bird 2003, Geochemistry Geophysics Geosystems 4(3), 1027) | Free with citation |
| Mantle structure | S40RTS (Ritsema, Deuss, van Heijst & Woodhouse 2011, Geophysical Journal International 184, 1223) | Free with citation |
| Hotspots and plumes | Courtillot et al. 2003; Morgan & Morgan 2007; French & Romanowicz 2015; Sleep 1990; King & Adam 2014; Torsvik et al. 2006 | Cited as references |
| Magnetic field | IGRF-14, International Association of Geomagnetism and Aeronomy (Alken et al. 2025) | Free with citation |
| Radii and densities of Earth's layers | PREM (Dziewonski & Anderson 1981) | Cited as a reference |

### Volcanic eruptions

Global Volcanism Program, Smithsonian Institution, <https://volcano.si.edu/>. Volcanoes of the World database: the 2020 copy published as TidyTuesday's 2020-05-12 data, brought up to date by hand from the Global Volcanism Program's lists of each year's eruptions, to March 2026. Distributed by Smithsonian Institution, compiled by Venzke, E.

**Licence:** the Smithsonian's terms of use allow personal, educational and other non-commercial uses, with a citation and a link to the Smithsonian's site. The Crust & Tectonics card cites the program and links to it. Commercial use, including using the data to promote or advertise products or services, needs the Smithsonian's written permission.

### Sky

| What | Source | Licence and credit |
|---|---|---|
| The 5,044 stars brighter than magnitude 6 | d3-celestial by Olaf Frohn (Hipparcos and Yale Bright Star data) | BSD 3-Clause ([licence text](#licence-texts)) |
| Milky Way glow and faint stars | Drawn by the app from a model of the galactic plane, not from an image | — |

### Icons, fonts and shader code

| What | Source | Licence and credit |
|---|---|---|
| Layer icons: Atmosphere "Fluffy cloud", Transition Zone "Crystal growth" and Outer Core "Vortex" by Lorc; Mantle "Flame" by Carl Olsen; Lower Mantle "Hot surface" by Sbed | game-icons.net | CC BY 3.0. Credited on each layer card |
| Crust & Tectonics, Hydrosphere & Cryosphere and Inner Core icons | Drawn for GEO-SMart | — |
| Fonts in the PDF report | DejaVu Sans and DejaVu Sans Bold, cut down to the characters a report uses | Bitstream Vera licence; DejaVu changes are public domain ([licence text](#licence-texts)) |
| 3-D simplex noise in the shaders | webgl-noise by Ian McEwan (Ashima Arts) and Stefan Gustavson | MIT ([licence text](#licence-texts)) |
| A small hash function in the shaders | "Hash without Sine" by David Hoskins | MIT ([licence text](#licence-texts)) |
| Tone-mapping curve | The ACES filmic curve fit published by Krzysztof Narkowicz (2016) | A published formula |

## CMIP6 acknowledgement

We acknowledge the World Climate Research Programme, which, through its Working Group on Coupled Modelling, coordinated and promoted CMIP6. We thank the climate modeling groups for producing and making available their model output, the Earth System Grid Federation (ESGF) for archiving the data and providing access, and the multiple funding agencies who support CMIP6 and ESGF.

| Model | Institution | Experiments used |
|---|---|---|
| MPI-ESM1-2-LR | MPI-M (Max Planck Institute for Meteorology) | piControl, historical, ssp126, ssp245, ssp585, abrupt-4xCO2, lgm |
| GFDL-ESM4 | NOAA-GFDL (Geophysical Fluid Dynamics Laboratory) | piControl, historical, ssp126, ssp245, ssp585 |
| MIROC-ES2L | MIROC (JAMSTEC, AORI, NIES and R-CCS) | piControl, lgm |

## Licence texts

The same text is in a comment at the top of `index.html`.

```
1. Star positions, magnitudes and colours (SKY_STARS_B64), from d3-celestial's stars.6.json (Hipparcos / Yale Bright Star data).

Copyright (c) 2015, Olaf Frohn
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the
following conditions are met:
1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following
   disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following
   disclaimer in the documentation and/or other materials provided with the distribution.
3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote
   products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

2. PDF report fonts (GEO_PDF_FONTS): subsets of DejaVu Sans and DejaVu Sans Bold.

Copyright (c) 2003 by Bitstream, Inc. All Rights Reserved. Bitstream Vera is a trademark of Bitstream, Inc.
DejaVu changes are in public domain.

Permission is hereby granted, free of charge, to any person obtaining a copy of the fonts accompanying this license
("Fonts") and associated documentation files (the "Font Software"), to reproduce and distribute the Font Software,
including without limitation the rights to use, copy, merge, publish, distribute, and/or sell copies of the Font
Software, and to permit persons to whom the Font Software is furnished to do so, subject to the following conditions:

The above copyright and trademark notices and this permission notice shall be included in all copies of one or more
of the Font Software typefaces.

The Font Software may be modified, altered, or added to, and in particular the designs of glyphs or characters in the
Fonts may be modified and additional glyphs or characters may be added to the Fonts, only if the fonts are renamed to
names not containing either the words "Bitstream" or the word "Vera".

This License becomes null and void to the extent applicable to Fonts or Font Software that has been modified and is
distributed under the "Bitstream Vera" names.

The Font Software may be sold as part of a larger software package but no copy of one or more of the Font Software
typefaces may be sold by itself.

THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO
ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF COPYRIGHT, PATENT,
TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL BITSTREAM OR THE GNOME FOUNDATION BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER
DEALINGS IN THE FONT SOFTWARE.

Except as contained in this notice, the names of Gnome, the Gnome Foundation, and Bitstream Inc., shall not be used in
advertising or otherwise to promote the sale, use or other dealings in this Font Software without prior written
authorization from the Gnome Foundation or Bitstream Inc., respectively. For further information, contact: fonts at
gnome dot org.

3. MIT License, for:
   - the climate engine's effective radiative forcing series, from IPCC-WG1/Chapter-7 (Smith et al. 2021,
     https://doi.org/10.5281/zenodo.5211357): Copyright (c) 2020 Chris Smith
   - the shaders' 3-D simplex noise (webgl-noise, https://github.com/stegu/webgl-noise):
     Copyright (C) 2011 by Ashima Arts (Simplex noise)
     Copyright (C) 2011-2016 by Stefan Gustavson (Classic noise and others)
   - the shaders' small hash ("Hash without Sine", https://www.shadertoy.com/view/4djSRW): Copyright (c) 2014 David Hoskins

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
