# Interviewing data

As a data journalist, I think in terms of "interviewing" data, approaching it with questions for which I want to find answers. To do that, you need to understand the structure of your data, the operations you can apply to ask questions of it, and some core principles of using numbers in the newsroom.

In this presentation, I'll cover those principles.

<div class = "iframe-container">

<iframe class="responsive-iframe" src="https://docs.google.com/presentation/d/1ISyRziI_QXUhX5YDFaBOLrBwJ5WY0ooUud2w9y3__Tg/preview" allowfullscreen="allowfullscreen">

</iframe>

</div>

### The tool we will use

Our spreadsheet tool for this session will be [Google Sheets](https://workspace.google.com/products/sheets/). Use from [Drive](https://drive.google.com/drive/home) in your Google account.

### The data we will use

Download the zipped folder from [this link](data-march-sessions.zip) and unzip. It contains the following files that we will use in this session:

-   `indicators.csv` Data from the World Bank's [World Development Indicators](https://data.worldbank.org/indicator) portal, including the following variables:

    -   `country` Name of each nation/territory.

    -   `iso2c` `isoc3` Two- and three-letter codes for each nation/territory.

    -   `year` From 2010 to 2023.

    -   `gdp_percap` Gross Domestic Product per capita (per person) in current international dollars, corrected for purchasing power in different territories.

    -   `population` Estimated total population at mid-year, including all residents apart from refugees.

    -   `co2_emissions` Total greenhouse gas emissions (excluding land use, land-use change and forestry) in millions of metric tonnes of carbon dioxide equivalent.

    -   `pc_land_forest` Forest area as a percentage of land area.

    -   `pc_land_arable` Arable land as a percentage of land area.

    -   `land_area` Total land area in square kilometers.

-   `indicators_2023.csv` The same, filtered for 2023 only.

-   We will also import data from the file at this url:

    `https://raw.githubusercontent.com/paldhous/owid-covid/main/covid_owid.csv`.

    This has the number of new COVID cases and deaths reported worldwide for every day since the start of the pandemic until April 2023, as recorded by [Our World in Data](#0). It is good for showing how to perform anchored calculations and calculate rolling averages and cumulative totals for time-series data.

### Working with spreadsheets

I'll demonstrate working with this data in Google Sheets. Rather than trying to follow along in the live sessions, I'd suggest focusing on understanding the concepts, methods, and formulas I'm showing. You can put questions into the Zoom chat and we can cover in a Q&A at the end of the session.

The session will be recorded, so you can practice with the video at your own pace later.

### Resources

Sarah Cohen: [Common mistakes and how to avoid them](numbers-in-the-newsroom.pdf) Extract from the book *Numbers in the Newsroom*, sadly no longer available.

Ben Welsh: [Numbers in the Newsroom online calculators](https://observablehq.com/collection/@palewire/numbers-in-the-newsroom)

Paul Bradshaw: [Finding Stories With Spreadsheets](https://leanpub.com/spreadsheetstories/)\
E-book from the head of the Masters in Data Journalism program at Birmingham City University in the UK.

[Google Sheets function list](https://support.google.com/docs/table/25273?hl=en)\
A handy reference for all of the functions available in Google Sheets.
