# Portfolio Watcher

This Jupyter Notebook can be used for continuous monitoring of the status of a trading portfolio in Dhaka Stock Exchange. The initial status of the portfolio i.e. name of the instruments, number of shares under portfolio, average cost and total cost must be provided. The standard pdf format that your broker provides can be used off-the-shelf. Upload the pdf file in Google Colab and run the whole notebook.The status would keep updating every 30 seconds, you can change the interval if you want.   

## Disclaimer
1. The broker provided pdf file might not suit the code, in that case you may provide the initial data in .xlsx file, that would require minor change in the code obviously
2. The gain/loss is calculated considering Latest Trading Price during the trading hour and Closing Price after trading hour.
