# Quantative_Option_Chain_Analytics_Nifty_23_06_2026

# Motivation of this project 
* option chain analysis for collective market expectations.
* Open intreset reveals trader positing for long term as well as short term analysis
* Implied volatility reveals the uncertainity.
* Put/Call behaviour show resistance as well as support for the underlying assets.
--
## Some financial glossory:
**Strike Price :** The specific price at which the buyer can buy (call option) and sell (put option) the underlying market asset. The market's current price usually sits in the middle, dividing in-the-money (ITM) and out-of-the-money(OTM) strikes. 

**Call Open Intreset (OI) :** The total number of outstanding call contracts currently active. HIgh call OI shows a strong resistance level. 

**Call Change OI** : The total change in OI during a trading session tells us above of upcoming resistance/support.

- **Call Volume** : The total number of call contracts traded duing the current trading session, showing the most actively traded strike price. 

**Call IV - Implied Volatility** - A measure of the expected future volatility of the underlying asset. Higher IV shows higher option permiums. 

**Call LTP (Last Traded Price) :**   Current price of the market premium you need to pay to buy a call option at that strike price.



> Similarly we have put side glossary as : 


**Put OI (Open Interest) :** The total number of outstanding put contracts. High Put OI typically highlights a strong support level.

**Put Change OI:** The net change in open interest for that specific put strike during the day.

**Put Volume:** The total number of put contracts traded today.

**Put IV:** The implied volatility for the put option.

**Put LTP:** The current premium you would pay to buy a put option at that strike.

<h1> Dataset Description</h1>

**Source** - NSE Option Chain 
**Underlying Asset** - NIFTY 50
**Expiry Date** - 23 June 2026

<h1> Data Cleaning </h1>

>step 1 - Rename the columns for call and put options.
> step 2 - Rename duplicated header row for better reading.
> step 3 - replace '-' with NaN using 'numpy'.
> step 4 - convert string (10,550) into numeric value using new function.
> step 5 - Validation of the data.
