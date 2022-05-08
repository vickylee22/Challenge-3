# Crypto Arbitrage

In this Challenge, you'll take on the role of an analyst at a high-tech investment firm. The vice president (VP) of your department is considering arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin trades on markets across the globe, can you capitalize on simultaneous price dislocations in those markets by using the powers of Pandas?

For this assignment, you’ll sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Your task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

This aspect of the Challenge will consist of 3 phases.

1. Collect the data.

2. Prepare the data.

3. Analyze the data. 

---

## Collect the Data
To collect the data that you’ll need, complete the following steps:

Instructions.

1. Using the Pandas read_csv function and the Path module, import the data from bitstamp.csv file, and create a DataFrame called bitstamp. Set the DatetimeIndex as the Timestamp column, and be sure to parse and format the dates.

2. Use the head (and/or the tail) function to confirm that Pandas properly imported the data.

3. Repeat Steps 1 and 2 for coinbase.csv file.

---

## Prepare the Data
To prepare and clean your data for analysis, complete the following steps:

1. For the bitstamp DataFrame, replace or drop all NaN, or missing, values in the DataFrame.

2. Use the str.replace function to remove the dollar signs ($) from the values in the Close column.

3. Convert the data type of the Close column to a float.

4. Review the data for duplicated values, and drop them if necessary.

5. Repeat Steps 1–4 for the coinbase DataFrame.

---

## Analyze the Data
Your analysis consists of the following tasks:

1. Choose the columns of data on which to focus your analysis.

2. Get the summary statistics and plot the data.

3. Focus your analysis on specific dates.

4. Calculate the arbitrage profits.

---

## License
MIT
