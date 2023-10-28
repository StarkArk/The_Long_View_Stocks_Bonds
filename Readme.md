# Overview  
  
An exploration of Edward McQuarrie's novel data set of stock and bond returns going back to 1793.  
  
Select Questions  
&emsp; - Do stocks outperform bonds?  
&emsp; - Are there significant periods where bonds outperformed?  
&emsp; - What are the maximum and minimum returns one can expect?  


## Background
  
Do stocks outperform bonds? In 1994 Jeremy Siegel published his widely admired book "Stocks for the Long Run". At the heart which is
the empirical claim that stocks outperform bonds. He backs this claim with empirical evidence of stock/bond returns stretching back to
1802. The book is enormously popular in the investor community and currently in its 6th edition update.  
  
In 2021 Edward McQuarrie, a retired professor, recreated Siegel's research making select updates and "changes" to his historical data.
Primarily, these were significant changes to certain periods in the 1800's affecting the returns of the stock and bond series that
underlies Siegel's key findings.  
  
## Data  
  
&ensp; Edward McQuarrie's Working Paper <ins>Stocks for the Long Run? Sometimes Yes. Sometimes No.</ins>  
  
&emsp; https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3805927  
  
&ensp; Original Spreadsheet Data can be found on McQuarrie's website https://www.edwardfmcquarrie.com/?p=579  
  
## Cleaning  
  
Starting with McQuarrie's Data, more data was added for years 2020-2023 consistent with the methodology he used.  
    
- Stock returns were extended using the total returns of the etf VTI(Vanguard Total Stock Market Index Fund).  
- Bond returns were taken from the etf VCLT(Vanguard Long-Term Corporate Bond Index Fund) 
- Yearly inflation(cpi) was obtained from the Department of Labor website  
  
Initial Cleaning and wrangling were done in excel then included in the resulting file "mcquarrie_real_stock_bond_returns_prepped_csv" and
can be found in this repository.  
  
## Summary Conclusion  
  
Except for some significant periods in the 1800's stocks tend to outperform bonds. Siegel's empirical claim of stock outperformance stands up
to the new scrutiny, mostly. Bonds did quite well with respect to stocks during much of the 1800's but not so well in the 1900's.