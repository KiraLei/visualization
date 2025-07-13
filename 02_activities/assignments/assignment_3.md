# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

✅ Visualization 1: Pet Licence Trends by Year
    > What software did you use to create your data visualization?
        I used Python with the Seaborn and Matplotlib libraries to generate a grouped bar chart.
    > Who is your intended audience?
    My intended audience includes Toronto city planners, animal services teams, and local residents who are interested in trends in pet ownership.

    > What information or message are you trying to convey with your visualization?
    The goal is to show how many dogs and cats were registered each year from 2020 to 2023 and to compare trends between the two species.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    I considered clarity and readability. I used contrasting colors (blue for dogs, orange for cats), a clean grid style, clear axis labels, and a title. The bar chart format makes comparisons between years and species easy to see.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    The full code and dataset are publicly available. The code uses only common libraries, and all steps are documented. Anyone can reproduce the visualization by running the script with the same data.

    > How did you ensure that your data visualization is accessible?
    I used accessible color palettes that are distinguishable by people with color blindness. The font sizes are large, and the title and axis labels are descriptive. I also exported the image with alt-text in the final version.

    > Who are the individuals and communities who might be impacted by your visualization?
    Animal advocacy groups, municipal pet service providers, and communities with growing pet ownership may use this information to adjust services or raise awareness about licensing needs.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I excluded columns like "Animal Name" and "Breed", which are too detailed for trend analysis. I focused on "Year" and "Species", which were essential for showing the trend over time.

    > What ‘underwater labour’ contributed to your final data visualization product?
    I cleaned the data by filtering out years before 2020 and missing values. I grouped data by year and species, tested multiple chart types, formatted titles, and customized the style for clarity and impact.

    ✅ Visualization 2: Top Neighbourhoods for Pet Licences (Heatmap)
    Tool used: Microsoft Excel (Conditional Formatting)

    > What software did you use to create your data visualization?
    I used Microsoft Excel and its built-in heatmap-style conditional formatting to visualize the top neighbourhoods with the most pet licences.

    > Who is your intended audience?
    This visualization targets local residents and community organizations interested in pet ownership distribution across Toronto.

    > What information or message are you trying to convey with your visualization?
    I want to highlight which Toronto neighbourhoods have the highest number of pet licences from 2020 to 2023 and how this varies over time.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    I used a table format with conditional color gradients (green to red) to emphasize variation in registration numbers. Each cell also includes the exact value for clarity. Row and column headers are clearly labeled.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    Excel is not fully reproducible without manual steps. To address this, I saved both the original data and the formatted version. I also wrote down the transformation steps and included formulas to make it easier for someone else to recreate.

    > How did you ensure that your data visualization is accessible?
    I used a colorblind-friendly gradient and ensured all cells included numerical values so that color is not the only way to interpret the data. The table is screen-reader friendly.

    > Who are the individuals and communities who might be impacted by your visualization?
    Neighbourhood associations, veterinary clinics, and community dog parks may use this information to allocate resources or tailor outreach efforts.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I focused on “Neighbourhood Name” and “Year” as the main variables. I limited the visualization to the top 10 neighbourhoods by total registrations to keep it simple and readable.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Work included grouping data by neighbourhood and year, creating pivot tables, checking for inconsistent spellings of neighbourhoods, filtering to the top 10 rows, and applying color formatting for visual emphasis.



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
* Submission Due Date: `23:59 - 13/07/2025`
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
