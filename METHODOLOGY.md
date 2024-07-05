# METHODOLOGY

## UN API IS PUBLICLY ACCESSIBLE

- NO AUTHENTICATION REQUIREMENT


[UNHCR - Global Public API](https://api.unhcr.org/population)


###### NOTE:

Direct API query to the U.N. Database returns content in JSON format. 

The following data fields are presented by the API:

> page,short-url,maxPages,items,year,coo_id,,coo_name, coo,coo_iso,coa_id,,coa_name,coa,coa_iso,refugees, asylum_seekers,returned_refugees,idps,returned_idps, 
> stateless,ooc,oip,hst



## API Output Archived to JSON and Converted

API queries were initiated for each country of asylum, and saved in the JSON folder titled JavaScript_Object_Notation.  The folders titled Excel-XLSX and Comma-Delimited are populated with their corresponding files which were converted from JSON.



## DATA


The data contained is in multiple formats for wider access (XLSX, CSV, JSON).  The data in summary reveals UNHCR refugee and asylee records for all available nations.  With this data, you may total the refugees and asylum_seekers (if they exist) for years 1951 thru 2024 for any available nation, you may identify trends by country of origin on an annual basis, and much more.  Excel pivot tables may be exceptionally useful in your own analysis.


## Example API Query

The following API query structure was used successfully as of JUL 4, 2024.

NOTE THAT *** = COUNTRY CODES USED BY U.N. IN README.md

```
https://api.unhcr.org/population/v1/population/?limit=100000
&dataset=population
&displayType=totals
&columns%5B%5D=refugees
&columns%5B%5D=asylum_seekers
&columns%5B%5D=idps
&columns%5B%5D=oip
&columns%5B%5D=stateless
&columns%5B%5D=hst
&columns%5B%5D=ooc

&year%5B%5D=1951    &year%5B%5D=1952    &year%5B%5D=1953    &year%5B%5D=1954    &year%5B%5D=1955    &year%5B%5D=1956    &year%5B%5D=1957    &year%5B%5D=1958    &year%5B%5D=1959    &year%5B%5D=1960    &year%5B%5D=1961    &year%5B%5D=1962
&year%5B%5D=1963    &year%5B%5D=1964    &year%5B%5D=1965    &year%5B%5D=1966    &year%5B%5D=1967    &year%5B%5D=1968    &year%5B%5D=1969    &year%5B%5D=1970    &year%5B%5D=1971    &year%5B%5D=1972    &year%5B%5D=1973    &year%5B%5D=1974
&year%5B%5D=1975    &year%5B%5D=1976    &year%5B%5D=1977    &year%5B%5D=1978    &year%5B%5D=1979    &year%5B%5D=1980    &year%5B%5D=1981    &year%5B%5D=1982    &year%5B%5D=1983    &year%5B%5D=1984    &year%5B%5D=1985    &year%5B%5D=1986
&year%5B%5D=1987    &year%5B%5D=1988    &year%5B%5D=1989    &year%5B%5D=1990    &year%5B%5D=1991    &year%5B%5D=1992    &year%5B%5D=1993    &year%5B%5D=1994    &year%5B%5D=1995    &year%5B%5D=1996    &year%5B%5D=1997    &year%5B%5D=1998
&year%5B%5D=1999    &year%5B%5D=2000    &year%5B%5D=2001    &year%5B%5D=2002    &year%5B%5D=2003    &year%5B%5D=2004    &year%5B%5D=2005    &year%5B%5D=2006    &year%5B%5D=2007    &year%5B%5D=2008    &year%5B%5D=2009    &year%5B%5D=2010
&year%5B%5D=2011    &year%5B%5D=2012    &year%5B%5D=2013    &year%5B%5D=2014    &year%5B%5D=2015    &year%5B%5D=2016    &year%5B%5D=2017    &year%5B%5D=2018    &year%5B%5D=2019    &year%5B%5D=2020    &year%5B%5D=2021    &year%5B%5D=2022
&year%5B%5D=2023    &year%5B%5D=2024

&coo_all=true&coa=***&page=1

```

----------------------------------------------------------------

## HISTORICAL DATA VALIDATION UNHCR API - ARCHIVE.ORG
SEE Historical UNHCR API query with U.S. specified as country of asylum, requesting UNHCR provide all refugee/asylee data for the period 1951-2022 [FEB 24, 2023].

```
https://web.archive.org/web/20230224024902/https://api.unhcr.org/population/v1/population/?limit=100000&dataset=population&displayType=totals&columns%5B%5D=refugees&columns%5B%5D=asylum_seekers&columns%5B%5D=idps&columns%5B%5D=oip&columns%5B%5D=stateless&columns%5B%5D=hst&columns%5B%5D=ooc&year%5B%5D=1951&year%5B%5D=1952&year%5B%5D=1953&year%5B%5D=1954&year%5B%5D=1955&year%5B%5D=1956&year%5B%5D=1957&year%5B%5D=1958&year%5B%5D=1959&year%5B%5D=1960&year%5B%5D=1961&year%5B%5D=1962&year%5B%5D=1963&year%5B%5D=1964&year%5B%5D=1965&year%5B%5D=1966&year%5B%5D=1967&year%5B%5D=1968&year%5B%5D=1969&year%5B%5D=1970&year%5B%5D=1971&year%5B%5D=1972&year%5B%5D=1973&year%5B%5D=1974&year%5B%5D=1975&year%5B%5D=1976&year%5B%5D=1977&year%5B%5D=1978&year%5B%5D=1979&year%5B%5D=1980&year%5B%5D=1981&year%5B%5D=1982&year%5B%5D=1983&year%5B%5D=1984&year%5B%5D=1985&year%5B%5D=1986&year%5B%5D=1987&year%5B%5D=1988&year%5B%5D=1989&year%5B%5D=1990&year%5B%5D=1991&year%5B%5D=1992&year%5B%5D=1993&year%5B%5D=1994&year%5B%5D=1995&year%5B%5D=1996&year%5B%5D=1997&year%5B%5D=1998&year%5B%5D=1999&year%5B%5D=2000&year%5B%5D=2001&year%5B%5D=2002&year%5B%5D=2003&year%5B%5D=2004&year%5B%5D=2005&year%5B%5D=2006&year%5B%5D=2007&year%5B%5D=2008&year%5B%5D=2009&year%5B%5D=2010&year%5B%5D=2011&year%5B%5D=2012&year%5B%5D=2013&year%5B%5D=2014&year%5B%5D=2015&year%5B%5D=2016&year%5B%5D=2017&year%5B%5D=2018&year%5B%5D=2019&year%5B%5D=2020&year%5B%5D=2021&year%5B%5D=2022&coo_all=true&coa=USA&page=1
```

## Comment:

Excel or OpenOffice is recommended for use by the general public when working with these CSV or XLSX files.  Feel free to conduct your own investigation!

On the XLSX format, all fields are set as text in the event if anything MIGHT have a leading zero, such is maintained as was received.  You can change that easily in excel.

All attempts for accuracy in this process was performed.

Scripting was used.

Conversion to CSV and XLSX used minimal steps.

Due diligence is attempted at all times.
