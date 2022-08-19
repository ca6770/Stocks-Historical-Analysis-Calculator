# Stocks-Historical-Data-Analyzer
An analysis tool designed to analyze the Historical Data of any stock using Google Finance

Link for the Analysis Tool: https://docs.google.com/spreadsheets/d/1-a1v6TiHxwl89XaIAvplzy3hs_JbwQyHPUL3bK_blh0/edit?usp=sharing 

Stocks-Historical-Data-Analyzer is an analysis tool to do data analysis using Open(O), High(H), Low(L), Close(C), PrevClose(P) i.e OHLC. The aim of the tool is to find out that if there exists any pattern between (O, H, L, C, P) for any stock.

Functioning of Stocks-Historical-Data-Analyzer
Just enter the ticker of stock you want to analyze
Analyzer will fetch the complete historical data of stock using google finance
Now, different statistical methods are applied to analyze this data and finding patterns
The analyzer will give insights about the probability distribution of the stock's intraday movement.
Using the insights one can give decide to select a stock which can give relatively more margin on a intraday trade in a non volatile market


In img1, we just have to enter the ticker of the company & it will load its last 5 years' historical data.
![Img1](https://user-images.githubusercontent.com/36085369/185718005-31db5b27-9154-4878-80df-fa349daefe38.png)


In img2 & img3, the insights from the historical data are shown. These are just 2 of the 9 graph insights.
![img2](https://user-images.githubusercontent.com/36085369/185718075-3652a222-716f-4266-9a5c-748df6ab6e4d.png)
![img3](https://user-images.githubusercontent.com/36085369/185718088-b1a441fa-688c-4b78-9d86-c0f5854066cd.png)


In img2,
the x-axis represents by what %, high is above from low i.e (H-L)/L*100
the y-axis represents the probability with respect to every point of (H-L)/L*100
The area under the curve gives the probability in a particular range.
From all the observations of (H-L)/L*100 recorded on different dates, the mean, median, mode & the range where the highest probability occurs is calcualted.

The same is done with multiple data points to find out some kind of pattern. All this is based on the last 5 years' historical data. These insights can be used with technical analysis to predict the High & low of stock with some probability on a normal market day(non-volatile market).


Conclusion: 
The analyzer will give insights about the probability distribution of the stock's intraday movement & using these insights one can give decide to select a stock which can give relatively more margin based on OHLC on a intraday trade in a non volatile market
