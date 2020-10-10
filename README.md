### Vanguard-Group
## Group Project #1

## Engineers
Bjorn --
Kevin --
Roman -- 

## Introduction

By the end of April 2020 global cases for COVID-19 had surged past 1,000,000 patients. Along with the pandemic an increasing amount of countries showed reduced economic activity. Global equity markets and traditional economic benchmark indicators were negatively impacted.

The goal of our project is to further understand the relationship between reported cases, reported deaths, and the performance of global market indexes. To do so, we will compare statistics for daily coronavirus cases and deaths being reported from three large, heavily effeced countries in seperate geographical locations across three continents, and compare them against daily primary market index returns in those countries over the same period of time. 

The data used will be the daily COIVD-19 cases and deaths  with relatively reliable coronavirus statistics: USA, Brazil, and India; and the daily returns posted from equity markets indices: USA’s S&P 500, India's S&P BSE Sensex, and Brazil's BVSP.

We then will analyze and correlate the data to find any potential connection, and see if the data lends itself to conclusions that could be provide valuable insight to affected communities and wary investors. 

## Hypothesis

We posit that it is likely the market will react negatively on days where reported cases are higher.
Our team hypothesizes that a negative correlation will exist between daily returns and percent change in new COVID-19 cases reported within the market’s respective countries. 

H₀: The number of daily new COVID-19 cases in USA, India, and Brazil has no effect on the daily returns for these countries’ respective major equity market indices.

H₁: The number of daily new COVID-19 cases in USA, India, and Brazil has a negative effect on the daily returns for these countries’ respective major equity market indices.


We posit that it is likely a percent increase in cases would correlate with a spike that would simultaneously breed lethality within the respective countries.
Our team hypothesizes that a positive correlation will exist between daily reported cases and daily reported deaths within the respective countries. 

## Psuedocode
Import India Coronavirus dataset from Kaggle as NEW CASES PER DAY
> Completed SAT OCT.3 

Import India SENSEX Stock Market Index from Yahoo Finance API and calculate daily returns
> Completed SAT OCT.3

Determine time periods reflected and do an inner join so only like days are reflected
> Completed SAT OCT.3

Calculate correllation between  NEW CASES PER DAY and SENSEX daily returns
> Completed SAT OCT.3

Import U.S. Coronavirus dataset from Kaggle as NEW CASES PER DAY
> Completed SAT OCT.3

Import S+P 500 data and calculate daily returns
> Completed SAT OCT.3

Determine time periods reflected and do an inner join so only like days are reflected
> Completed SAT OCT.3

Calculate correllation between  NEW CASES PER DAY and S+P 500 daily returns
> Completed SAT OCT.3
