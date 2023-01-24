# surfs-up
#### Purpose of Analysis
The purpose of this analysis was to use SQLalchemy to grab temperatures in June, and grab the summary statistics of the temperatures in June. We also did the same thing to December temperatures.
#### Results

![](junetemp.png) ![](dectemps.png)
##### Three Key Differences
* The count of temperatures(1700 vs 1517)
* The minimum(64 vs 56)
* The first quartile(73 vs 69)

As we see, we have almost 200 more logged temperatures for June, coming in at a count of 1700 whereas December has 1517 logged temperatures. There really isn't a huge difference in the temperature data for these months. The mean comes in really close with Junes being 74 and Decembers being 71. The biggest difference that I see is their logged minimum temp. The coldest it was in June was 64 degrees while the coldest it was in December was 56. There may be different information if December had as many logged temperatures as June did. The first quartile is 73 for June and 69 for December, which hints that it has been colder in December than it had been in June, but not often enough for it to make a huge difference, as the means are very similar.

#### Summary
![](prep.png)
In order to start off this analysis, we had to make sure SQLalchemy was set up by running the code in the image above.

