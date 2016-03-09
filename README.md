# class-ProjectExecutive Summary

This report will be analyzing the rapidly developing Southeast Asian economies, many of these are already ready well established international super powers when it comes to markets. The intent of this research is to explore the less known southeast Asian markets, the economic boom is much more than China and India.

Thailand, Indonesia and Singapore are rapidly developing as well and being overlooked by the international community. These nations have been overshadowed by the enormity of China and India, but a deeper look is well worth it for these smaller nations. Over the past 30 years these nations have managed to lift millions of people out of poverty and raise their GDP per capita by substantial amounts in a relatively short time.
This report will attempt to establish what exactly these nations are exporting to the rest of the world and how much, but also what their countries’ newly formed middleclass or buying from overseas. The main focus will be to show the reader that investments in these are profitable and they ought not be overshadowed by China, India and Hong Kong.

















Indonesia

	As this study will attempt to show, that the nation of Indonesia is not just currently, but have for several years been experiencing strong growth. Economist measure growth with a wide range of variables, to get an understanding of how their economy is running and to check its overall health, these stats are also closely scrutinized for years even decades for accuracy and to track trends. The most valuable statistic at an economist’s disposal is a nation’s GDP per capita, which is an average of what your typical citizen of a country makes.

	The GDP per capita is the Keystone Statistic of where an economy finds itself, where its struggling or if it is picking up. A high GDP means that the people of a nation have more disposable income, and is generally correlated with a higher quality of life. For all practical purposes this study focused on the most important variables of the Indonesian economy to keep it within a manageable scope, and be able to show the current state of their economy.
















class(data)
[1] "data.frame"
> summary(data)
         VAR00001          VAR00002 
 Country Name: 1   Country Code: 1  
 Indonesia   :60   IDN         :60  
                                    
                                    
                                    
                                    
                                    
                                                           VAR00003 
 Adolescent fertility rate (births per 1,000 women ages 15-19) : 1  
 Agriculture, value added (% of GDP)                           : 1  
 Annual freshwater withdrawals, total (% of internal resources): 1  
 Births attended by skilled health staff (% of total)          : 1  
 Cash surplus/deficit (% of GDP)                               : 1  
 CO2 emissions (metric tons per capita)                        : 1  
 (Other)                                                       :55  
              VAR00004               VAR00005     VAR00006         VAR00007 
 AG.LND.FRST.K2   : 1   Scale (Precision): 1   ..     :11   ..         :12  
 AG.SRF.TOTL.K2   : 1   Unit (0.0)       :60   0      : 2   -4550355286: 1  
 BX.KLT.DINV.CD.WD: 1                          41.5   : 2   0.1        : 1  
 BX.TRF.PWKR.CD.DT: 1                          0.1    : 1   0.7        : 1  
 DT.DOD.DECT.CD   : 1                          0.8    : 1   0.9        : 1  
 DT.ODA.ALLD.CD   : 1                          0.9    : 1   1          : 1  
 (Other)          :55                          (Other):43   (Other)    :44  
    VAR00008      VAR00009     VAR00010     VAR00011     VAR00012     VAR00013 
 ..     : 8   ..      : 4   ..     : 4   ..     : 7   ..     : 6   ..     :12  
 -0.6   : 1   -1      : 1   -0.3   : 1   -1.7   : 1   0.4    : 1   0.4    : 1  
 0.2    : 1   -1116994: 1   0.3    : 1   0.3    : 1   0.6    : 1   0.7    : 1  
 0.7    : 1   0.3     : 1   0.6    : 1   0.6    : 1   1      : 1   1      : 1  
 1      : 1   0.8     : 1   1      : 1   1      : 1   1.3    : 1   1.3    : 1  
 1.3    : 1   1       : 1   1.3    : 1   1.3    : 1   1.8    : 1   102.5  : 1  
 (Other):48   (Other) :52   (Other):52   (Other):49   (Other):50   (Other):44  
    VAR00014     VAR00015     VAR00016           VAR00017 
 ..     : 9   ..     :15   ..     :24   ..           :54  
 -700000: 1   5.6    : 2   0.5    : 1   2015 [YR2015]: 1  
 0.4    : 1   0.5    : 1   0.8    : 1   27.2         : 1  
 0.8    : 1   0.9    : 1   1.3    : 1   47.8         : 1  
 1      : 1   1.3    : 1   10190  : 1   60.8         : 1  
 1.3    : 1   11.4   : 1   11.3   : 1   84.4         : 1  
 (Other):47   (Other):40   (Other):32   (Other)      : 2  
