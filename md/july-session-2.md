# Making charts and maps with Datawrapper

I'll demonstrate how to make simple maps and charts with Datawrapper. Rather than trying to follow along in the live sessions, I'd suggest focusing on understanding wht I'd demonstrating showing. You can put questions into the Zoom chat and we can cover in a Q&A at the end of the session.

The session will be recorded, so you can practice with the video at your own pace later.

### The tools we will use

- **Datawrapper** Web app developed by German journalism organizations used to make simple online charts and maps by leading news outlets. No installation required, but you will need to [sign up](https://app.datawrapper.de/signin) for a free Datawrapper account.
- **Sublime Text** Text editor optimized for editing web pages and other code. Download from [here](https://www.sublimetext.com/). we will use to embed published Datawrapper charts.

### The data we will use

Download the zipped folder from **[this link](data-july-sessions.zip)** and unzip.

The folder contains the following files:

- `indicators_2023.csv` Data from the World Bank's World Development Indicators portal. Contains the following variables:
  - `country` Name of each nation/territory.
  - `iso2c` `isoc3` Two- and three-letter codes for each nation/territory.
  - `year` 2023 for this data.
  - `life_expectancy` Life expectancy at birth.
  - `gdp` Gross Domestic Product in current international dollars, corrected for purchasing power in different territories.
  - `gdp_per_capita` Gross Domestic Product per person in current international dollars, corrected for purchasing power in different territories.
  - `population` Estimated total population at mid-year, including all residents apart from refugees.
  - `co2_emissions` Total greenhouse gas emissions (excluding land use, land-use change and forestry) in millions of metric tonnes of carbon dioxide equivalent.
  -   `pc_land_forest` Forest area as a percentage of land area.
  -   `pc_land_arable` Arable land as a percentage of land area.
  -   `land_area` Total land area in square kilometers.
  - `region` As defined by the World Bank.
  - `capital` Capital city.
  - `longitude` `latitude` Coordinates at the center of each nation/territory.
  - `income` Current income group, as defined by the World Bank.
  - 
- `camp_fire.geoson` Geodata showing the area burned in the 2018 Camp Fire, the deadliest wildfire in California history.
- `index.html` An HTML document in which to embed Datawrapper charts.

### The charts and maps we will make

<div style="min-height:545px" id="datawrapper-vis-5ZvrE"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/5ZvrE/embed.js" charset="utf-8" data-target="#datawrapper-vis-5ZvrE"></script><noscript><img src="https://datawrapper.dwcdn.net/5ZvrE/full.png" alt="Area Burned in the Camp Fire (Locator map)" /></noscript></div>

<br>

<div style="min-height:508px" id="datawrapper-vis-0mTAl"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/0mTAl/embed.js" charset="utf-8" data-target="#datawrapper-vis-0mTAl"></script><noscript><img src="https://datawrapper.dwcdn.net/0mTAl/full.png" alt="The Health and Wealth of Nations (Scatter Plot)" /></noscript></div>

<br>

<div style="min-height:773px" id="datawrapper-vis-oKmSR"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/oKmSR/embed.js" charset="utf-8" data-target="#datawrapper-vis-oKmSR"></script><noscript><img src="https://datawrapper.dwcdn.net/oKmSR/full.png" alt="GDP and Greenhouse Gas Emissions for the World's Nations in 2023 (Table)" /></noscript></div>

<br>

<div style="min-height:367px" id="datawrapper-vis-y8F35"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/y8F35/embed.js" charset="utf-8" data-target="#datawrapper-vis-y8F35"></script><noscript><img src="https://datawrapper.dwcdn.net/y8F35/full.png" alt="Percentage of Forested Land by Nation in 2023 (Choropleth map)" /></noscript></div>

<br>

### Resources

[**Datawrapper Academy**](https://www.datawrapper.de/academy)
Tutorials for making charts and maps with Datawrapper.

[**Datawrapper blog**](https://www.datawrapper.de/blog)
Blog written by Datawrapper staff, has lots of tips on using the tool and for good practice in data visualization.

[**HEX codes to set transparency**](https://gist.github.com/lopspower/03fb1cc0ac9f32ef38f4)

[**Customizing tooltips in Datawrapper**](https://www.datawrapper.de/academy/i-want-to-change-how-my-data-appears-in-tooltips)
How to use HTML code and formatting formulas to improve your tooltips.

[**Flourish**](https://www.datawrapper.de/academy/i-want-to-change-how-my-data-appears-in-tooltips) Another web-based tool that allows you to make some more sophisticated visualizations, including animations. There are [training videos](https://www.datawrapper.de/academy/i-want-to-change-how-my-data-appears-in-tooltips).

[**Mapshaper**](https://mapshaper.org/)
Web app that can be used to convert other geodata formats to GeoJSON for use in Datawrapper.