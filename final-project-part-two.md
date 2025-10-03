| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Wireframes / storyboards

(shorthand sketch)[https://preview.shorthand.com/K31qOA9hxgt8khpl]

| Story Section           | Description                                                                                 | Wireframe / Visualization |
|-------------------------|---------------------------------------------------------------------------------------------|---------------------------|
| **Introduction**        | Brief overview of Pittsburgh crime data, key attributes, and project goal: identify trends by time, location, and offense type. | Sketch of dashboard layout with main title, dataset summary, and catalog to different sections |
| **Overall Crime Trends**      | Examining the monthly crime data from 2024 to 2025, we notice some fluctuations throughout the year. Interestingly, there is a consistent peak every July. This pattern serves as a clear reminder to exercise extra caution during this month. For instance, tourists planning to visit Pittsburgh might consider avoiding July or taking additional safety precautions during that period. Understanding these seasonal trends can help both residents and visitors stay more aware of potential risks.  | Line chart sketch with months on x-axis, crime count on y-axis |
| **Crime by Hour of the Day**       | One surprising insight from the hourly distribution is that crimes occur relatively infrequently between 4 AM and 5 AM. In contrast, there is a noticeable increase in incidents between 4 PM and 5 PM. This pattern indicates that daylight does not necessarily guarantee safety. People should remain vigilant even during the afternoon hours, as criminal activity can still be significant during times when we usually feel safe. | Bar chart sketch with x-axis as hours (0–23), y-axis as number of crime incidents |
| **Crime Distribution by Neighborhoods**   | Spatial analysis reveals that Downtown Pittsburgh experiences the highest concentration of crime incidents. This insight can be particularly valuable for newcomers or students relocating to the city. For example, students planning to attend local universities may want to consider neighborhoods with lower crime rates when choosing rental housing. By being aware of neighborhood-level differences, residents can make safer decisions regarding where to live and spend time. | Treemap sketch; each rectangle represents a neighborhood, size corresponds to number of incidents |
| **Crime by Type** | Analyzing crime by category shows that the majority of incidents are property-related, such as theft and burglary. This highlights the importance of taking preventive measures to protect personal and residential property. Examples of precautionary actions include installing security cameras, using quality locks, avoiding leaving valuables in vehicles, and staying alert to suspicious activity in the surroundings. Understanding the type of crime most likely to occur allows residents to focus their safety efforts effectively. | Pie chart or stacked bar chart sketch with labels for Person, Property, Society crimes |
| **Conclusion / Implications** | Summarize key insights for policymakers and communities. Suggest next steps or interventions. | Text block with key findings and recommended actions |

<div class='tableauPlaceholder' id='viz1759451992823' style='position: relative'><noscript><a href='#'><img alt='Monthly Crime Trends in Pittsburgh (2024 – Aug 2025)  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_mothlytrend&#47;monthlytrend&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='final_mothlytrend&#47;monthlytrend' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_mothlytrend&#47;monthlytrend&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1759451992823');
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>



<div class='tableauPlaceholder' id='viz1759452010861' style='position: relative'><noscript><a href='#'><img alt='Hourly Crime Distribution in Pittsburgh (2024–Aug 2025)  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_hourly&#47;Sheet6&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='final_hourly&#47;Sheet6' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_hourly&#47;Sheet6&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /></object></div> 
<script type='text/javascript'>  
  var divElement = document.getElementById('viz1759452010861');
  var vizElement = divElement.getElementsByTagName('object')[0];  
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';  
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>


<div class='tableauPlaceholder' id='viz1759453497762' style='position: relative'><noscript><a href='#'><img alt='Crime Distribution by Neighborhood in Pittsburgh (2024 – Aug 2025) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_heighborhood&#47;Sheet7&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='final_heighborhood&#47;Sheet7' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_heighborhood&#47;Sheet7&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div> 
<script type='text/javascript'> 
  var divElement = document.getElementById('viz1759453497762'); 
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px'; 
  var scriptElement = document.createElement('script'); 
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js'; 
  vizElement.parentNode.insertBefore(scriptElement, vizElement); 
</script>


<div class='tableauPlaceholder' id='viz1759453837349' style='position: relative'><noscript><a href='#'><img alt='Crime Type Distribution in Pittsburgh (2024 – Aug 2025)  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_type&#47;type&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='final_type&#47;type' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;final_type&#47;type&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-CN' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1759453837349');
  var vizElement = divElement.getElementsByTagName('object')[0]; 
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


I have already set Tableau’s language to English, but some elements are still displaying in Chinese. I haven’t been able to fully resolve this issue yet, and I will continue trying to fix it. If it cannot be resolved, I may switch to using Python to generate the visualizations instead.

# User research 

## Target audience
Residents of Pittsburgh.
Prospective newcomers to Pittsburgh, such as students preparing to attend local universities and looking for housing.
Audience does not need prior data expertise—visualizations should be easily understandable to a general public reader.
  
## Interview script
The purpose of this user research is to evaluate the clarity, understandability, and engagement of the crime data storyboard and its visualizations. I want to ensure the visuals are meaningful for target audience who care about public safety and neighborhood information.

| Goal | Questions to Ask |
|------|------------------|
|  Understand overall story clarity  |   Do you understand the overall story of crime trends from the visuals?  |
|   Evaluate hourly distribution visualizations   |   The 24-hour bar chart shows crime frequency by hour. Is this easy to interpret? Do you notice clear “risk windows”?             |
|  Evaluate neighborhood distribution visualizations    |      The Treemap shows crimes by neighborhood. Do the sizes and percentages make sense to you?            |
|   Whether audience will be uncomfortable with some  small area in treemap that can not show neighborhoods name and incidents count   |    Is it easy to compare neighborhoods, or do you feel some names/numbers are hard to read?    |
|   Evaluate crime type distribution visualizations   |     Looking at the pie chart of Person/Property/Society crimes, does it clearly communicate proportions? |
|   Use percentages or counts in pie chart  |   Which format do you prefer percentages, counts, or both?  |



## Interview findings

| Questions | Interview 1 (TSBD classmate) | Interview 2 (Graduate student(python classmate)) | Interview 3 (Graduate student, BIDA) |
|-----------|---------------------------------------------|---------------------------------------|---------------------------------------------|
| Overall story clarity | “Yes, I can follow the story from time → location → type. It feels like a clear narrative.” | “The order makes sense, but I’d like more context about whether crime is going up or down.” | “Very logical flow, but maybe add short captions explaining why each chart matters.” |
| 24-hour bar chart | “Easy to see crime peaks. It’s helpful.” | “Yes, but I wonder if weekends look different—can we compare weekdays vs weekends?” | “Clear, but labels could be larger to highlight peak hours.” |
| Treemap clarity | “The big neighborhoods are clear, but small ones are hard to notice.” | “Yes, the incidents counts help, but I don’t know all the neighborhood names—maybe group them?” | “Treemap works, but tooltips or filters would make it better.” |
| Treemap readability (small blocks) | “Hard to read tiny blocks, I just ignored them.” | “Yes, some areas disappear—it feels like lost info.” | “As a data person, I zoom in mentally, but normal users will find it messy.” |
| Pie chart clarity | “Easy to understand three crime types.” | “Yes, but maybe colors could be stronger for contrast.” | “It works, but add both counts + percentages.” |
| Label format (counts vs %) | “Prefer both, so I know the actual numbers and share.” | “Percentages are enough for me.” | “Both, especially for context.” |


# Identified changes for Part III


| Research Synthesis | Anticipated Changes |
|--------------------|----------------------|
| Story flow is understandable but could be more explanatory | Add short captions or annotations under each visualization to highlight key takeaways. |
| Audience wants weekday vs weekend view | Add a filter or comparison chart to separate weekday vs weekend crime patterns. |
| Treemap small blocks are unreadable | Group smaller neighborhoods into broader regions or enable tooltips. |
| Some participants unfamiliar with neighborhood names | Provide map-based context  or a legend showing grouped neighborhoods. |

## References
- [City of Pittsburgh. *Police Incident Data*. Western Pennsylvania Regional Data Center (WPRDC)](https://data.wprdc.org/organization/city-of-pittsburgh) (Accessed September 2025)  
- [City of Pittsburgh. *Monthly Criminal Activity Dashboard*](https://app.powerbigov.us/view?r=eyJrIjoiM2FiNWUxMDUtY2MyMS00NWY2LTllZDEtZWY2OWM0NWM2ZWIyIiwidCI6ImY1ZjQ3OTE3LWM5MDQtNDM2OC05MTIwLWQzMjdjZjE3NTU5MSJ9) (Accessed September 2025)  
- [Federal Bureau of Investigation. *National Incident-Based Reporting System (NIBRS)*](https://www.fbi.gov/how-we-can-help-you/more-fbi-services-and-information/ucr/nibrs)  

## AI acknowledgements
In the process of completing this assignment, I used AI tools as a support resource to improve clarity and efficiency. Specifically, AI was used to:
1. Help with grammar refinement and wording when drafting project descriptions in English
2. Offer formatting guidance for technical documentation


