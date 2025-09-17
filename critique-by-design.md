| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The cheapest countries to study in Europe

In this critique, I apply principles from Good Charts and Stephen Few’s [Data Visualization Effectiveness Profile](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) to evaluate and redesign a visualization from the article “The Cheapest Countries to Study in Europe.” The original chart—a shaded map of Europe showing total yearly study costs—provides a clear geographic frame but leaves gaps in precision, completeness, and audience alignment. To strengthen the critique, I also incorporate feedback from audience interviews, which reveal how real users interpret, struggle with, or disengage from the design. By combining theoretical frameworks with external perspectives, I will break down the visualization step by step, highlighting design trade-offs, contextual limitations, and opportunities for improvement. My goal is to demonstrate how thoughtful redesign choices, informed by both expert guidance and user feedback, can transform the chart into a more accurate, engaging, and decision-oriented tool for students evaluating study-abroad options.

## Step one: the visualization

<img src="Critic - Data Viz _Original.png" width="1000"/>

I selected this particular data visualization from the article “The Cheapest Countries to Study in Europe” because study-abroad costs are a pressing concern for many international students, and the visualization attempts to summarize complex financial data in a way that is approachable for a general audience. Its accessibility and practical focus make it an ideal case for critique, as the stakes are high—misleading or incomplete representations could directly influence how students perceive affordability across different countries. As someone currently studying in the United States, where both tuition and living expenses are notably high, I am also curious to see how the costs of studying in Europe compare. This personal perspective makes the visualization especially relevant and engaging to analyze.

**Citation**: Boyle, Matthew, and Sophie Barber. “The Cheapest Countries to Study in Europe.” Finder UK. Updated July 11, 2024. Accessed September 17, 2025. [https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe](https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe)


## Step two: the critique

**1. First Impressions & Design Strengths**
- The visualization uses a map of Europe with a gradient legend to show total yearly study costs.
- The geographic framing is intuitive—audiences immediately connect the shading to cost differences across countries.
- The title is clear and aligned with the data, making the visualization accessible and easy to read.

**2. Simplicity and Engagement**

The color gradient (darkest blue = highest cost, lightest = lowest) keeps the design simple and easy to interpret. However, this simplicity also creates drawbacks:
- It is difficult to compare countries precisely or rank them by cost.
- Once the cheapest and most expensive countries are identified, there is little incentive to keep exploring, since the audience must spend extra effort comparing gradients.
In addition, when non-EU audiences try to focus on comparing numbers, the map slows them down because they first have to identify each country by location. This added barrier makes it harder to quickly find the cost information they care about and may reduce their overall interest in engaging with the visualization.
As a result, engagement drops quickly after the initial glance. This limitation is compounded by the lack of supporting context. Providing more information and a persuasive framing could make the visualization not only more engaging but also more accurate and truthful for audiences interpreting the data.

**3. Completeness & Data Breakdown**
The map shows only the total yearly cost of studying in European countries. The article explains that this cost is the sum of yearly living expenses and average yearly tuition fees, but this breakdown is missing from the visualization.
This distinction is important, as students may weigh tuition and living costs differently depending on their priorities. For example, a student might prefer lower tuition but allocate more of their budget to higher-quality housing. Without showing these details, the visualization oversimplifies the decision and reduces its usefulness and accuracy.

**4. Audience & Context**
At first glance, the visualization seems to target all students considering studying abroad in Europe, whether EU residents or non-EU students. However, the article later clarifies that many EU students pay no tuition in several countries (Austria, Denmark, Finland, France, Germany, Greece, Hungary, Norway, Poland, Slovenia, and Sweden).
The data does not reflect this benefit. For example, Germany shows a tuition cost of £219, but tuition is actually free for EU residents. In reality, the data represents costs for non-EU (international) students, but the visualization never specifies this distinction. I think it’s important to clarify their target audience in the title like “for Non-EU Students” improve accuracy and trustworthiness.


## Step three: Sketch a solution

<iframe title="Total Annual Cost of Studying in Europe for Non-EU Students" aria-label="Stacked Bars" id="datawrapper-chart-MCSZo" src="https://datawrapper.dwcdn.net/MCSZo/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="1269" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}})}();
</script>