> names(data)
 [1] "VAR00001" "VAR00002" "VAR00003" "VAR00004" "VAR00005" "VAR00006"
 [7] "VAR00007" "VAR00008" "VAR00009" "VAR00010" "VAR00011" "VAR00012"
[13] "VAR00013" "VAR00014" "VAR00015" "VAR00016" "VAR00017"
> str(data)
'data.frame':   61 obs. of  17 variables:
 $ VAR00001: Factor w/ 2 levels "Country Name",..: 1 2 2 2 2 2 2 2 2 2 ...
 $ VAR00002: Factor w/ 2 levels "Country Code",..: 1 2 2 2 2 2 2 2 2 2 ...
 $ VAR00003: Factor w/ 61 levels "Adolescent fertility rate (births per 1,000 women ages 15-19)",..: 54 47 46 56 45 49 48 20 18 21 ...
 $ VAR00004: Factor w/ 61 levels "AG.LND.FRST.K2",..: 40 57 56 2 11 50 49 32 34 33 ...
 $ VAR00005: Factor w/ 2 levels "Scale (Precision)",..: 1 2 2 2 2 2 2 2 2 2 ...
 $ VAR00006: Factor w/ 49 levels "..","0","0.1",..: 21 18 10 20 11 1 37 6 39 35 ...
 $ VAR00007: Factor w/ 50 levels "-4550355286",..: 23 24 9 20 15 2 2 7 42 49 ...
 $ VAR00008: Factor w/ 54 levels "-0.6","..","0.2",..: 23 24 6 21 13 19 2 30 17 8 ...
 $ VAR00009: Factor w/ 58 levels "-1","-1116994",..: 25 26 7 23 16 18 3 31 19 9 ...
 $ VAR00010: Factor w/ 58 levels "-0.3","..","0.3",..: 24 26 6 21 14 18 25 34 22 8 ...
 $ VAR00011: Factor w/ 55 levels "-1.7","..","0.3",..: 24 27 6 21 16 17 2 37 26 8 ...
 $ VAR00012: Factor w/ 56 levels "..","0.4","0.6",..: 25 28 5 22 15 13 18 38 29 7 ...
 $ VAR00013: Factor w/ 50 levels "..","0.4","0.7",..: 20 23 5 14 12 9 1 39 25 15 ...
 $ VAR00014: Factor w/ 53 levels "-700000","..",..: 21 24 6 16 13 10 2 43 29 17 ...
 $ VAR00015: Factor w/ 46 levels "..","0.5","0.9",..: 18 22 4 13 9 5 1 44 25 14 ...
 $ VAR00016: Factor w/ 38 levels "..","0.5","0.8",..: 15 19 4 11 9 6 1 38 23 12 ...
 $ VAR00017: Factor w/ 8 levels "..","2015 [YR2015]",..: 2 1 1 1 1 1 1 1 1 1 ...
>


The Data that is being displayed is data that was collected from the “world Bank”, and then processed Through “R” so the data could be cleaned up and further broken down from raw data into useable information. The study took strong indicators such as education, life expectancy, etc., to show the pattern that Indonesia’s economy is improving and becoming much more competitive with the nations surrounding it. 

	The data that was gathered and now being displayed shows that there is a steady increase in life expectancy which is an indispensable variable when accessing the economic development of a nation. For example the first year that is being examined is 1990, it shows that the average life expectancy was 63.3 years. In one decade that number went up to 66.2, and the last Stat has life expectancy at 68.7. Life expectancy is a valuable variable because it tells you so much, from this we can derive that the Indonesian healthcare system is improving, as well as work conditions, and overall quality of life.

	While life expectancy and public healthcare access, education, etc. are important in telling you what is going on with aspects of quality of life. The most indispensable piece of information is a country’s GDP per capita, this is the variable that shows how much of a nations products are wanted all over the world, and what their population can afford to buy. This gets the attention of foreign investors and companies from overseas to begin to build new infrastructure in that nation. The data shows that the country’s GDP has grown at around a 5% level since 1990, that year it had 9% growth. Twenty five years later it grew by exactly 5% which is expected, it is a slowdown but not a contraction of their economy.


