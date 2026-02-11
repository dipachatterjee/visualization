# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?  
    Jupyter & Python 
    
    > Who is your intended audience?  
    The general public/anyone who might be interested in marriage activity trends (city planners, event planners, government officials tracking population/census/citizenship)

    > What information or message are you trying to convey with your visualization?  
    Monthly trends in (potential) marriages across Toronto’s four civic centres from 2011 to 2026 via heatmap...highlighting seasonal patterns (e.g. winter vs summer), yearly anomalies (e.g. decreases during 2020-2021 for COVID), and regional differences (e.g. greater numbers in Toronto) in marriage activity.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?  
    Clarity/readability: axis labels, tick labels, and titles were rotated and bolded to improve legibility  
    Quantitative information: each cell in the heatmap is annotated with the exact number of licenses for precise data awareness  
    Qualitative information: colour gradients (magma) were chosen to show intensity while remaining distinguishable for colour-blind audeinces  
    Layout/organization: subplots were arranged in a 2x2 grid, with consistent axes and spacing to allow easy comparisons  
    Consistency: fonts, sizes, and formatting were kept uniform across all subplots to reduce clutter/visual overload
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?  
    For the jupyter notebook/python, I am providing the full Jupyter Notebook with all code cells intact, so a reader can rerun the entire notebook and regenerate the visualizations. Alternatively, I can put the codes in a notepad file and submit them, but for this assignment I will leave the whole notebook on file. The caveat is if the reader does not have python or jupyter notebook installed, or doesn't understand how to run code, it will not be possible to reproduce this file.
    
    > How did you ensure that your data visualization is accessible?  
    Consistent layout: the 2×2 grid layout helps viewers know where to look and makes patterns easier to compare across regions, including vertical and horizontal lines to physically break the subplots apart into their own visual quadrants (avoiding visual clutter)  
    Clear labels: the axes and titles are clearly labelled and rotated  
    Colour gradient: the magma palette provides good contrast and is distinguishable for many types of colour‑blindness  
    Annotations: cells are annotated with numbers, so viewers who may struggle with colour interpretation can still read exact values...the font for this might be a bit small due to space constraints, but since this is presented on a computer, viewers can zoom in and get a clearer picture - if this was sent for print, I would porbably increase the whole figure size (which would allow me to increase font size proportionately)
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    Many people can be impacted by this visualization:  
    Couples that are planning on getting married might use the data to understand seasonal and yearly patterns in marriage license activity (both within their district and in neighbouring districts), which could help with planning venues or bookings.  
    Local businesses in the wedding industry (e.g., venues, photographers, bakers, caterers, event planners) might use these trends to anticipate busy periods and allocate resources accordingly.  
    City planners, researchers, government officials, and community organizations could use the visualization to understand demographic patterns.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?  
    I chose key features (the number of marriage licenses issued, the month, year, and the specific civic centre) that would allow a clear comparison of marriage activity across time and location. I excluded the _id column as it's an unique identifier and does not contribute to understanding trends. I also chose to create four separate subplots (one per region) instead of plotting everything onto one graph to avoid overcrowding and make comparisons easier/improve readability. 

    > What ‘underwater labour’ contributed to your final data visualization product?  
    There are quite a few:  
    People collecting, verifying, and maintaing the marriage licence dataset.  
    Respondants that make the data collection possible.  
    People managing and updating the Toronto Open Data portal.  
    Infrastructure engineers, database administrators, and web designers who support the servers and interfaces that make the data accessible.  
    Software developers who create and maintain data analysis tools like Python, Jupyter, and the many packages.  
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
