# Bay-Area-air-pollution-anaysis-after-camp-file
This project is for _**CEE263D: Air Pollution and Global Warming: HIstory, Science, and Solutions**_.

In this paper, we studied Bay Area air quality in the 3 weeks after the Camp Fire in November 2018. We discussed our data set from BAAQMD and methods in crawling, analyzing and modeling the data. Moreover, we presented our results and compared air quality in San Francisco and Redwood City. Specifically, our findings are:
+ PM<sub>2.5</sub> concentrations at both locations increased by 10-fold during the pollution. Air pollution in San Francisco is little worse than Redwood City.
+ Calculations by two methods PSSA and Photostationary State Relation equation produce very close results on rate of reaction for photolysis of NO<sub>2</sub> (this rate is denoted by k<sub>1</sub> throughout the paper). San Francisco and Redwood City witnessed very similar trends in the study period for k<sub>1</sub> values.
+ A closer look at k<sub>1</sub> values of the week 19<sup>th</sup> to 26<sup>th</sup> revealed an interesting case where O<sub>3</sub> concentration remained high and NO and NO<sub>2</sub> stayed low overnight in San Francisco. A hypothesis was suggested that some other sources beyond the scope of this paper might have played an important role in the accumulation of O<sub>3</sub> concentration. Also, the favorable condition introduced by the rainy weather of the week could have contributed.
+ A negative linear relationship was found between logarithm of daily maximum k<sub>1</sub> values and logarithm of daily maximum PM<sub>2.5</sub> concentrations at both locations. Confidence for both fittings are high and the coefficients were close. We used daily maximum to avoid noise in per hour data.

| ![SF-fit](figure/sf-fit.png "SF linear")|
|:--:| 
| *Linear fit between log PM<sub>2.5</sub> and log k<sub>1</sub> in San Francisco* |

| ![RW-fit](figure/redwood-fit.png "RW linear")|
|:--:| 
| *Linear fit between log PM<sub>2.5</sub> and log k<sub>1</sub> in Redwood City* 
