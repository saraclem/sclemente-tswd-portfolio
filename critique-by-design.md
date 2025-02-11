| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualization Redesign

I completed this data visualization redesign exercise as part of a course at Carnegie Mellon University. The exercise involved selecting an existing data visualization (using a site called MakeoverMonday.uk), evaluating the efficacy of that visualization, and then completing my own redesign. The sections below outline my progress in each step of the exercise. 

## Step one: the visualization

The first step in this exercise was to select an existing data visualization for the redesign. I selected a visualization found on [Makeover Monday] (https://makeovermonday.co.uk/)

The visualization I selected is titled: [World Happiness Report 2024 Country Rankings by Life Evaluation in 2021-2023] (https://worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023)

I pulled the source data from [here] (https://data.world/vanessasliva/life-expectancy/workspace/file?filename=WorldHappinessIndex2013-2023.csv)

<div class='tableauPlaceholder' id='viz1739227342498' style='position: relative'><noscript><a href='https:&#47;&#47;worldhappiness.report&#47;'><img alt='World Happiness Report 2024Figure 2.1: Country Rankings by Life Evaluations in 2021-2023 _________NotesTabs 1 &amp; 2: The 95% confidence interval is shown in the grey-shaded area at the end of each life evaluation bar.Tab 2: The sub-bars have no impact on the total score reported for each country. Instead, they are a way of explaining the implications of the model estimated in Table 2.1. The few countries that have empty bars do not have sufficient information for the calculation of portions explained by individual factors. These countries still have their overall scores, though, which are based entirely on survey responses, and are independent of our efforts to explore the underlying support factors of happiness. ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2024Draft&#47;Figure2_1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='2024Draft&#47;Figure2_1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;20&#47;2024Draft&#47;Figure2_1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1739227342498');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                   
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Step two: the critique
After selecting a visualization for this exercise, I submitted a critique. I used a critique method called [Stephen Few's Data Visualization Effectiveness Profile](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf). This method considers factors such as Usefullness, Completeness, Perceptibility, Truthfulness, Intuitiveness, Aesthetics, and Engagement. 

#### Critique Summary
Overall, I thought the visualizations represented useful information and did a good job of visualizing a lot of data in a digestible format. I assume that the charts were tailored for an audience of researchers, scientists, or journalists who may be exploring the World Happiness Report for opportunities to conduct social science research, write articles, or discover insights for more specific audiences. The visualizations seemed to be created as "tools", with a search box and access to a large dataset. 

My main critique is that I struggled to identify insights directly from the chart, and needed to read the article to better understand how the metrics shown were calculated and how data was collected. If I were to redo these visuals, I would consider breaking up the information into more specific insights or stories for the reader. This could improve the intuitiveness, aesthetics, and engagement. Additionally, I would suggest providing more detailed descriptions or titles to differentiate the data sources used for each visualization, especially to avoid confusion for the audience about which data is observed vs. pulled from surveys. 

## Step three: Draft 1 solution 
After my initial critique, I created a draft visualization that could be used as a redesign for the original. 
_Important Note._ I chose to use a subset of the information shown in the original visual. One of my recommendations was to break up the information into separate visuals, each representing a more specific insight for the audience to takeaway. 

<div class="tableauPlaceholder" id="viz1739228877691" style="position: relative;">
  <noscript>
    <a href="#">
      <img
        alt="Dashboard 1"
        src="https://public.tableau.com/static/images/ha/happinessReportRanking/Dashboard1/1_rss.png"
        style="border: none;"
      />
    </a>
  </noscript>
  <object class="tableauViz" style="display: none;">
    <param name="host_url" value="https%3A%2F%2Fpublic.tableau.com%2F" />
    <param name="embed_code_version" value="3" />
    <param name="site_root" value="" />
    <param name="name" value="happinessReportRanking/Dashboard1" />
    <param name="tabs" value="no" />
    <param name="toolbar" value="yes" />
    <param name="static_image" value="https://public.tableau.com/static/images/ha/happinessReportRanking/Dashboard1/1.png" />
    <param name="animate_transition" value="yes" />
    <param name="display_static_image" value="yes" />
    <param name="display_spinner" value="yes" />
    <param name="display_overlay" value="yes" />
    <param name="display_count" value="yes" />
    <param name="language" value="en-US" />
    <param name="filter" value="publish=yes" />
  </object>
</div>

<script type="text/javascript">
  var divElement = document.getElementById("viz1739228877691");
  var vizElement = divElement.getElementsByTagName("object")[0];

  if (divElement.offsetWidth > 800) {
    vizElement.style.width = "1000px";
    vizElement.style.height = "827px";
  } else if (divElement.offsetWidth > 500) {
    vizElement.style.width = "1000px";
    vizElement.style.height = "827px";
  } else {
    vizElement.style.width = "100%";
    vizElement.style.height = "727px";
  }

  var scriptElement = document.createElement("script");
  scriptElement.src = "https://public.tableau.com/javascripts/api/viz_v1.js";
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Step four: Test the solution
After creating an initial draft, I shared the visualization with a group of my peers for feedback. Questions asked and responses collected are summarized below. 

#### Questions & Responses:
- Can you tell me what you think this is?
  - 	Change in average happiness index by country, year
- Can you describe to me what this is telling you?
  - Are the countries getting happier?
- Is there anything you find surprising or confusing?
  - Assuming higher index = more happiness
	- Could be EU countries?
- Who do you think is the intended audience for this?
  - Report viewers
  - Maybe used for policy?
- Is there anything you would change or do differently?
  - Highlight a specific country with the biggest change?
  - Have dots for the beginning of the date range and end of date range, or one per year
  - Consider removing the pages / animation. Maybe make the year bigger or more obvious that its moving by year.
  - Adjust the axis so that there isn't a big gap on the left side of the chart
  - Flip the axis so that the tracking isn’t being covered by the country label

#### Reflection & Themes:
I found the feedback session very helpful. The thought process that my peers went through when looking at the visual were similar to mine, but they also shared new ideas and perspectives that hadn't occured to me. My main takeaways from the feedback session were: 
- It's important that the visual is tailored to the audience. If I assume this is a more research or policy-focused audience, then I should focus on statistical significance over aesthetics and engagement for a broader audience.
- The 'pages' and movement were not useful. The intent of this feature was to show more data (years) without overwhelming the visual, but I knew I needed to find a better way to acheive this.
- Better labeling and formatting. There were a few formatting items in the feedback that would be simple but powerful updates. 

## Step five: build the solution
Following the feedback session for my first draft, I completed a second draft of the visualization (included below). In this version, I included all years in the same visual, and chose to represent variation by country using boxplots. My intent is to meet the needs of a research or science-focused audience who may be interested in variation over time amongst these countries, and outliers. I also made a potentially controversial choice to limit the X-axis to an index of 5-9. While this may not be the most appropriate decision, it allowed for a deeper understanding of the variation between countries. If I had more time, I would also move the Y-axis to the right side of the chart to better align the boxplots with their country name labels. I found this version to be pretty interesting - it highlights some potentially unexpected variation in countries such as Finland, Canada, and Norway. It also highlights outlier years which lead to questions about why happiness might have dipped or peaked in a particular year. 

<div class='tableauPlaceholder' id='viz1739286458505' style='position: relative'><noscript><a href='#'><img alt='Dashboard 3 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ha&#47;happinessReportRanking&#47;Dashboard3&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='happinessReportRanking&#47;Dashboard3' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ha&#47;happinessReportRanking&#47;Dashboard3&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1739286458505');                    
  var vizElement = divElement.getElementsByTagName('object')[0];
  
  if ( divElement.offsetWidth > 800 ) { 
    vizElement.style.width='1000px';
    vizElement.style.height='827px';
  } else if ( divElement.offsetWidth > 500 ) {
    vizElement.style.width='1000px';
    vizElement.style.height='827px';
  } else { 
    vizElement.style.width='100%';
    vizElement.style.height='727px';
  }                     
  
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## References
- World Happiness Report: https://worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023
- Makeover Monday: https://makeovermonday.co.uk/
- Source Data Used for Visualizations: https://data.world/vanessasliva/life-expectancy/workspace/file?filename=WorldHappinessIndex2013-2023.csv
- Chris Gorunson (Telling Stories w/Data Course Materials, Spring 2025)
- Good Charts Workbook: Tips, Tools, and Exercises for Making Better Data Visualizations By: Scott Berinato
  
## AI acknowledgements
- I used ChatGPT-o3 to assist with Tableau features and chart design. Link to chat: https://chatgpt.com/share/67ab6d87-2a24-8010-9885-d9f73e12e127
