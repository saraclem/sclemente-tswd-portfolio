| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualization Redesign
Text here...

_For each step below, you should document your progress as you move forward.  In terms of tone, think of the writeup as though you're keeping journal of your step-by-step process.   You should include a any insights you gained from the critique method, and what it led you to think about when considering the redesign.  You should talk about how you moved next to the sketches, and any insights you gleaned from your user feedback.  Document what you changed based on the user feedback in your redesign.  Finally, talk about what your redesigned data visualization shows, why you selected the data visualization you did, and what you attempted to show or do differently._

_You can include screenshots, sketches or other artifacts with your narrative to help tell the story of how you moved through the process.  Again, make sure to avoid including any personally identifying information about your interviewees (don't list full names, etc.).  While this template serves as a guide, make sure to reference the assignment writeup on Canvas for the official guidance.  This template does not include all guidance mentioned on the assignment page._

## Step one: the visualization

The first step in this exercise was to select an existing data visualization for the redesign. I selected a visualization found on [Makeover Monday] (https://makeovermonday.co.uk/)

The visualization I selected is titled: [World Happiness Report 2024 Country Rankings by Life Evaluation in 2021-2023] (https://worldhappiness.report/ed/2024/happiness-of-the-younger-the-older-and-those-in-between/#ranking-of-happiness-2021-2023)

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

#### critique summary
Overall, I thought the visualizations represented useful information and did a good job of visualizing a lot of data in a digestible format. I assume that the charts were tailored for an audience of researchers, scientists, or journalists who may be exploring the World Happiness Report for opportunities to conduct social science research, write articles, or discover insights for more specific audiences. The visualizations seemed to be created as "tools", with a search box and access to a large dataset. 

My main critique is that I struggled to identify insights directly from the chart, and needed to read the article to better understand how the metrics shown were calculated and how data was collected. If I were to redo these visuals, I would consider breaking up the information into more specific insights or stories for the reader. This could improve the intuitiveness, aesthetics, and engagement. Additionally, I would suggest providing more detailed descriptions or titles to differentiate the data sources used for each visualization, especially to avoid confusion for the audience about which data is observed vs. pulled from surveys. 

## Step three: Draft 1 solution 
After my initial critique, I created a draft visualization that could be used as a redesign for the original. 
_Important Note._ I chose to use a subset of the information shown in the original visual. One of my recommendations was to break up the information into separate visuals, each representing a more specific insight for the audience to takeaway. 

<div class='tableauPlaceholder' id='viz1739228877691' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ha&#47;happinessReportRanking&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='happinessReportRanking&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ha&#47;happinessReportRanking&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                

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

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

