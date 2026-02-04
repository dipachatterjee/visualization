# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?  
    Excel & Graphpad Prism
    
    > Who is your intended audience?  
    The general public/anyone who may be curious about long‑term patterns in marriage activity (including city planners, event planners, government officials). It can be especially valuable for researchers such as sociologists or epidemiologists who are interested in observing broader trends in social behaviour over extended periods. By showing the average of 5 years, this graph highlights consistent seasonal and cyclical features that are meaningful and persistant.

    > What information or message are you trying to convey with your visualization?  
    Long-term seasonal and temporal patterns in marriage licence activity across the city of Toronto. By grouping data into 5-yr averages, it reduces short‑term variability and emphasizes persistent trends in how marriage activity changes throughout the year and across a greater time-span, allowing us to detect broader changes in societal behaviour over time.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?  
    Clarity/readability: axis labels, tick labels, and titles were rotated and bolded to improve legibility  
    Qualitative information: line colours and symbols were provide good contrast between different time periods while remaining distinguishable for colour-blind audiences  
    Layout/organization: plot was uncluttered, avoiding unnecessary features (e.g. gridlines), with consistent axes and spacing to allow easy comparisons  
    Consistency: fonts, sizes, and formatting were kept uniform throughout the graph to reduce clutter/visual overload  
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?  
    Excel and Graphpad are not inherently reproducible (can't re-run code blocks as most caluclations, formula, and graphs are done manually or via a clickable interface), however I will be providing the full excel and graphpad files. From there readers can see the complete dataset, all formulas used, and how each graph was made. The caveat is if the reader doesn't have excel or graphpad installed then they might not be able to see inside the files.  
    
    > How did you ensure that your data visualization is accessible?  
    Consistent layout: in the graph, each line & symbol were styled and coloured distinctly to reduce confusion for viewers, and spacing and layout were adjusted so elements do not crowd each other  
    Clear labels: the axes and titles are clearly labelled and rotated, with readable font size  
    Colour gradient: the line colours and symbols provide good contrast and is distinguishable for many types of colour‑blindness  
    Zoom feature: since this is presented on a computer, viewers can zoom in and get a clearer picture - if this was sent for print, I would porbably increase the whole figure size (which would allow me to increase font size proportionately), if needed
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Many people can be impacted by this visualization:  
    Couples that are planning on getting married might use the data to understand seasonal and yearly patterns in marriage license activity, which could help with planning venues or bookings.  
    Local businesses in the wedding industry (e.g., venues, photographers, bakers, caterers, event planners) might use these trends to anticipate busy periods and allocate resources accordingly.  
    City planners, government officials, and community organizations could use the visualization to understand demographic patterns.  
    Researchers such as sociologists or epidemiologists could observe broader trends in social behaviour in relation to marriages and how they change over multi‑year periods.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?  
    I chose to focus on the total number of marriage licenses issued per month aggregated across all four regions. I aggregated the total number of marriage licenses per month across all regions and then averaged these totals within multi‑year periods, which allowed me to smooths out yearly variability and highlights broader seasonal and long‑term patterns in marriage activity. I excluded region‑specific data and individual yearly fluctuations to avoid clutter and emphasize generalized trends. I also excluded the _id column as it's an unique identifier and does not contribute to understanding trends.

    > What ‘underwater labour’ contributed to your final data visualization product?
    There are quite a few:  
    People collecting, verifying, and maintaing the marriage licence dataset.  
    Respondants that make the data collection possible.  
    People managing and updating the Toronto Open Data portal.  
    Infrastructure engineers, database administrators, and web designers who support the servers and interfaces that make the data accessible.  
    Software developers who create and maintain data analysis tools like Excel/Microsoft Office and Graphpad Prism.  
    Source: https://open.toronto.ca/dataset/marriage-licence-statistics/

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
* Submission Due Date: `23:59 - 02/02/2026`
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
