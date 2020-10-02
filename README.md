# Portfolio Watcher

This Jupyter Notebook can be used for continuous monitoring of the status of a trading portfolio in Dhaka Stock Exchange. The initial status of the portfolio i.e. name of the instruments, number of shares under portfolio, average cost and total cost must be provided. The standard pdf format that your broker provides can be used off-the-shelf. Upload the pdf file in Google Colab and run the whole notebook.The status would keep updating every 30 seconds, you can change the interval if you want.   

## Disclaimer
1. You need to upload the portfolio file from the "Files" section. The accepted format is either .pdf or .xlsx. 
2. The broker provided .pdf file might not suit the code, in that case you may provide your portfolio data in .xlsx format. Please ensure that the .xlsx file has TRADING.CODE, Total Quantity, Average Cost and Total Cost in the first four columns. 
3. The gain/loss is calculated considering Latest Trading Price during the trading hours and Closing Price after trading hours.
