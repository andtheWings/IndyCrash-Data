🚸 IndyCrash-Data
===

Hello! I'm Daniel, a pediatric resident in Indianapolis who is passionate about the built environment's role in improving people's health and safety. I am grateful for public access to the awesome [ARIES datasets](https://hub.mph.in.gov/dataset/aries-crash-data-2007-2017) and wanted to give back to the road safety community by sharing my workflow for  data prep. 

## Rationale

As partners with the [Indiana Management Performance Hub](https://www.in.gov/mph/), the Indiana State Police publish annual automobile crash data to the ARIES collection:

> The Automated Reporting Information Exchange System (ARIES) is the State of Indiana’s crash repository. Crash data is generated through first responder crash reports and collected within ARIES. Data is available for 2007 to 2017. Examples of this data include crash details such as, vehicle information, road conditions, crash severity, weather conditions, location, date, and time.

There are two issues with the data that this dataset addresses.

### Issue 1 -- ARIES data is separated into annual reports:

Solution -- We combine all ARIES datasets from annual reports into a unified database that covers 2007 to present.

### Issue 2 -- Each year's table has records that mix observational units:

One of the principles of ["tidy data"](https://tidyr.tidyverse.org/articles/tidy-data.html) is that "each type of observational unit forms a table". Because ARIES data is stored with a mix of observational units in each row, there is risk for redundacy of data storage that can lead to inconsistencies depending on how data is queried. 

> Further explanation of this issue is forthcoming!

Solution -- We separate variables into 3 tables representing people, vehicles, and crash events respectively.

## Who is this for?

I'm strong believer in the value of [citizen scientists](https://en.wikipedia.org/wiki/Citizen_science) who contribute their efforts and expertise to the greater good. Anybody can be a citizen scientist!

## Why?

I have generated this dataset as part of a larger effort to understand the dyanamics of risk for pedestrian/bicyclist crashes around the city of Indianapolis. 

## To Be Continued

Keep an eye out for updates on this work!
