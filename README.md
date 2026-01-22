![Made with Python](https://forthebadge.com/images/badges/made-with-python.svg)
![Build with Love](http://ForTheBadge.com/images/badges/built-with-love.svg)

```ascii
██████╗ ██╗   ██╗ ██████╗ ██╗  ██╗ ██████╗ 
██╔══██╗╚██╗ ██╔╝██╔═══██╗██║ ██╔╝██╔═══██╗
██████╔╝ ╚████╔╝ ██║   ██║█████╔╝ ██║   ██║
██╔══██╗  ╚██╔╝  ██║   ██║██╔═██╗ ██║   ██║
██║  ██║   ██║   ╚██████╔╝██║  ██╗╚██████╔╝
╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ 

       by Hex (@RemiH06)          version 1.2
```

![Maintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)

### General Description
Main functions taken from https://dev.to/chukhraiartur/scrape-google-flights-with-python-4dln
The scraper automation and the dataset maker work pretty good. 
Using the Guadalajara-Tokyo dataset, created a model that could predict flight prices.

## Installation

1. Install requirements with the following commands:

   `pip install playwright selectolax`
   `playwright install chromium`

## Features

- Scrapes flights
- Unit: individually scraping, just informations with specific params
- Process: massive scraping, saves info with pandas in an excel file so it can be analyzed later
- Within predict.ipynb there are models that can help predicting flight prices.