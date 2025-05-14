# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.

ASSIGNMENT #2 Checklist

What to submit for this assignment:

* DONE - This file (assignment_3.md)
* DONE - Two data visualizations
    - assignment_3_Excel.png, and assignment_3_Python.png
    - also included in assignment_3.xlsx and Excel and assignment_3.ipynb files
* DONE - Two markdown files for each visualizations with their written descriptions
    - Excel markdown included as the "MARKDOWN" tab in assignment_3.xlsx file
    - Python markdown included in the assignment_3.
* DONE - Link to your dataset of choice
    - https://open.toronto.ca/dataset/renewable-energy-installations/
* DONE - Complete and commented code as an appendix
    - assignment_3.xlsx
    - assignment_3.ipynb
* DONE - Total word count should not exceed **(as a maximum) 1000 words** (775 words + Appendices)

START

INTRODUCTION
The City of Toronto "Renewable Energy Projects" dataset contains historic renewable energy installation information by:
- ownership type, namely solar that is 
    a) generated (owned and operated by the City), 
    b) purchased (by the City from a third-party provider) and
    c) hosted (by the City but owned by a third-party) 
- solar type, namely energy in the form of 
    a) solar photovoltaics (i.e. electricity generation),
    b) solar hot water (i.e. pre-heating and heating of water using a solar water system), and
    c) solar air heating (i.e. pre-heating and heating of air for space heating). 

This datset is for a period (1986 - 2014) but my interest is the period (2006-2014) of various solar financial support programs in Ontario, including the Renewable Energy Standard Offer Program (RESOP) and the Feed-In Tariff (FIT) Program. These programs effectively terminated in 2014.

As a result of recent declines in costs of solar generation as well as performance improvements, the City of Toronto (and most Ontario municipalities) is now considering whether to install, purchase or host additional solar energy facilities without the benefit of financial support programs. To assist the City in its decision-making, I have provided two visualizations of the City of Toronto's solar installations during the period 2006-2014. 

QUESTIONS

- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    Microsoft Excel
    Python  

    > Who is your intended audience?
    Excel - Decision-makers respecting City of Toronto solar power generation, purchasing and hosting of solar photovoltaic, solar hot water and solar air heating facilities.
    
    Python - Decision-makers respecting the City of Toronto's solar photovoltaic generation, purchasing and hosting (NOTE: only solar photovoltaics for the Python visualization).
 
    > What information or message are you trying to convey with your visualization?
    Excel - This visualization summarizes the history of solar installations during the period 2006-2014 by solar type (photovoltaic, hot water, air heating) and by solar installation type (generated, purchased, hosted), as well as the share(as %) of solar installation type by solar type. This graph attempts to convey the historical patterns of solar installations.
    
    Python - This graph focuses only on solar photovoltaics since (based on recent trends in the industry) this solar type will comprise the bulk of future solar deployment. The data is displayed as cumulative installed capacity to demonstrate how the installations of solar photovoltaics were increasing rapidly in the latter years of the period 2006-2014 and that this rapid growth was driven entirely by "generated" solar photovoltaics (i.e. owned and operated by the City). This graph attempts to show the performance of the three ownership types to spur further investigation into how and why these patterns occurred and whether they remain relevant to future investment decisions. Initial advice on whether to invest are provided on the visualization.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    > How did you ensure that your data visualization is accessible?

    (addressing the above three questions collectively)
    
    Excel
    - findable - the dataset and visualization are described using markdown text, the files are systematically named and stored in a searchable repository
    - accessible - the file is open-access and accessible with permissions on Github; the markdown is readily convertible to .txt format, and in simple, consistent language with terms defined and capitalized
    - interoperable - the data and excel script are in theory readible by both machines and humans, though the excel file would best be converted to a more readible format (e.g., csv)  
    - reproducible - addressed through a detailed "MARKDOWN" tab; this was very time-consuming to produce, reflecting the limitations of Excel to operate "programmatically"

    Python 
    - findable - the dataset and visualization are described using markdown text, the files are systematically named and stored in a searchable repository 
    - accessible - no metadata was created, the file is open-access and accessible with permissions on Github; the markdown is in .txt format, and in simple, consistent language with terms defined and capitalized
    - interoperable - the data and python script are readible by both machines and humans
    - reproducible - addressed by working programmatically and by using detailed Markdown within the Jupyter Notebook

    > Who are the individuals and communities who might be impacted by your visualization?
    - decision-makers in the City of Toronto
    - Toronto taxpayers receiving investment returns
    - Toronto ratepayers receiving electricity

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    Excel and Python
    - Inclusion/Exclusion - I was interested in a particular period when facilities were receiving financial incentives to develop renewable energy projects (i.e. 2006-2014)
    - Completeness - The dataset contained key gaps in the parameter of interest, installed capacity (eKW), for non-solar energy projects, so these were excluded
    
    Python (alone)
    - Opportunity - solar photovoltaics provide the most opportune investment opportunity at this time, so this meant focusing the Python visualization only on solar photovoltaics

    > What ‘underwater labour’ contributed to your final data visualization product?
  
    Excel and Python
    - contributors (underwater labour)
        - data providers (solar facility operators)
        - data collectors, collators, programmers, managers (City of Toronto)
        - data hosters (City of Toronto)
        - municipal taxpayers (City of Toronto)
        - data management and visualization software developers

END


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
* Submission Due Date: `23:59 - 09/05/2025`
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
