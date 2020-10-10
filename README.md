### Vanguard-Group
## Group Project #1

## Engineers
Bjorn --
Kevin --
Roman -- 

## Introduction

By the end of April 2020 global cases for COVID-19 had surged past 1,000,000 patients. Along with the pandemic an increasing amount of countries showed reduced economic activity. Global equity markets and traditional economic benchmark indicators were negatively impacted.

The goal of our project is to further understand the relationship between reported cases, reported deaths, and the performance of global market indexes. To do so, we will compare statistics for daily coronavirus cases and deaths being reported from three large, heavily effeced countries in seperate geographical locations across three continents, and compare them against daily primary market index returns in those countries over the same period of time. 

The data used will be the daily COVID-19 cases and deaths from KAGGLE from countries with relatively reliable coronavirus statistics: USA, Brazil, and India; and the daily returns posted from equity markets indices: USA’s S&P 500, India's S&P BSE Sensex, and Brazil's BVSP.

We then will analyze and correlate the data to find any potential connection, and see if the data lends itself to conclusions that could be provide valuable insight to affected communities and wary investors. 

## Hypothesis

We posit that it is likely the market will react negatively on days where reported cases are higher. As such, our team hypothesizes that a negative correlation will exist between daily returns and percent change in new COVID-19 cases reported within the market’s respective countries. 

H₀: The number of daily new COVID-19 cases in USA, India, and Brazil has no effect on the daily returns for these countries’ respective major equity market indices.

H₁: The number of daily new COVID-19 cases in USA, India, and Brazil has a negative effect on the daily returns for these countries’ respective major equity market indices.


We posit that it is likely a percent increase in cases would correlate with a coronavirus spike that would simultaneously breed lethality within the respective countries.
Our team hypothesizes that a positive correlation will exist between daily reported cases and daily reported deaths within the respective countries. 

H₀: The number of daily new COVID-19 cases in USA, India, and Brazil has no effect on the daily deaths for these countries.

H₁: The number of daily new COVID-19 cases in USA, India, and Brazil has a positive effect on the daily deaths for these countries.

We posit that either reported deaths OR reported cases will affect the index more
H₀: Deaths and cases equally affect indexes

H₁: Deaths OR Cases superiorly impact

We posit that the United States will show the greatest reactionary volatility 
H₀: Countries show the same reactionary volatility
H₁: United States will show the greatest reactionary volatility 

## Psuedocode for Kevin's Demonstration
Import India Coronavirus dataset from Kaggle as NEW CASES PER DAY
> Completed SAT OCT.3 

Import India SENSEX Stock Market Index from Yahoo Finance API and calculate daily returns
> Completed SAT OCT.3

Determine time periods reflected and do an inner join so only like days are reflected
> Completed SAT OCT.3

Calculate correllation between  NEW CASES PER DAY and SENSEX daily returns
> Completed SAT OCT.3

Determine time periods reflected and do an inner join so only like days are reflected
> Completed SAT OCT.3

Repeat for U.S., Brazil
> Completed SAT OCT.3

## Visualization
Graph 1(Bjorn): Mapbox 
THis graph visualizes that the pandemic is relatively reflective in each of the three countries, and highlights the sheer signifigance of the pandemic. These three countries along have 

Graph2:(Roman) Total confirmed deaths by country


Graph (bjorn) percent change in deaths

Graph Market Daily returns(kevin)

Heatmap(bjorn

## Limitations

dropna() function limited our comparable data to only 3/19-7/21 so only a period of 4 months, but the entries over that time period were sufficient to show our points and find results.

Brazil (and all countries) may be misrepresenting their coronavirus statistics, particularly as there was a scandal when brazil deaths spiked and Bolsonaro stopped presenting the data to the CDC Because India and Brazil may have less sophisticated testing infrastructure leading to underrepresented statistics in both cases and deaths

Percent change data in the first month when cases were initially low was far more volatile than market index data could ever be, including spikes of over 100% in a day for some outlying cases; this may have skewed the correllation data.

## Conclusions
We were incorrect that market will react negatively on days where reported cases are higher. All three countries' indexes had different reactions to the cases and deaths statistics as you saw in the heatmap. Additionally, all of the correlations were relatively low.
We think that means that there is little reaction to daily new cases, and as such investors need not necesarily worry on a daily basis about the new cases statistics.

We were correct that cases and deaths were correllated in all three countries, as was to be expected.

We were incorrect in that deaths and cases equally affect indexes, if any effect was present at all it did not seem to differentiate between the effect of cases or deaths.

We were correct that that the United States showed the greatest reactionary volatility! This should inform investors that the S+P 500 is wary of a bubble and could lose a large amount in a relatively small period of time in response to negative news.

## Next steps/Follow up research

We thought it would be interesting to look at data for different time periods; i.e. weekly or monthly, and see if the results were more indicative of a correlation trend.
Also, more data will accumulate over the next months and may yeild results; i.e. it would be interesting to reveiw this project again in a year or so and see if anything changed.

# Sources
https://www.kaggle.com/unanimad/corona-virus-brazil
