# VBA of Wall Street

## Overview of Project

### Purpose

The purpose of this project was to help us learn VBA by doing an exercise analyzing stocks. First, we analyzed the performance of just one stock that our friend Steve’s parents were thinking about investing in. 
When it appeared that the performance of that stock was not great, we analyzed the performance of other stocks in the same time period to see if there was one that would be better to invest in.
Finally, we refactored our code to make it more efficient, and easier to apply to larger data sets if needed.

### Background

## Results

After running the code on the 2017 and 2018 datasets, it is clear that the stocks we’re looking at performed far better in 2017 than they did in 2018. In 2017, 11 of the 12 stocks analyzed had a positive return. Returns ranged from almost 200% (DQ) to 9%. In the image below, you can see the returns for all the stocks in 2017.

![2017](https://user-images.githubusercontent.com/74469315/101990544-6fd4f680-3c75-11eb-8464-83c38036e4d3.PNG)

On the other hand, the stocks did not perform as well in 2018. Only two of the stocks had positive returns in 2018, and the rest were negative. In the image below, you can see the returns for all the stocks in 2018.

In terms of execution times, it takes the refactored code a much shorter time to run. The original code takes over half a second to run for both 2017 and 2018, where the refactored code takes approx. 0.07 seconds for 2017 and 0.09 seconds for 2018. While it may seem silly to want to make your code more efficient by less than half a second, it can prove useful when working with larger and larger data sets. For a data set with thousands of entries, it will prove useful to be able to write code that runs faster and saves time when analyzing.
 
## Summary

In general, refactoring code helps make it more efficient. It will take less time, less steps or use less memory, which is a good thing. However, it can also take the time and effort of the coder to go through and refactor, which ultimately costs the company money. 

The original VBA script is effective because it came about fairly naturally, and follows our thought process as we worked through the questions asked of us by Steve and his parents. A disadvantage of the original VBA script is that is fairly lengthy and broken out into a number of different macros. The refactored script runs much faster, and is also easy to follow the thoughts process for. It will work more effectively on larger data sets. It was worth refactoring this code, as it did not take a huge amount of time and resulted in a significantly more efficient code.
