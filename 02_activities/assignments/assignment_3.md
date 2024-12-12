# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Your answer...
        
Good Data visualization:
Gapminder - Global Trends in Life Expectancy and Income
Link：https://www.gapminder.org/tools/#$chart-type=bubbles&url=v2

Accessibility
Gapminder’s design is mostly accessible due to its clean layout and interactive features. According to Ware (2012), effective visualizations use clear visual cues, and Gapminder achieves this with hoverable tooltips and a well-structured interface. However, its reliance on color to represent regions can exclude color-blind users, as Few (2006) points out. Adding patterns or textures to bubbles and regions could help. Additionally, the heavy focus on visuals makes it hard for screen readers to convey key information, limiting access for visually impaired users.

Reproducibility
While Gapminder provides raw data and source references, it lacks details about how the data is processed, cleaned, or adjusted, which are key for reproducibility (Munzner, 2014). For example, users don’t know how missing data is handled or how life expectancy is interpolated for gaps in records. Without this, other researchers or users cannot fully replicate the findings or build upon them, as Kirk (2019) emphasizes.

Equity
Gapminder supports equity by including data from a wide range of countries and regions, following D’Ignazio and Klein’s (2020) principle of giving visibility to underrepresented groups. However, smaller nations can be overshadowed by large bubbles representing populous countries like China or India. This makes it harder to notice trends from these regions, which could limit the fairness of the visualization.

References：
Ware, C. (2012). Information Visualization: Perception for Design.
Few, S. (2006). Information Dashboard Design.
Munzner, T. (2014). Visualization Analysis and Design.
Kirk, A. (2019). Data Visualisation: A Handbook for Data Driven Design.
D’Ignazio, C., & Klein, L. F. (2020). Data Feminism.

Bad Data Visualization:

Accessibility
This visualization lacks accessibility in several ways. While the basic bar chart format is simple, the truncated y-axis misrepresents the data and requires viewers to mentally reconstruct the true scale. According to Tufte (2001), good visualizations should minimize cognitive load and clearly communicate the magnitude of changes. Additionally, the inconsistent bar widths and lack of clear labels make the chart harder to interpret, violating Few's (2006) principle of visual clarity.

Reproducibility
The chart is not reproducible because it omits critical information about the data source, sample size, and methodology. Munzner (2014) emphasizes the importance of transparency in data visualization, noting that providing metadata allows others to verify and reproduce results. Without this context, viewers cannot confirm the reliability of the chart or replicate its findings.

Equity
The visualization is not equitable, as it exaggerates the decline in Christian affiliation through visual manipulation (e.g., truncated y-axis). This design choice introduces bias, potentially misleading viewers about the significance of the trend. According to D’Ignazio and Klein (2020), equitable data visualizations should present information fairly and avoid amplifying bias. Furthermore, the chart does not provide information about other religious affiliations or secular trends, leaving out critical context that could provide a more balanced perspective.

References
Few, S. (2006). Information Dashboard Design.
Munzner, T. (2014). Visualization Analysis and Design.
Tufte, E. R. (2001). The Visual Display of Quantitative Information.
D’Ignazio, C., & Klein, L. F. (2020). Data Feminism.

        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Your answer...

Good example --

Accessibility:
Use patterns or shapes in addition to colors for bubbles and regions to support color-blind users. Add text descriptions for key trends to make it compatible with screen readers.

Reproducibility:
Share details about data processing, including how missing data is handled or how trends are smoothed. This will help others verify or replicate the analysis.

Equity:
Highlight smaller countries by adding notes or annotations for their specific trends. Adjust bubble scaling slightly to avoid small nations being overshadowed by larger ones.
        ```

Bad example --

Accessibility：
Start the Y-Axis at Zero: Adjust the y-axis to begin at 0%, ensuring that the visual representation accurately reflects the true scale of change. 
Add Clear Labels and Titles: Include specific labels for the x-axis (years) and y-axis (percentage of Christian population), along with a descriptive title, to clarify the data being represented. 

Reproducibility：
Provide Metadata: Include information about the data source, sample size, methodology, and time period covered. 
Include a Legend or Additional Annotations: If the chart aims to compare groups (e.g., different religious affiliations), provide a legend or textual annotations to explain the categories clearly.

Equity：
Avoid Biased Design Choices: Avoid truncating the y-axis or using inconsistent visual elements, as these choices can exaggerate trends and mislead viewers. 
Present Comparative Context: Include data about other religious groups or trends in secularism to provide a balanced and comprehensive view of the population changes. This ensures that the visualization reflects a broader societal context and aligns with principles of fairness and inclusivity.



### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
