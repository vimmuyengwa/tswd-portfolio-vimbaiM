| [home page](https://vimmuyengwa.github.io/tswd-portfolio-vimbaiM/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# The World Happiness Report  

For my data visualization critique, I chose to analyze the World Happiness Report which collects happiness data for approximately 143 countries in a 3 year period. The report is updated annually. 

## Step one: the visualization

Original data visualization:
<div class='tableauPlaceholder' id='viz1739415136221' style='position: relative; width: 100%; height: 75vh;'>
  <noscript>
    <a href='https://worldhappiness.report/'>
      <img alt='World Happiness Report 2024Figure 2.1: Country Rankings by Life Evaluations in 2021-2023' src='https://public.tableau.com/static/images/20/2024Draft/Figure2_1/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <!-- Tableau Embed via iframe -->
  <iframe src="https://public.tableau.com/views/2024Draft/Figure2_1?:embed=y&:display_count=yes&:showVizHome=no"
          width="100%" height="100%" style="border:none;">
  </iframe>
</div>

Source: World Happiness Organization 

For my data source, I chose to analyze the World Happiness Report. I selected this visualization out of curiosity and intrigue. When I first encountered the chart, I was skeptical about how happiness could be measured, as it can be highly subjective—especially across 143 countries. Much like the rural participants in the Data is Personal study, my perceptions of how much I could trust this data were influenced by the source once I did some digging. In fact, the research was a collaboration between Gallup, the Oxford Wellbeing Research Centre, the UN Sustainable Development Solutions Network, and the editorial board of the World Happiness Report.

This made me reflect on how our interpretation and trust of data are often shaped by our inherent biases, particularly after seeing these exemplified in the rural research study. The article emphasized how people tend to interpret data by looking for connections and patterns that resonate with their own perspectives. This highlighted how the way we process information can be deeply influenced by our individual leanings and preconceived notions 

## Step two: the critique

Considering userfulness, perceptability, truthfulness, intuitiveness, and engagement, here is a summary of my thoughts 

**Usefulness:**
I ranked the chart overall a 7. I think it was clear that this was measuring overall happiness with rankins shown by descending order of countries shown. As someone living in the United states and a native of Zimbabwe, my immediate thought was researching how these two countries ranked 

Overall, Happiness is difficult to measure because it’s highly subjective. This article looks at the overall sociological measure of happiness at the country level. As someone who studied sociology, iam particularly interested in the life evaluations. My question becomes are the factors highlighted such as dystopia and residual, perceptions of corruption, generosity, freedom to make life choices, healthy life expectancy, social support, and gdp per capita really the only factors to measure. From my vantage point I can see how life expectancy, social support, and gdp are more measurable that the other factors called out. 

**Perceptibility:**
The chart is generally understandable, but it starts using 95% CI statistical language that might confuse some readers. As noted in the article by Evan Peck on “Data is Personal”, charts should be accessible to all audiences, regardless of their education level. The use of terms like “life evaluations” could be clearer—replacing it with “contributing factors” might be more intuitive for a reader. Also, dystopia and residual is also hard for me to conceptualize as a reader. 

**Truthfulness:**
The visualization is mostly accurate. The author clarifies that the happiness measure is based on surveys and does not account for other underlying factors. It's important to note that the data covers a 3-year period and is updated annually.

**Intuitiveness:**
The chart communicates the main idea well, but some finer details, like the Confidence Interval, are not intuitive. As Peck points out, chart accessibility should not be limited to highly educated audiences.

**Aesthetics:**
The chart is somewhat simple in its use of horizontal bar. I would not describe it as visually striking. In Crafting for Clarity (Chapter 2), simplicity is emphasized, and I think reducing the number of countries displayed would improve the chart’s clarity. Focusing on the top 8 countries for comparison to the U.S. would make it more relatable and engaging for readers. This aligns with Peck’s recommendation to make charts relevant to the audience.

For my use case I will use the United States, which is ranked 23rd overall for countries. My current working title is "How the United States Compares to the Happiest Countries." This allows for a more focused and relevant comparison. Referencing the “Data is personal” article, Evan Peck suggests, data visualizations should be relevant to the audience, and narrowing the scope to include fewer countries would make the chart more personal and engaging for U.S. readers, helping them better connect with the information (Peck, E).

**Engagement:**
The chart offers insights but could be more engaging if simplified. The factors are clear, but the description and jargon is too long for a chart, and is geared towards a very specific audience. Making it more concise would improve its impact and encourage sharing and discussion.


## Step three: Sketch a solution

<div style="min-height:358px" id="datawrapper-vis-F0Vji"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/F0Vji/embed.js" charset="utf-8" data-target="#datawrapper-vis-F0Vji"></script><noscript><img src="https://datawrapper.dwcdn.net/F0Vji/full.png" alt="" /></noscript></div>

For my first iteration, I focused on creating a simple, streamlined chart for group review, extracting data on happiness and the Index for the top 10 countries along with the United States. Throughout the creation process, I kept the principle of simplicity in mind, aiming to present the information as simple as possible. I wanted to ensure that the chart was easily digestible and didn't overwhelm the viewer as the original chart did. After sharing it with the group, the initial peer reviews indicated that the chart effectively provided a clear and concise summary of the data.


## Step four: Test the solution

Results:  

| Question | Response | Additional Notes |
|----------|----------|------------------|
| **- Can you tell me what you think this is?** | **Peer Cohort Consensus**: This is a horizontal bar chart. | |
| **- Can you describe to me what this is telling you?** |**Peer Cohort Consensus**: This compares happiness in the United States with the world. | |
| **- Is there anything you find surprising or confusing?** | **Student 1:** Score Measurement question: Is the score out of 10? What is the maximum possible score? | Happiness Index Measurement: How is the happiness index measured and calculated? Cantril ladder call-out. Include how many people participated in the survey. |
| **Who do you think is the intended audience for this?** | **General feedback from Peer cohort:** the world, public health professionals, United States. | |
| **Is there anything you would change or do differently?** | **Student 2:** Color Contrast: The white text on light blue is hard to read. Consider adjusting the background or using a darker color for text. | **Student 3:** Highlighting U.S. Ranking: Call attention to the U.S. ranking specifically. |
| | **Student 2: Label Placement**: Move data labels away from the y-axis and place them outside the chart for better readability. Ensure the labels are in black to improve contrast. | |

Synthesis: 

Suggestions for Data Visualization:
Color Contrast: The white text on light blue is hard to read. Consider adjusting the background or using a darker color for text.

Highlighting U.S. Ranking: Call attention to the U.S. ranking specifically.
Label Placement: Move data labels away from the y-axis and place them outside the chart for better readability. Ensure the labels are in black to improve contrast.

**Other observations,**: similar to when I analyzed the data, all students got excited about analyzing their specific home countries. Of the three, there were two countries represented and each was curious to learn how their country stacked up. This proved my original theory that the audience would be interested in the data specific to them or in this case their home country . 

## Step five: build the solution

World Happiness Index Chart: Building a Solution

Given the global nature of the topic, I initially turned to a world map to represent my data. However, I found that the global map didn't effectively highlight the contrasts I wanted to focus on. After receiving feedback from the professor, I agreed that larger countries often dominate the map, which can obscure the underlying ratings and make the differences less clear. For this iteration I used the data of all 143 countries. 

<div style="min-height:367px" id="datawrapper-vis-JKRb5"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/JKRb5/embed.js" charset="utf-8" data-target="#datawrapper-vis-JKRb5"></script><noscript><img src="https://datawrapper.dwcdn.net/JKRb5/full.png" alt="" /></noscript></div>


For my next graph iterations, I decided to not only look at a single dataset but also analyze the World Happiness Index across 5 years. This involved extracting data from 5 different datasets and consolidating it into a file with the current top 10 rankings of 2024 countries. I had to manually review the data using pivot tables, then populate it into a consolidated Excel sheet, before loading it into Datawrapper and Tableau. After this process, I began to experiment with several different methods. I utilized a new tool the professor introduced me to with raw graphs, where I observed a very interesting trend using a time series forecasting graph. This tool was very difficult for me to use and less intuitive. However, I found something even more interesting than just the U.S. dataset: World happiness is decreasing over time for the majority of the top 10 countries, including the U.S.! The only countries that did not show lower happiness than in 2020 were Israel and Iceland. The story I thought I could tell here was how happiness is decreasing over time.

Created with Raw Graphs (Source: World Happiness Report)
![image](https://github.com/user-attachments/assets/cc667c85-3fda-4c4c-88b1-704f92142155)

**Another graph showing decreasing happiness over time for countries in the top 10 along with the United States** (Source: World Happiness Report) 

<div class='tableauPlaceholder' id='viz1739406886521' style='position: relative; width: 100%; height: 75vh;'>
  <noscript>
    <a href='#'>
      <img alt='World Happiness Decline A Look at How The U.S. Stacks Up Against 2024&#39;s Top 10 &quot;Happiest&quot; Countries'
           src='https://public.tableau.com/static/images/Wo/WorldHappinessDecline/Sheet1/1_rss.png' style='border: none' />
    </a>
  </noscript>
  <!-- Tableau Embed via iframe -->
  <iframe src="https://public.tableau.com/views/WorldHappinessDecline/Sheet1?:embed=y&:display_count=yes&:showVizHome=no"
          width="100%" height="100%" style="border:none;">
  </iframe>
</div>

For perspective, I also thought it was important to look at the contributing factors documented that showed life evaluations for happiness. After looking at the dataset, I though the aforementioned factors such as dystopia and residual as well as perceptions of corruption would engender more questions than otherwise. This also proved to be a tedious process because I was hovering over the original data to plot points in my excel beforre finding the offical data reports from World Happiness. 

<div style="min-height:402px" id="datawrapper-vis-rqBsF"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/rqBsF/embed.js" charset="utf-8" data-target="#datawrapper-vis-rqBsF"></script><noscript><img src="https://datawrapper.dwcdn.net/rqBsF/full.png" alt="" /></noscript></div>

Finally, after testing out a number of theories, I decided to go back to my original idea and use the comparison of the United States against the world for Happiness Index. 

In evaluating the feedback from my peers, I incorporated suggestions about the color contrast for the different years, moving away from the original light blue in favor of bolder brown and red gradients. I also highlighted the U.S. ranking in the footnotes, along with an explanation of the ranking as recommended. I made sure the labels were clearly called out for each time period, as suggested, and stayed true to the original visualization to minimize questions from my audience. Based on the reaction to exploring specific countries relevant to my peers, I believed this approach would also engage other U.S.-based viewers. Taking inspiration from the Tableau reference chart "World GDP Through Time," I added my own spin to focus specifically on the United States, creating what I believe to be a more concise chart.

<div style="min-height:380px" id="datawrapper-vis-93uqZ"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/93uqZ/embed.js" charset="utf-8" data-target="#datawrapper-vis-93uqZ"></script><noscript><img src="https://datawrapper.dwcdn.net/93uqZ/full.png" alt="" /></noscript></div>

## References
World Happiness Report. (2024). Happiness of the younger, the older, and those in between. Retrieved February 12, 2025, from https://worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023

VizHealth. (n.d.). VizHealth Wizard. Retrieved February 12, 2025, from http://www.vizhealth.org/wizard/

Berinato, S. (2023). Good charts: The HBR guide to making smarter, more persuasive data visualizations (updated and expanded).

Peck, E. (2019, May 20). Data is personal. What we learned from 42 interviews in rural America. Multiple Views: Visualization Research Explained. https://www.medium.com

Tableau Software, Inc. (2025). Tableau reference - chart overviews [PDF]. Retrieved from https://canvas.cmu.edu/courses/45739/files/12197445?module_item_id=6045478#:~:text=Files-,Tableau%20reference%20%2D%20chart%20overviews.pdf,-Spring%202025

Trina Chi. (n.d.). Chapter 15: Data design builds. In Data design builds. Retrieved January 26, 2025, from https://trinachi.github.io/data-design-builds/ch15.html

Datawrapper. (n.d.). What to consider when choosing colors for data visualization. Datawrapper Academy. Retrieved January 26, 2025, from https://academy.datawrapper.de/article/140-what-to-consider-when-choosing-colors-for-data-visualization


## AI acknowledgements
AI used to generate github code for pictures embedded for World Happiness Decline 

