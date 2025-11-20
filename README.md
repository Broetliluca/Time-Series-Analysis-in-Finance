# Time-Series-Analysis-in-Finance
Shared Folder for Study Project

## Group members of the assessment
- Mattia Bettoja
- Luca Signorini

## General idea of the case study
**Einfluss von CO₂-Zertifikatpreisen auf die Renditen oder Preise von Renewable Energy und/oder green ETFs**

## Brief description of the data and data sources to be used
- CO₂-Zertifikatpreise -> EU ETS
- MSCI Europ Paris Align Climat ETF -> Hypothesis: Positive corelation
- STOXX-Europe-600 Oil-Gas ETF -> Hypothesis: Negative correlation

## Brief description of the method to be used (optional)
- TBD


## DATA
### icap-graph-price 2019-2025
**Description** 
The Carbon Price Viewer shows the historical price of European allowances (EUA), i.e. the price of emitting 1 tonne of CO2-equivalent for a European industrial installation or airline covered by the Emissions Trading System. It does not mean that this price is always paid by polluters, as many of them receive free allowances. 

EUAs are traded between buyers and sellers, either directly “over the counter” or via organised markets. They can be traded either with immediate delivery (spot) or with delivery in the future, usually at slightly different prices. Up until December 2009, the price shown is based on spot-month continuous contract calculation. After that date, it corresponds to auction settlement prices, from the European Energy Exchange AG.

**Data Quality**
 - Weekly second marked data
 - unregulary dayli primary market data

### iShares-MSCI-Europe-Paris-Aligned-Climate-UCITS-ETF-EUR-Acc_fund
**Description**
https://www.blackrock.com/uk/individual/products/318925/ishares-msci-europe-paris-aligned-climate-ucits-etf?

**Data Quality** 
- Daily data since Fund has been mad in 2021
- Date, Curreny (EUR), NAV per Share, Share Outstanding, Total Net Assets, Fund Return Series, Benchmark Return Series

### STOXX-Europe-600-Oil--Gas-UCITS-ETF-DE_fund
**Description**
https://www.ishares.com/ch/privatkunden/de/produkte/251954/ishares-stoxx-europe-600-oil-gas-ucits-etf-de-fund#/

## Understanding of ETF Flow
<img width="470" height="228" alt="image" src="https://github.com/user-attachments/assets/0bc3656d-5ec1-4c01-9629-f71ac589e9e9" />


**Data Quality** 
- Daily data since Fund has been mad in arround 2002
- Date, Curreny (EUR), NAV per Share, Share Outstanding, Total Net Assets, Fund Return Series, Benchmark Return Series
