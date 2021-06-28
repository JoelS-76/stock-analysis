# stock-analysis
Help Steve diversify his parents' stocks in green energy

## background

Steve needs to gather information about Daqo New Energy (DQ) to help his parents make a smart investment. He also wants to diversify their portfolio. So we will analyze the performance of DQ stock in particular, and of other green stocks as well, to give Steve useful information to advise his parents.

# Analysis

We began by isolating the DQ ticker for 2018. We found that DQ had a return of -62%, making it appear to be an unattractive investment. 
![image](https://user-images.githubusercontent.com/84299125/123584776-2fffd780-d79f-11eb-8b43-debbddf3bf2b.png)

But Steve's parents are passionate about green energy, so we looked at data for 11 other stocks as well. For 2018, only two (ENPH) and (RUN) showed positive returns. Things were more favorable across the board in 2017, with only one stock showing a negative return and DQ leading the pack at nearly 200%. 
![image](https://user-images.githubusercontent.com/84299125/123584856-56257780-d79f-11eb-931e-47a72df6cb67.png)

My recommendation from this analysis would be that instead of investing all of their money in DQ, Steve's parents should at least buy some stock in (ENPH) and (SEDG), the only two stocks with positive returns in both years. They also have much higher volume; generally speaking they seem to be the most consistently high-performing stocks in this analysis.

The DQ Analysis yielded at least one block of code which we used multiple times in this project, The RowCount. RowCount = Cells(Rows.Count, "A").End(xlUp).Row. I'll remember that one.

# pros and cons of refactoring in general

Refactoring is a time consuming process. Clearly it does save time in running the code, but it is only worthwhile if you are working with extremely large datasets. If we were analyzing the entire stock market, I imagine it would save a significant amount of time.

# pros and cons of refactoring this particular code
However, 12 stocks is a tiny fraction of the stock market. I spent several hours over the course of 2 days working on this, and I gained a little less than half a second (See Resources). So this isn't going to be very worthwhile unless we are analyzing massive amounts of data. The time gained by refactoring would increase exponentially with the size of the dataset.
