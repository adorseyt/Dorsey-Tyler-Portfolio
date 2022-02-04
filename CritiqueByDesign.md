# Assignment 3 & 4: Critique by Design

## Introduction
This exercise follows the critique by design proces, which allows data visualization creators to think about the components of a sucessful design, recieve feedback, and iterate the creation process. In this case, we'll be starting with an existing chart from an outside source. The visualization will be evaluated based on its usefulness, completeness, perceptability, truthfulness, intuitiveness, aesthetics, and engagement. Each componant will be given a score between 0 and 10, with a description of how features impacted each score.

These insights will provide a roadmap for our goals in the redesign. For example, if the original chart feels incomplete what elements should be included to improve it? This will be undertaken in a wireframing exercise, where the designer can brainstorm a number of solutions and reconceptualize the data into the narrative the original author may have intended. Just as the original may benefit from the critique exercise, these prototupes will be subject to peer review - allowing perspectives outside of the author to contribute to the final solution. In the final step, this feedback will be encompassed into a finalized revision of the data visualization. 

## Step 1: Identifying an Existing Data Visualization
For this exercise, I have selected a chart from the <a href="https://www.intracen.org/country/Albania/">International Trade Centre's Country Profile for Albania</a>. The work of ITC was integral to my previous work in understanding Albania's long-term economic strategy, but at the time I had felt the generated visualizations struggled to easily convey information to my end readers. In the end, I opted to describe the takeaways from the data over leveraging the charts themselves. This exercise gave me a wonderful opportunity to ask what I would do with another chance to take this on.

I have chosen to work specifically with ITC's Aid Dependency timeline, which describes how dependent on foreign aid the Albanian economy has been compared to other nations in the region. Here, aid dependency is calculated as how much Official Development Assistance (ODA) the country received as a proportion of their Gross National Income (GNI). 

