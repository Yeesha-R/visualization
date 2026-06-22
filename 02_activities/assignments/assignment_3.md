# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?


# TTC Subway Delay Data Visualization Report
# The Dataset

For this visualization assignment, I used the 2025 TTC Subway Delay data obtained from the city of Toronto Open Data Portal (https://open.toronto.ca/dataset/ttc-subway-delay-data/). The dataset contains information about subway delays, including the date, time, station location, subway line, delay duration, and service gap. I selected this dataset because public transit reliability affects many Toronto residents and provides opportunities to explore both operational patterns and service performance.


## Visualization 1: Number of Delays by Subway Line (Python)

### What software did you use?

I used Python with Pandas and Matplotlib libraries because it allows transparent data processing and reproducible visualization creation through code. 

### Who is your intended audience?

The intended audience includes TTC riders, Toronto residents, transportation researchers, and city planners interested in understanding transit reliability across the subway network.

### What information or message are you trying to convey?

This visualization shows the number of delay incidents reported on each TTC subway line. The chart demonstrates that Line 1 (Yonge-University) and Line 2 (Bloor-Danforth) account for the majority of reported delays, while Line 4 (Sheppard) experiences relatively fewer incidents. The visualization helps identify where delays occur most frequently within the system.

### What aspects of design did you consider?

I chose a bar chart because it is effective for comparing categorical values. Clear axis labels and a descriptive title help viewers understand the chart quickly. During data exploration, I found that the Line variable contained several inconsistent entries that did not represent TTC subway lines. To improve accuracy and readability, I filtered the data to include only valid subway line categories, including Line 1 (Yonge–University), Line 2 (Bloor–Danforth), Line 4 (Sheppard), and combination line categories. I also replaced line abbreviations with full line names to improve readability and accessibility. Finally, I used a simple visual design with a single colour scheme and minimal visual effects so that viewers could focus on the data rather than decorative elements.

### How did you ensure reproducibility?

I created the visualization entirely using Python code. Because the data cleaning, aggregation, and chart creation processes are documented in code, another person can reproduce the visualization using the same dataset and script.

### How did you ensure accessibility?

I supported accessibility through clear labels, readable font sizes, and high contrast between chart elements and the background. The visualization does not rely solely on color to communicate information.

### Who might be impacted by this visualization?

The visualization may be relevant to TTC riders, transit advocacy groups, city officials, transportation planners, and TTC management. The findings may contribute to discussions about transit infrastructure and service improvements.

### How did you choose which features to include or exclude?

I included the "Line" variable because it directly addresses the question of where delays occur most frequently. Variables such as station location, day of week, and vehicle number were excluded because they were not necessary for comparing delay frequency across subway lines.

### What underwater labour contributed to the final visualization?

The final chart required reviewing the dataset documentation, cleaning records, checking for missing values, grouping observations by subway line, and calculating delay counts. These preparation steps are not visible in the final chart but were necessary to ensure accurate results.





## Visualization 2: Average TTC Subway Delay Duration by Day of Week (Excel)

I used Microsoft Excel to create a PivotTable and bar chart showing average delay duration by day of the week. Excel was selected because it provides efficient tools for data aggregation and visualization.

### Who is your intended audience?

The intended audience includes TTC riders, commuters, policymakers, and members of the public who are interested in understanding when longer delays are most likely to occur.

### What information or message are you trying to convey?

This visualization shows how average delay duration varies throughout the week. The results indicate that delay durations are relatively consistent across all days, although Sunday experiences the highest average delay duration. This suggests that while delays occur throughout the week, there may be operational factors that contribute to slightly longer disruptions on Sundays.

### What aspects of design did you consider?

I chose a bar chart because it allows straightforward comparison between days of the week. The chart uses clear axis labels, an informative title, and a simple colour scheme. The design emphasizes readability and avoids unnecessary decorative elements.

### How did you ensure reproducibility?

I documented the Pivottable methodology so that another user could recreate the chart using the same dataset. However, Excel relies on manual steps and is therefore somewhat less reproducible than code-based approaches. Different users may make slightly different formatting choices when recreating the visualization.

### How did you ensure accessibility?

I supported accessibility through readable text, clear labels, and sufficient contrast between the bars and background. Information is communicated through both labels and bar height rather than colour alone.

### Who might be impacted by this visualization?

The visualization may be useful for TTC riders planning travel, transit researchers studying service reliability, and decision-makers evaluating system performance.

### How did you choose which features to include or exclude?

I included the "Day of Week" and "Delay Duration (minutes)" variables because they directly support the question of whether delay severity differs across the week. Variables such as Delay causes, time of day, Specific subway lines, and vehicle number were excluded to keep the visualization focused and easy to interpret. Also, too many dimensions would have reduced clarity.

### What underwater labour contributed to the final visualization?

The final chart required reviewing the data preparation, transformation, quality check, and creating a separate pivot table before visualization. These tasks were essential to producing an accurate and interpretable visualization.





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
* Submission Due Date: `23:59 -  2026-06-16`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * Two distinct data visualizations (for example, PNGs, PDFs, or screenshots)
        * Two Markdown files answering all questions for each visualization (including a link to your dataset in both files)
        * One Python file contains the complete code and visualization, and another file (with or without code) contains the visualization.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
