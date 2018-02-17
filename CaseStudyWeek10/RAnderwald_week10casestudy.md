# Chulwalar Case Study
Scott Anderwald  
July 21, 2016  




####Purpose of the Study
For many countries, the export of products accounts for a large segment of the income for not only the government but the local workforce. This income not only contributes to the tax base but it also helps the local workforce to afford a higher standard of living. When a country is able to export products, it's income base increases.  Chulwalar is not exception, with it's collection of agricultural products available for export, it has the ability to improve the lives of it's citizens. To better understand the future potential, the Prime Minister of Chulwalar asked for a study to be conducted so future exports can be planned.  While many products are currently exported from Chulwalar, only one was examined for the case study.  The Red Etel flower was selected for this forecast analysis.  Along with the export data for the product, several types of demographic data was supplied as well.  This data will hopefully give a better picture of the furture export potential.

 
  












####Demographic Information
Chulwalar is part of the island group Urbano in the northern hemisphere.  Many different varieties of agricultural products are exported from the island of Chulwalar. These products include the leafy white bush with white flowers called the Efak, a grass like plant with tiny pink flowers called the Wuge, and the flowering tree which either displays red or blue flowers called the Etel.  While Chulwalar exports many different agriculture products, this study concentrated on the Red Etel tree.    Like many cultures around the world, many festivities are celebrated on the island of Chulwalar.  The celebration of Independence is on the 1st of December where it is customary for participants to give gifts to both family and friends.  Another famous time of year is the March Equinox celebration which is considered the time of rebirth.

####Data Preparation and Analysis
Many steps are involved in the data preparation. The first step is the data gathering; for this the country of Chulwalar was gracious enough to be the source of the data.  Like many data sets the first and largest segment of time is involved with data cleanup.  Before the analysis can begin, data needs to be in the proper format to aid in the analysis.  Only after cleanup and formatting can the data analysis begin.  The first look at the data gives the researcher the ability to quickly understand what the data is telling them.  For this data, which is by it's nature a time series, the use of a decomposition method known as a STL which is an acronym for "seasonal and trend decomposition".  This decomposition is used to study time series data.  After the "seasonal and trend decompositioin" method is used, demographic data provided by the government was analyzed to better determine if any correlations were effecting the export potential. This correlation number allows the researcher the ability to understand how closely related two variables are to each other.  When comparing correlation numbers, the higher the number the better the correlation.  After examining the data it appears that there is a seasonal influence  to the data.  This influence can be better modeled with the Holt's Winter seasonal method.  

####First Look at the Data
Similar to many other agricultural products, it appears production of the Red Etel has a seasonal component.  After running the STL function, the data displays fluctuations typically seen in seasonal data.  This can be seen in the second pane in graph number 1. In both graphs 1 and 2, there appears to be stagnation in the export of Red Etel flowers.  It should be noted that the stagnation appears both in the trend line and the export.  Further investigation will be needed to truly understand the reason behind the stagnation of Red Etel flower exports.


![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-8-1.png)<!-- -->


![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-9-1.png)<!-- -->

In the graph number 3, one can see the seasonal effects on the exports for the Red Etel flower.  As mentioned in the demographic background Chulwalar has two major holidays celebrated on the island.  The first is the March Equinox and the Independence Celebration which is observed on the first of December.  Along with these two celebrations, one can notice a drop in exports during the season with the higher temperatures.  


![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-10-1.png)<!-- -->



####Data Provided from the Chulwalar Government
Many factors contribute to the economic situation of any given country.  Chulwalar, like many countries concerned with their economic growth, collects data to keep track of export potentials.  The government of Chulwalar provided the group with varied amounts of internal and external economic data.  Correlations were made between overall exports and the Red Etel flower. Not all factors will effect the export potential of any given product.  For example a correleation was made between the birth rate of the country and the export of the Red Etel flower. While it might seem that there should be a correlation (since it is assumed both males and females provide the work force for product exporation), the correlation was relatively small, around -.12.  It is not very significant relative to other factors. Temperature of the island seemed to have the biggest impact on the export of the Red Etel flower. It was noted in graph 2, there appears to be a stagnation of export of the Red Etel flower during the period of 2011 to 2013. Looking at the government provided data, it appears that for that period the inflation rate was increasing.  For the 2008 year inflation rate was at approximately 3% while the export was at the lowest amount for the period.  Further investigation into potential external causes in the stagnation of exports need to be conducted.  Graphs from the government provided data will show the correlation in what appears to be affecting the Red Etel flower exports. Complete data sets can be provided on request.







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-12-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-15-1.png)<!-- -->





