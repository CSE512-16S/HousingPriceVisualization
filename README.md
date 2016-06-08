# Final Project

## Team Members

- Mingwei Tang
- Xiaochuan Du

## Visualization for Housing Price in Greater Seattle Area

In the recent 20 years, the median housing sales pricing in the greater Seattle area has fluctuated dramatically. From 1996 to 2007, there was a steady growth in housing price. However, during the financial crisis in 2008, the median housing price in Greater Seattle area has shrank nearly 30% percent. In recent 5 years, the housing market has been gradually recovered from financial crisis. Recently, the housing price has increase by 50% and exceed the price before the financial crisis. 

Along side with the housing price, there is a booming of IT industries in Great Seattle Area. Besides big companies like Microsoft and Amazon, Many start-ups choose their location to be in Greater Seattle Area. As a consequence, Seattle has a annual population growth rate of 2.8\% each year, which is the fastest among all cities in United States. With more people moving to Seattle in the recent years, it is time to use the power of visualization to demonstrate the housing price. In this project our goal is to explore the housing sales price in greater Seattle area in the past 20 years. We hope our project can help people making decisions on buying or renting a house. 


### Data Domain

The data we use comes fromt the Zillow Research website: [http://www.zillow.com/research/data/](http://www.zillow.com/research/data/). The data contains median for different types of housing (condo, studio, one bedroom apartment, etc.) in city level, county level, zip code level and neighborhood level.

## Our Interactive Visualization

### Running Instructions

Access our visualization at [https://github.com/CSE512-16S/fp-mingweiwilliamtang-xdu2peter](https://github.com/CSE512-16S/fp-mingweiwilliamtang-xdu2peter) or download this repository and run `python -m SimpleHTTPServer 8000` and access this from http://localhost:8000/.

###Overview of Major Interactions:
* <b>Click an arrow</b> to explore more at a particular location. 
* <b>Search a zipcode in the search box</b> to relocate the map at the interested area.
* <b>Click on the histogram</b> to discover more infomation of the Washington State housing price.
* and more...

## Development Process
Our group delegated tasking on the major components of our visualization to the two members, but we spent a lot of time coding all together in the office. 

We spent weeks to explore the functionality of the Google Map API. Mingwei spent time collecting and cleaning the data from Zillow. Xiaochuan created customized icons, initiated and updated animations of the markers, and changed the whole theme for better visualization. We both fine-tuned the map and interactions to the stage you see now. Ming wei created the line charts and histograms in D3, while Xiaochuan setup the SlideReveal to work properly. We worked together on the poster and report.
