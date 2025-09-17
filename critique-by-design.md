| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The cheapest countries to study in Europe

In this critique, I apply principles from Good Charts and Stephen Few’s [Data Visualization Effectiveness Profile](https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) to evaluate and redesign a visualization from the article “The Cheapest Countries to Study in Europe.” The original chart—a shaded map of Europe showing total yearly study costs—provides a clear geographic frame but leaves gaps in precision, completeness, and audience alignment. To strengthen the critique, I also incorporate feedback from audience interviews, which reveal how real users interpret, struggle with, or disengage from the design. By combining theoretical frameworks with external perspectives, I will break down the visualization step by step, highlighting design trade-offs, contextual limitations, and opportunities for improvement. My goal is to demonstrate how thoughtful redesign choices, informed by both expert guidance and user feedback, can transform the chart into a more accurate, engaging, and decision-oriented tool for students evaluating study-abroad options.

## Step one: the visualization

<img src="Critic - Data Viz _Original.png" width="1000"/>

I selected this particular data visualization from the article “The Cheapest Countries to Study in Europe” because study-abroad costs are a pressing concern for many international students, and the visualization attempts to summarize complex financial data in a way that is approachable for a general audience. Its accessibility and practical focus make it an ideal case for critique, as the stakes are high—misleading or incomplete representations could directly influence how students perceive affordability across different countries. As someone currently studying in the United States, where both tuition and living expenses are notably high, I am also curious to see how the costs of studying in Europe compare. This personal perspective makes the visualization especially relevant and engaging to analyze.

**Citation**: Boyle, Matthew, and Sophie Barber. “The Cheapest Countries to Study in Europe.” Finder UK. Updated July 11, 2024. Accessed September 17, 2025. https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe


## Step two: the critique

**1. First Impressions & Design Strengths**
•	The visualization uses a map of Europe with a gradient legend to show total yearly study costs.
•	The geographic framing is intuitive—audiences immediately connect the shading to cost differences across countries.
•	The title is clear and aligned with the data, making the visualization accessible and easy to read.

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

<img src="Critic - Data Viz _Redesign.png" width="1200"/>

**1. Redesign Focus: Breaking Down Costs**
- Decision: Separate the total yearly cost into tuition fees and living expenses, instead of showing only a combined figure.
- Reasoning: Students making study-abroad decisions often weigh these two factors differently. Some prioritize keeping tuition low, while others may accept higher tuition if living costs are more manageable.  Presenting them separately gives students a more realistic view of trade-offs and avoids oversimplification.

**2. Visualization Method**
- Decision: Use a stacked bar chart with countries ranked from highest to lowest total cost, and bars divided into tuition and living segments labeled with values and percentages. Use green for yearly living costs and yellow for average yearly tuition fees to create a clear visual contrast between the two components.
- Reasoning:
o	A stacked bar chart supports side-by-side comparison while still showing the contribution of each cost component.
o	Sorting by total cost makes it easy for audiences to see rankings clearly without needing to scan back and forth across a map.
o	Labels and segment shares provide both absolute numbers and proportional context, helping students evaluate not just “how much” but also what matters most.
o	The color contrast ensures the two data types are immediately distinguishable, reinforcing the breakdown and making the chart more accessible and visually intuitive.

**3. Context & Accuracy: Defining the Audience**
- Decision: Clarify that the chart reflects costs for non-EU (international) students.
- Reasoning: EU residents often pay no tuition in many countries, so failing to specify the scope could mislead audiences into believing the data applies universally. Explicitly stating the scope:
• Prevents misinterpretation.
• Builds trust in the visualization by being transparent.
• Ensures the data is actionable for the correct audience (primarily non-EU students).

**4. Transparency & Source Note**
- Decision: Include a note at the bottom of the visualization explaining the scope, assumptions, and source. The note reads:
“Data was collected for 28 European countries and converted into GBP (£) as of July 2024. Actual expenses may vary depending on university, city, program type, and lifestyle choices. In many countries, EU residents are eligible for free or reduced tuition, so the costs presented here may apply specifically to international (non-EU) students.” The original source is cited alongside this note.
- Reasoning:
•	Acknowledges uncertainties and variability in actual costs, helping prevent overgeneralization or misinterpretation.
•	Clarifies that the data likely applies to non-EU students, addressing a limitation in the original source, which did not clearly specify methodology.
•	Citing the source ensures transparency and credibility, making the visualization more trustworthy for decision-making.


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

