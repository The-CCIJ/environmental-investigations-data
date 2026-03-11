## Acquiring, processing and cleaning data

### The tools we will use

-   [Google Pinpoint](https://journaliststudio.google.com/pinpoint/about/) to extract structured data from a series of documents and use its AI functions to obtain summaries of the documents. Sign up for access using an email address associated with your Google account, noting your status as a journalist.

-   [Open Refine](https://openrefine.org/) to process and clean data. Click the download button to download and install for your computer's operating system.

-   [Google Sheets](https://workspace.google.com/products/sheets/) to show how to join data from multiple tables.

### The data we will use

We will again use data from the zipped folder at [this link](data-march-sessions.zip) that you downloaded last week. It contains the following folders and files that we will use in this session:

-   `energy_lobbying` Folder containing the following:

    -   `documents` Subfolder containing "[Exhibit B](https://www.justice.gov/nsd-fara/page/file/1273636/dl?inline=)" documents filed with the U.S. Department of Justice by lobbyists representing "foreign principals" (which can be governments, organizations, corporations, or individuals) working in the field of energy in 2024 and 2025.

    -   `exhibits_b.csv` Structured data extracted from those documents, cleaned to standardize the names of the foreign principals.

    -   `foreign_principals.csv` Data with the countries of those foreign principals, which we will join to the extracted data.

-   `co2_emissions` Total greenhouse gas emissions (excluding land use, land-use change and forestry) in millions of metric tonnes of carbon dioxide equivalent. We will reshape this data from a wide to a "tidy" format.

-   `ucb_stanford.csv` Data on grants awarded by the U.S. government to the University of California, Berkeley and to Stanford University. It is ideal for demonstrating the power of Open Refine to clean and process "dirty" data prior to analysis.

### Portals with useful environmental data

-   The **World Bank’s [World Development Indicators](https://data.worldbank.org/indicator/?tab=all)** catalog contains data for thousands of variables, compiled by the bank, other UN agencies, and other reliable sources.
-   [**Our World In Data**](https://ourworldindata.org/) Many charts and maps with downloadable data, again compiled from multiple vetted sources by a team at the University of Oxford.
-   [**UN Environment Programme**](https://www.unep.org/data-resources)
-   [**UN Statistical Division**](https://unstats.un.org/UNSDWebsite/)
-   [**UN Data Explorer**](http://data.un.org/Explorer.aspx) Links to many UN databases.
-   [**EU Copernicus Climate Data Store**](https://cds.climate.copernicus.eu/) Great resource for climate and other environmental data, but requires some specialist knowledge to acquire and use its data.

### Google data search

-   [**Advanced search**](https://www.google.com/advanced_search) Using the options for "site or domain" (e.g. usgs.gov for data on earthquakes) and/or "filetype" (e.g. Excel spreadsheets) can help hone searches for data.
-   [**Dataset search**](https://datasetsearch.research.google.com/) A searchable catalog of data sources curated by Google.

### Capturing data from HTML tables

Install the **Table Capture** ([Chrome](https://chrome.google.com/webstore/detail/table-capture/iebpjdmgckacbodjpijphcplhebcmeop?hl=en) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/table-capture-firefox/)) extension for your browser.

### Downloading multiple files at once

Install the **DownThemAll!** ([Chrome](https://chrome.google.com/webstore/detail/downthemall/nljkibfhlpcnanjgbnlnbjecgicbjkge?hl=en) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/downthemall/)) extension for your browser.

### Extracting data from searchable online databases

#### Get to know the quirks of each database

When you start working with a new online database, take some time to familiarize yourself with how its searches work: Read the Help or FAQs, and then run test searches to see what results you obtain. Many online databases can be searched using Boolean logic, using the operators `AND`, `OR` and `NOT` to link search terms together. So find out how a particular database uses Boolean logic — and the default settings that it will use if you list search terms without any Boolean operators.

Putting search terms in quote marks often searches for a specific phrase. Also find out whether the database allows “wildcards,” symbols such as `*` or `%` that can be dropped into your search to obtain results with variations on a search term.

#### Beware search and download limits

Having run a search on an online database, you will usually want to download the results, so look for the download links or buttons.

A common problem with online databases, however, is that they may impose limits on the number of results that are returned on each search. And even when a search returns everything, there may be a limit on how many of those results can be downloaded to your own computer.

If broad searches on a database keep returning the same number of results, that is a sign that you are probably running up against a search limit, and any download will not contain the complete set of data that you are interested in. However, you may be able to work out ways of searching to obtain all of the data in chunks.

#### Download the entire database if possible

Downloading an entire database, where this is allowed, frees you from the often-limited options given on an online advanced search form. You can then upload the data into your own software, and query it in any way that you want.

So look for ways to grab all of the data. There may be a link to a bulk data download. One trick worth trying is to run a search on just the database’s wildcard character, or with the query boxes left blank.

Be aware, however, that large databases may exceed the limits of spreadsheet software. Google Sheets, for example, [currently has a limit](https://support.google.com/drive/answer/37603) of 10 million cells per spreadsheet.

### Do I need to clean, convert or reshape this data?

In this presentation I will discuss common problems with data that should be considered before moving on to analyze/interview the data:

::: iframe-container
<iframe class="responsive-iframe" src="https://docs.google.com/presentation/d/1flMmZnYZuK1F6LMYIyTNMFmiUc3oEf4012U27dTrbeY/preview" allowfullscreen="allowfullscreen">

</iframe>
:::

### **Using Google Pinpoint to extract structured data from documents**

I will demonstrate with our energy lobbying documents. This [video](https://www.youtube.com/watch?v=Rqr6rker5V0) from Google is another useful reference.

### Processing and cleaning data with Open Refine

I will demonstrate reshaping and cleaning data with Open Refine and show how it can be used to generate a reproducible recipe to repeat a data processing pipeline on data with the same format and column headers.

For the most part, I will use Open Refine's point-and-click interface, but for one data transformation I will use the following formula, which will be easier to copy-and-paste than to type:

`value.replace('$','').replace('(','-').replace(')','').replace(',','')`

### Open Refine resources

-   [Open Refine Wiki](https://github.com/OpenRefine/OpenRefine/wiki)

-   [Open Refine User Manual](https://openrefine.org/docs)

-   [Open Refine Recipes](https://github.com/OpenRefine/OpenRefine/wiki/Recipes)
