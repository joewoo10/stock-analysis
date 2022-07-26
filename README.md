# All Stocks Analysis Refactored
## Overview
### Project Background 
My friend, Steve, has been tasked by his parents with locating a sound investment for them in a green energy stock. His parents are very interested in DAQ0 New Energy Corp (DQ), however Steve asked for my help to analyze several other green energy stocks in addition to DQ. After I wrote a script in VBA to compare DQ with eleven other green energy stocks, Steve was quite pleased with the ease and efficiency of being able to compare these stocks with just the touch of a button. In fact, he is now interested in going beyond just these twelve stocks using the same tools of comparison.
### Purpose
Since the focus moved to comparing a greater number of stocks, I needed to concentrate on increasing the efficiency of the script I’d previously written, so the run time does not become too cumbersome. In fact, my goal here was to *reduce* the time it takes for the stock comparison to run. 
### Results
#### 2017 vs. 2018 Stock Performance
There is considerable disparity when looking at the performance for the twelve stocks from 2017 to 2018 (See *Resources* file, 2017 and 2018 Stock Returns). First, the 2017 returns, with the exception of TERP, all had positive returns. In fact, half showed gains of 50% or higher. By contrast, the 2018 returns were quite the opposite (minus ENPH and RUN, which showed returns of 81.9% and 84.0%, respectively). Half of the stocks returned double digit losses. ENPH appears to be the only stock that showed a strong return in both 2017 and 2018. Steve’s parents may want to take a closer look at this stock. At the same time, this sector displays intense volatility and may be something for Steve’s parents to question if they are comfortable investing in this sector or perhaps look elsewhere. 
#### Execution time
Looking at the timer comparisons (See *Resources* file, Original Script Run and VBA Challenge images), the refactored code did improve the run time of each script by just over 80%. The 2017 run time was reduced from 0.7109375 seconds to 0.1367188 seconds (81%) and the 2018 comparison was reduced from 0.7109375 seconds to 0.1289063 seconds (82%).
### Summary
The most obvious advantage of refactoring code is that you can make it run more efficiently and cut down on the time it takes to analyze large amounts of data. In this case, the script run time was reduced by about 80%.
I discovered the disadvantage of refactoring code is that the script may not run after making adjustments. I had to save a copy of my original code and repeatedly refer to it as a checkpoint where I *knew* I had something that worked. All things considered, the refactored code was worth a little extra work.