**1. Redesign Focus: Breaking Down Costs**
- Decision: Separate the total yearly cost into tuition fees and living expenses, instead of showing only a combined figure.
- Reasoning: Students making study-abroad decisions often weigh these two factors differently. Some prioritize keeping tuition low, while others may accept higher tuition if living costs are more manageable.  Presenting them separately gives students a more realistic view of trade-offs and avoids oversimplification.

**2. Visualization Method**
- Decision: Use a stacked bar chart with countries ranked from highest to lowest total cost, and bars divided into tuition and living segments labeled with values and percentages. Use green for yearly living costs and yellow for average yearly tuition fees to create a clear visual contrast between the two components.
- Reasoning:
  - A stacked bar chart supports side-by-side comparison while still showing the contribution of each cost component.
  - Sorting by total cost makes it easy for audiences to see rankings clearly without needing to scan back and forth across a map.
  - Labels and segment shares provide both absolute numbers and proportional context, helping students evaluate not just “how much” but also what matters most.
  - The color contrast ensures the two data types are immediately distinguishable, reinforcing the breakdown and making the chart more accessible and visually intuitive.

**3. Context & Accuracy: Defining the Audience**
- Decision: Update the title to clarify that the data reflects costs for non-EU (international) students by changing it to: “Total Annual Cost of Studying in Europe for Non-EU Students).”
- Reasoning: EU residents often pay no tuition in many countries, so failing to specify the scope could mislead audiences into believing the data applies universally. Explicitly stating the scope:
  - Prevents misinterpretation.
  - Builds trust in the visualization by being transparent.
  - Ensures the data is actionable for the correct audience (primarily non-EU students).

**4. Transparency & Source Note**
- Decision: Include a note at the bottom of the visualization explaining the scope, assumptions, and source. The note reads:
“Data was collected for 28 European countries and converted into GBP (£) as of July 2024. Actual expenses may vary depending on university, city, program type, and lifestyle choices. In many countries, EU residents are eligible for free or reduced tuition, so the costs presented here may apply specifically to international (non-EU) students.” The original source is cited alongside this note.
- Reasoning:
  - Acknowledges uncertainties and variability in actual costs, helping prevent overgeneralization or misinterpretation.
  - Clarifies that the data likely applies to non-EU students, addressing a limitation in the original source, which did not clearly specify methodology.
  - Citing the source ensures transparency and credibility, making the visualization more trustworthy for decision-making.


## Step four: Test the solution

To gather feedback on my visualization, I conducted interviews using five guiding questions. Some of the questions were intentionally framed around areas where I was uncertain about my design choices, which I later realized could introduce a degree of bias. Still, the responses provided valuable insights into how viewers interpret and interact with my work. It was especially interesting to see where participants agreed, where they diverged, and how their backgrounds shaped their perspectives.

### Results: 

<img src="Interview Table.png" width="1000"/>

### Synthesis: 

**Patterns in the Feedback:**
Overall data presentation was understandable, there are specific design choices that hinder quick interpretation. Small font size, lack of clear separation between elements, and the overwhelming number of stacked bars made it harder for viewers to grasp the key insights without extra effort. I also learned that my assumption about the usefulness of regional grouping may not hold true for my audience — participants felt more comfortable making sense of data when it was presented by individual country.

**In Class Feedback:**
I also received feedback from classmates suggesting more detailed information on living costs (rent, utilities, transportation) and a clearer title, such as adding “The Cheapest” or “The Most Expensive” European country to study for Non-EU students. Because the chart includes many countries, its length makes comparisons difficult, especially with the top x-axis variables. Reducing the list to the top 10 most popular European countries for international students, ranked by the dataset, would make it more digestible. Finally, the contrast between the yellow and green bars is too strong, drawing attention almost entirely to the green bar and overshadowing the total yearly cost.

## Step five: build the solution

<iframe title="Annual Cost to Study in Nine Popular European Countries for Non-EU Students" aria-label="Stacked Bars" id="datawrapper-chart-KScuH" src="https://datawrapper.dwcdn.net/KScuH/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="518" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}})}();
</script>



## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

