# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
     Python with libraries such as Plotly, Matplotlib, and Pandas.
     I also used Tableau to create the data visualizations for this assignment
     # link : https://public.tableau.com/views/Ontario_Housing_Dashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

    > Who is your intended audience? 
    Policy Makers: To understand which municipalities are meeting or lagging behind housing targets.
    Urban Planners: To identify areas that need more resources or attention.
    General Public: To raise awareness about housing progress in Ontario.
    Researchers: To analyze trends and patterns in housing development.

    > What information or message are you trying to convey with your visualization? 
    Progress Tracking: Show how municipalities are performing against their 2024 housing targets.
    Trends: Identify patterns or correlations between housing targets and progress.
    Top and Bottom Performers: Highlight the municipalities with the highest and lowest progress percentages.
    Accessibility: Make the data easy to understand for a non-technical audience
    Geographical Distribution: A map shows the distribution of housing progress across Ontario, highlighting regions that are excelling or struggling.
    Housing Target Status: Color-coding and tooltips provide insights into whether municipalities are "On track," "Not met," or "Exceeded" their targets

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
# Substantive Principles:
    Relevance: Focused on key metrics like Progress % for 2024 and Total housing progress since 2022.
    Accuracy: Ensured the data was correctly represented by using precise calculations and labels.
    Clarity: The map and bar charts are designed to be easy to interpret, with clear labels and tooltips.
# Perceptual Principles:
    Clarity: Used clear labels, titles, and legends to make the visualizations easy to interpret.
    Color Coding: Used distinct colors (e.g., green for top performers, red for bottom performers) to highlight differences.
    Hierarchy: The map is the central focus, with bar charts placed below to provide additional context.
    Hover Interactivity: Added hover tooltips to provide additional context (e.g., municipality names, exact progress percentages).
# Aesthetic Principles:
    Consistency: Used consistent color schemes and fonts across all visualizations.
    Simplicity: Avoided clutter by focusing on the most important data points.
    Balance: Ensured that the visualizations were well-proportioned and visually appealing.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
# Reproducibility:
    Code Sharing: Provided the complete Python code used to generate the visualizations.
    Data Source: Linked to the original dataset from the Ontario government website.
    Documentation: Included comments in the code to explain each step.
    Version Control: Used tools like Git to track changes and ensure consistency.
    Environment: Specified the Python libraries and versions used (e.g., Plotly 5.15.0, Pandas 2.0.0).
    Tableau Workbooks: The Tableau workbook (.twb or .twbx) is saved and shared, allowing others to reproduce the visualizations. The workbook includes all data connections and calculations.

# Impact of Non-Reproducibility:
    If the tool or process were not reproducible, it would be difficult for others to verify the results or recreate the visualizations. This could reduce the credibility and usefulness of the analysis.
    Tableau Public workbooks are reproducible only if the user has access to Tableau. To mitigate this, screenshots and descriptions are included in the GitHub repository.

    > How did you ensure that your data visualization is accessible?  
Colorblind-Friendly Palettes: Used color schemes that are distinguishable for colorblind users.
Alt Text: Provided descriptions of the visualizations for screen readers.
Interactive Features: Enabled zooming, panning, and hover tooltips to make the visualizations more engaging and accessible.
Clear Labels: Used large, readable fonts for titles, axis labels, and legends.
Responsive Design: Ensured the visualizations are usable on different devices (e.g., desktops, tablets, mobile phones).
Interactive Elements: Filters and highlight actions make the dashboard more accessible by allowing users to explore the data in different ways
    
    > Who are the individuals and communities who might be impacted by your visualization?  
Municipal Governments: May use the insights to adjust housing policies or allocate resources.
Residents: May gain awareness of housing progress in their area and advocate for change.
Developers: May identify opportunities for new housing projects in high-need areas.
Non-Profit Organizations: May use the data to advocate for affordable housing initiatives.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
Included Features:
Progress % for 2024: To measure how close municipalities are to meeting their targets.
Total housing progress since 2022: To show overall progress over time.
Municipality: To identify specific regions.
Housing Target Status: To categorize municipalities as "Not met", "On track", or "Exceeded".
Excluded Features:
Irrelevant Columns: Excluded columns like _id that do not contribute to the analysis.
Redundant Data: Excluded columns that were highly correlated with others to avoid clutter.

    > What ‘underwater labour’ contributed to your final data visualization product?
Underwater Labour:
Data Cleaning: Removed missing or inconsistent data, standardized column names, and converted data types.
Data Analysis: Calculated metrics like Progress % for 2024 and identified top/bottom performers.
Research: Researched best practices for data visualization design and accessibility.
Testing: Tested different visualization types (e.g., scatter plots, bar charts) to find the most effective one.
Documentation: Wrote detailed explanations and comments to ensure reproducibility and clarity.

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
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
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
