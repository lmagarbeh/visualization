# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
Bad visualization (#1): 
      This visualization is a sorted stream graph showing terrorist attacks over time by motivation (religious, political, and ethnic), but it is a poor choice for accurate data interpretation. Stream graphs encode values using area and shifting baselines, which makes precise comparison across time and between categories difficult; research in graphical perception shows that position on a common scale is far more accurate than area or shape for quantitative judgment (Cleveland & McGill, 1984). Because the layers are reordered and lack a stable baseline, viewers cannot easily determine the magnitude of change for each category or compare values at specific time points (Munzner, 2014). The dramatic visual emphasis on the post-2007 increase in religious attacks, reinforced by the “+438%” headline, further biases interpretation and risks exaggerating the perceived trend, prioritizing rhetorical impact over analytical clarity. 


Good visualization (#2): 
    This visualization is a strong example of an effective time-series line chart because it clearly communicates trends in profile views over time using appropriate visual encoding. The line chart leverages position along a common scale, which is one of the most accurate perceptual channels for judging quantitative change (Cleveland & McGill, 1984). The clean design, limited color palette, and subtle background bars provide additional context without overwhelming the main trend, reducing cognitive load and supporting quick interpretation. Axes, markers, and labels are simple and legible, allowing viewers to easily identify peaks, dips, and overall patterns. Overall, the chart balances aesthetic appeal with clarity, making it well suited for dashboard-style communication and rapid decision-making. 

References: 

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American Statistical Association.
https://www.jstor.org/stable/2288400

Munzner, T. (2014). Visualization Analysis and Design. CRC Press.
https://www.cs.ubc.ca/~tmm/vadbook/


      ```
    - How could this data visualization have been improved?  
      ```
      The sorted stream graph could be improved by redesigning it to support more accurate comparison and interpretation. First, replacing the stream graph with a stacked bar chart or multiple line charts with a fixed baseline would allow viewers to compare changes over time more precisely, since position on a common scale is perceptually more accurate than area or curvature. If a stacked format is retained, keeping a consistent category order and stable baseline would reduce confusion caused by shifting layers (Munzner, 2014). Second, adding clear axis labels, numerical values, and normalized rates (e.g., attacks per population) would provide essential context and reduce the risk of misleading conclusions. 

      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 10/26/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