![Aid Dependency - ITC](https://github.com/adorseyt/Dorsey-Tyler-Portfolio/blob/main/ITC%20Chart%20-%20Albania%20Aid%20Dependency.PNG?raw=true)
<sup>Source: <a href="https://www.intracen.org/country/albania/income/">International Trade Centre</a> - Accessed February 2022</sup>

### Discussion
While the core data for this visualization being readily available from the <a href="https://databank.worldbank.org">World Bank World Development Indicators DataBank</a> allowed a recreation of many elements of the visualization, there are aspects of the chart that can not - or perhaps should not - be reproduced. For example, the original chart correctly includes Greece as a neighbor to Albania, the WDI do not have Greece's data for this series. In the original chart, Greece is listed in the key despite not being present in the timeline. I have decided to omit it completely. Conversely, there is a dotted green line that is unidentified in the key and thus cannot be recreated. It will also be omitted.

In addition, there are a number of categories with ambiguous meanings or incorrect nomenclature. There are two ambiguous regional groupings - "ITC Regional Group Average" and "Neighbour's Average". The ITC considers Albania part of their Eastern Europe and Central Asia region, which emcompasses Albania, Bosnia & Herzgovina, Croatia, North Macedonia, Serbia, Romania, Turkey, Ukraine, Belarus, Kazakhstan, Uzbekistan, Kyrgyzstan, Tajikistan, and the Russian Federation. However, the average data for these nations does not reflect what the original chart outlines. In fear of misrepresenting their intention here, I have decided to omit this grouping. For the Neighbour's Average, I was again unable to recreate the figures presented here, but felt the grouping was useful, so will be presenting it as an average of all nations (excluding Albania) presented in the chart.  What is listed as The Former Yugoslav Republic of Macedonia represents the data of North Macedonia. The WDI has updated their labeling to refer to the nation's 2019 official renaming, but ITC has not. I have opted to use "North Macedonia" to reflect this update.

These data issues will be discussed further in Step 2, but another omission I considered was in the timeline of data presented. This speaks more about the intended narrative that the chart is meant to support, and can be up to interpretation. I believe that ITC's intention is to show the general trajectory of aid dependence for all regions and nations, and such a 2002-2012 10-year period is sufficient. However, I approached this with a focus specifically on Albania, and considered the inclusion of key dates specific to the country and how it would have a more comprehensive narrative. Albania suffered an economic collapse that resulted in a quasi-civil war in 1997. While it may be taking liberties, I also want to explore how this chart can tell that story. What impact did that collapse have on aid and income, and how has Albania's economy reacted compared to other nations who did not have that event? For this reason I will wireframe some ways playing with that idea and not.

## Step 2: Critique
In this step, we're focused on evaluating the data visualization on a number of aspects that can make it successful. The chart will be assigned a score for each aspect category, as well as a description of elements that could have improved the score.

### Usefulness - 6
<i>Is the visualiztion useful to the intended audience? Does it communicate valuable information?</i>

In order to evaluate usefulness, we first have to define the intended audience and surmise their need for this information. I've discussed how this graph didn't meet my original purpose, namely how well Albania has been able to reduce their aid dependency since the civil crisis. However, this hyper-specific study question does not objectively describe the intended audience. Instead, ITC publishes these overviews for development and financial experts to get a quick understanding of a country's economy contextaulized within the region. They are primarily used to inform intended actions and interventions. 

The decision to describe aid dependancy as defined is a great indicator for the intended audiences, especially development interventionists. The information itself is useful and by contextualizing Albania's performance on this metric as relative to its neighbors allows readers to easily understand what baselines can be expected. Seeing that Albania often performs in the middle of the pack here is in itself a useful piece of information.

However, how useful is the chosen x-axis here? The selection of dates shown is not an objective issue with completeness. But when I ask myself "What do I wish I could see?" I can't help but expand the scope beyond the 10 years chosen. In addition to my use as a narrative surrounding the nation's internal context, there's the simple fact that 2012 was a long time ago. WDI's data is available for all of these categories up to 2019; why would even general information-minded readers not want more recent data? For that reason, the scope has impacted the usefulness score. 

### Completeness - 3
<i>Does the visualization have everything necessary to make it understandable?</i>

This visualization suffers primarily in this aspect; there are categories that are not completely defined, inclusions that should be omitted, and exclusions that are essential to the interpretation of the data. 

The most overwhelming issues seem to be in the key. Greece is included in the key despite having no data presented, and there is an undefined dotted green line that cannot be interpreted (or reproduced) with the information provided. My feeling is that these charts are computer generated for each country, which can explain some of these errors. 

The notes below the visualization provide sufficient information to access the base dataset, though it could be improved with a link to either the WDI DataBank with selections chosen or to a table with the same data. This would have greatly facilitated my ability to verify the data. In addition, the note's reference to the ITC regional groupings is not sufficient to understand this category in the key. It took a lot of looking through their site to understand what Region ITC considers Albania in, and even more to understand what nations that region contains. This could be improved with a link to their regional descriptions, or more comprehensively with a full description of the calculation methodology - what countries were included and how was the average calculated? The fact that I cannot recreate this category belies the severity of this issue, but also restricts my ability to provide specific feedback - my suggestions reflect my interpretation of what they were going for, but we can't verify that the interpretation is correct.

However, there are other elements that should be taken into account. The original timeline has an appropriate x-axis label, a y-axis label that is explained in the title, and appropriate grids lines that allow referencing without being overly cluttered. Excluding the issues described above, the key allows users to match lines with their respective countries. At the very least, Albania is identifiable which is the most important category.

### Perceptability - 5
<i>Can the reader understand the information with minimal effort? Is the visualization type appropriate? Does it use logical comparisons?</i>

One of the greatest strengths of this visualization is the use of comparisons. The countries chosen represent a logical regional context by being Albania's immediate neighbors. The outlined audience will appreciate that many nations, such as Serbia, North Macedonia, and Bosnia & Herzegovina have gone through their own recent events that may have impacted their aid dependence. Albania's economic journey could not be fairly compared to the U.S., Russia, Western Europe, or China.  

The visualization type chosen is so appropriate that I anticipate a struggle to come up with a better general design (though I intend to try by refinining the narrative or perhaps streamlining the information). Multiple lines over a timeline is a great way to convey how this metric has changed over time, and how one's journey compares to others'. The chart conveys a strong story - that despite different origins the nations in this region have convereged on similar aid dependencies, and those dependencies are lower than before. 

However, the question of how much effort it takes to understand what's being presented is where the visualization flags in this category. An immediate and simple modification would be bringing Albania to the forefront; the fact that the core country's line is layered below all other lines borders on unacceptable. The use of symbols has also greatly reduced the perceptability due to how much they obstruct many tightly-grouped lines. I can see this as a feature to improve accessibility to colorblind readers and black/white printing which still needs to be addressed, if in another way. One way to make this visualization much more perceptable would be a reduction in color. As the audience, we care most about how Albania is performing, and how that performance relates to its neighbors. We could grey out all the neighbors and highlight on Albania in a darker color. This would give the necessary information, remain colorblindness friendly, and make Albania the star of the visualization.

The y-axis is also a hindrance to percpetability. It has to convey a lot of information and needs the title (located to the side, so a large distance for the eye) to be understood. If the y-axis was more clear, the title could be leveraged to convey a message; what is the takeawy here? What we can eventually see is that Albania is on par with its neighbors in reducing their aid dependency though that may be plateauing or even reversing in the 2010's. Perhaps a double lined y-axis would help? Something like "Aid Dependency: Official Development Assistance received as a percent of Gross National Income". This is going to be an area of particular experimentation in Step 3.

### Truthfulness
<i>Is the visualization accurate, reliable, and valid? Is it representing what it says it is, and in the most complete and truthful manner? Does it misrepresent the data or make comparisons that aren't correct?</i>

The visualization uses data from a properly cited and reliable source - the World Bank is considered a premiere source of this information, and has safeguards to ensure that the metrics are consistent across countries.The labels are exact replicas of how the data is described by the source, making it easy to replcate and compare to other visualizations from the same source. I believe that the data is presented holistically, and while I've noted that the citation could be improved for accessibility, I don't consider it a question of truthfulness. 

However, the extent to which the comparisons were correct wasn't readily apparent until I sought to reproduce the graph. With the exception of the aforementioned ambiguity, the country trajectories appear correct and a labeled correctly. However, when placing the same dataset into my own timeline, I found inconsistencies in the data presentation that can't be easily explained. Serbia is the most identifiable example; in the original visualiztion the country's aid dependence hovers just below 14%, but when plotted independently it's much closer to 12%:


### Intuitiveness
Is it easy to understand and clearly communicates the information? If unfamiliar, does it include easy to understand instrcutions on how to interpret it?

### Aesthetics
Is it interesting or enjoyable to look at? Is it a good example of what a beautiful data visualization might look like? Is it somewhere in the middle - pleasing but otherwise not distracting to look at? 

### Engagement 
Does it lead the audience to learn more about the topic? Does it inspire the audience to talk about the data or share it with others?

## Step 3: Wireframe a Solution

## Step 4: Test the Solution

## Step 5: Build the Solution