![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-18-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-21-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-24-1.png)<!-- -->





![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-27-1.png)<!-- -->







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-30-1.png)<!-- -->







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-33-1.png)<!-- -->







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-36-1.png)<!-- -->







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-39-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-42-1.png)<!-- -->







![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-45-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-48-1.png)<!-- -->








![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-51-1.png)<!-- -->






![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-54-1.png)<!-- -->








Data for the study can be used to look forward in time to better understand the Red Etel flower export potential. This potential can be modeled utilizing various models available to the researcher.  One needs to understand that many factors can affect the model and it's ouptut.  These models have both advantages and disadvantages in using them. Depending on the variables, selection of the model will need to be both simple and robust enough to properly analyze the data. For this analysis the Holt's Winter multiplicative forecast model was selected.  The selection of the this particular model was due in large part to the seasonal component of the data.  The Holt's Winter model analyzes both seasonality and seasonal variation seen in the data.  When making the decision on the model the ACC/ACCc and BIC values need to be low as possible.  
   






















 




```r
Model_hw_2 <- hw(RedEtelAsIs ,seasonal="multiplicative",h=12)
summary(Model_hw_2)
```

```
## 
## Forecast method: Holt-Winters' multiplicative method
## 
## Model Information:
## Holt-Winters' multiplicative method 
## 
## Call:
##  hw(y = RedEtelAsIs, h = 12, seasonal = "multiplicative") 
## 
##   Smoothing parameters:
##     alpha = 0.0917 
##     beta  = 0.023 
##     gamma = 1e-04 
## 
##   Initial states:
##     l = 879689.968 
##     b = 12472.9814 
##     s=1.1446 1.3097 1.271 1.6657 0.6903 0.5471
##            0.6126 0.7128 0.7822 1.0347 1.0913 1.1379
## 
##   sigma:  0.1409
## 
##      AIC     AICc      BIC 
## 2060.011 2071.345 2098.715 
## 
## Error measures:
##                     ME     RMSE      MAE       MPE     MAPE      MASE
## Training set -495.4941 142687.3 115050.2 -2.042696 11.56463 0.6116582
##                    ACF1
## Training set -0.1923664
## 
## Forecasts:
##          Point Forecast     Lo 80   Hi 80     Lo 95   Hi 95
## Jan 2014      1705091.2 1397204.1 2012978 1234218.6 2175964
## Feb 2014      1647487.9 1348043.8 1946932 1189527.7 2105448
## Mar 2014      1573557.9 1284916.0 1862200 1132118.1 2014998
## Apr 2014      1198289.9  975819.2 1420761  858050.3 1538530
## May 2014      1100027.3  892690.6 1307364  782933.2 1417121
## Jun 2014       952217.4  769436.2 1134998  672677.8 1231757
## Jul 2014       856616.9  688637.5 1024596  599714.5 1113519
## Aug 2014      1088511.8  869796.2 1307227  754015.2 1423008
## Sep 2014      2645161.1 2099030.4 3191292 1809926.2 3480396
## Oct 2014      2032634.9 1600306.6 2464963 1371445.8 2693824
## Nov 2014      2109088.5 1645914.3 2572263 1400724.7 2817452
## Dec 2014      1856142.4 1434441.5 2277843 1211206.5 2501078
```

```r
plot(Model_hw_2)
```

![](RAnderwald_week10casestudy_files/figure-html/unnamed-chunk-68-1.png)<!-- -->




####Outlook for 2014
As with any agricultural products there appears to some seasonality of the exports. We are 95% confident that the exports expected for the Red Etel could continue to be in a situation of a growth plateau.



```
##            Jan       Feb       Mar       Apr       May       Jun       Jul
## 2014 1705091.2 1647487.9 1573557.9 1198289.9 1100027.3  952217.4  856616.9
##            Aug       Sep       Oct       Nov       Dec
## 2014 1088511.8 2645161.1 2032634.9 2109088.5 1856142.4
```
####Conclusion
The country of Chulwalar has many different products available for export.  This ability to export will allow for the both the government and personal citizen to prosper and to improve the life of it's citizens.  After evaluating data provided by the government of Chulwalar, it appears that the export for the Red Etel flower potenially be plateaued.  While the overall exports appear to be increasing for Chulwalar, export of the Red Etel product could potentially have little increase on the revenue for the country. This analysis does not take into account any other economic factors internally or externally affecting the growth and export of any of Chulwalar products.

















