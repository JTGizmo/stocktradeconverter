# stocktradeconverter
Goal: The goal is to download user etoro transactions that were purchased in USD and covert the amounts to historic EUR of matching dates. I.e. if you purchased 1 stock for 10 USD on 01.01.2010 then you convert the USD value to EUR based on currency exchange rate of 01.01.2010.

Required steps for the converter
1. Extact user transaction data from etoro
2. Extract eestipank.ee currency date and match the currency for the same time frame
3. Convert the etoro transactions from USD to EUR 
4. Output the transactiosn in EUR corresponeding to etoro transactions

