# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
This visualization was created using Python, with pandas for data cleaning, grouping, and aggregation, and matplotlib for generating the bar chart.

## Dataset source: https://data.ontario.ca/dataset/2021-22-schools-with-recent-covid-19-cases
## first visualization: "Total confirmed COVID-19 cases reported in Ontario schools (daily)"


    > Who is your intended audience? 
The intended audience includes public health officials, education policymakers, school administrators, researchers, and members of the general public interested in understanding COVID-19 trends in Ontario schools.
    
    > What information or message are you trying to convey with your visualization? 
    
    The visualization shows how the total number of confirmed COVID-19 cases reported in Ontario schools changed over time during the 2021–22 school year. It highlights periods of increased or decreased reporting and provides a temporal overview of pandemic activity in schools.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    A line chart was chosen because it is well suited for representing trends over time. Dates were placed on the x-axis and total confirmed cases on the y-axis to align with common conventions. Axis labels and a descriptive title were added to ensure clarity. The figure size and rotated date labels were adjusted to improve readability and prevent overlap.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    Reproducibility was ensured by using a Python script that loads the publicly available CSV file, converts dates programmatically, aggregates the data, and generates the plot directly from the raw dataset. Any user with access to the data and the script can reproduce the visualization exactly.

    > How did you ensure that your data visualization is accessible?  
    Accessibility was considered by using clear labels, sufficient font sizes, and a simple color scheme that does not rely on color alone to convey meaning. The visualization is interpretable in grayscale and suitable for screen readers when accompanied by a textual description.

    > Who are the individuals and communities who might be impacted by your visualization?  
    Students, parents, educators, and policymakers may be impacted by this visualization, as it can influence perceptions of COVID-19 trends in schools and inform discussions about public health responses and educational policy.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    The reported_date and total_confirmed_cases variables were included because they directly support temporal trend analysis. School-level identifiers and geographic details were excluded to avoid unnecessary granularity and to focus on province-wide patterns rather than individual institutions.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Underwater labour included reviewing dataset documentation, understanding reporting limitations, converting date formats, handling aggregation decisions, and verifying that the resulting trend accurately reflected the dataset’s scope and time range.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
