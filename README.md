# A Whale Off the Port(folio)

Requirements:
- Jupyter notebook
- Python libraries: Pandas, Numpy, Datetime, Pathlib, Matplotlib

Overview:

- Data cleaning:
  
  - Whale_returns.csv
   - Removed empty feilds.
   - Sorted index.
  
  - SNP500_history.csv
   - Renamed SNP500 column as "Close"
   - Removed empty feilds.
   - Sorted index
  
  - Algo_returns.csv
   - Removed empty feilds
   - Sorted index

After cleaning all the CSV files, they were merged as combined portfolio and did performance, risk and rolling statistics analysis.

- Performance analysis
 - Daily Returns
 ![](https://raw.githubusercontent.com/bhatt11z/A-Whale-Off-the-Port-folio-/main/Screenshot%202021-06-29%20at%209.38.37%20PM.png)
 
 - Cumulative Daily Returns
 ![](https://raw.githubusercontent.com/bhatt11z/A-Whale-Off-the-Port-folio-/main/Screenshot%202021-06-29%20at%209.40.43%20PM.png)