Singapore



	The study is meant to show that there is general growth in South Asia, which is why data for Singapore was also pulled. This was done to show that there is a steady and healthy upward trend in all of Asia. Singapore is an outlier because of its geography, it is an archipelago perfectly located with the big traders of the region such as China, Japan, and South Korea this makes it an import and export paradise.  

	The exact same statistics were taken for the Nation of Singapore Health, GDP percentage growth, GDP per capita, etc. the purpose is the same to show that Singapore’s economy is booming and has been in an expansion for some time. Hopefully the info will prove that Singapore is a nation worthy of foreign investment.


> data <- read.csv(file="C:/Users/edeloss3/Documents/Sing.csv",head=TRUE,sep=",")
> class(data)
[1] "data.frame"
> summary(data)
     datada       SGP            SGP.1       SGP.2           SGP.3  
 2012   :2   ..     :1   ..         :1   ..     :1   ..         :1  
        :1   3047100:1   1.297297588:1   11450  :1   1.6393E+11 :1  
 1990   :1   4027900:1   1.62070839 :1   23670  :1   2.54525E+11:1  
 2000   :1   4401400:1   1.732945979:1   32080  :1   2.86279E+11:1  
 2006   :1   4588600:1   1.770661207:1   35660  :1   2.92953E+11:1  
 2007   :1   4839400:1   2.08576428 :1   36680  :1   2.93016E+11:1  
 (Other):6   (Other):7   (Other)    :7   (Other):7   (Other)    :7  
     SGP.4           SGP.5            SGP.6  
 ..     :1   ..         :1   -0.603388298:1  
 21960  :1   1.47797E+11:1   ..          :1  
 40700  :1   1.79981E+11:1   1.787620228 :1  
 57830  :1   1.92226E+11:1   10.04421048 :1  
 58750  :1   1.92408E+11:1   15.24037704 :1  
 60530  :1   2.36422E+11:1   2.918389477 :1  
 (Other):7   (Other)    :7   (Other)     :7  
> data[1:13]
Error in `[.data.frame`(data, 1:13) : undefined columns selected
> data[1:13,]
   datada               SGP                        SGP.1
1   years Population, total Population growth (annual %)
2    1990           3047100                  3.888077553
3    2000           4027900                  1.732945979
4    2006           4401400                  3.129293551
5    2007           4588600                  4.165229452
6    2008           4839400                  5.321577945
7    2009           4987600                  3.016408604
8    2010           5076700                  1.770661207
9    2011           5183700                   2.08576428
10   2012           5312400                  2.452462354
11   2012           5399200                   1.62070839
12   2013           5469700                  1.297297588
13                       ..                           ..
                           SGP.2       SGP.3               SGP.4
1  GNI per capita, (current US$)   GNI, PPP  GNI per capita, PPP
2                          11450 66904580333               21960
3                          23670  1.6393E+11               40700
4                          32080 2.54525E+11               57830
5                          35660 2.86279E+11               62390
6                          36680 2.92953E+11               60530
7                          37080 2.93016E+11               58750
8                          44790 3.56367E+11               70200
9                          48330 3.79651E+11               73240
10                         51390 3.97064E+11               74740
11                         54580 4.20253E+11               77840
12                         55150 4.39044E+11               80270
13                            ..          ..                  ..
                                SGP.5                 SGP.6
1  GDP at market prices (current US$) GDP growth (annual %)
2                         36152800270           10.04421048
3                         95833932715           8.897544418
4                         1.47797E+11           8.860196114
5                         1.79981E+11           9.111527148
6                         1.92226E+11           1.787620228
7                         1.92408E+11          -0.603388298
8                         2.36422E+11           15.24037704
9                         2.75365E+11           6.207448728
10                        2.89936E+11           3.414361301
11                        3.02246E+11           4.443213647
12                         3.0786E+11           2.918389477
13                                 ..                    ..
> names(data)
[1] "datada" "SGP"    "SGP.1"  "SGP.2"  "SGP.3"  "SGP.4"  "SGP.5"  "SGP.6"


		The picture that the information form R programing is painting is one very similar to the one it painted for Indonesia, all the variables are positively correlated and seemingly increasing year by year. The nation of Singapore has a very high current GDP per capita its last year recorded was at $55,150, making it one of the highest in the world; in 1990 it was barely $10,000. The statistics take wide leaps over the decades on every level, with the exception of population growth, which decreased from around 3.5 million to 1.8. That is actually a good thing amount developing economies, it a sign the middle class is growing and quality of life is improving. Through and through both Indonesia and Singapore are growing at healthy rate or surpassing that rate at almost all levels, the conclusion from this study is that both of these nation’s economies will continue to expand for the foreseeable future and shouldn’t be overshadowed by China.

