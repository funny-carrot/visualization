# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      Your answer...
      
Good example:
A very classic data visualization: Gapminder - Global Trends in Life Expectancy and Income
link：https://www.gapminder.org/tools/#$chart-type=bubbles&url=v2

1. Dynamic Interactivity
Gapminder’s interactive timeline enables users to observe changes in life expectancy and income over decades, vividly demonstrating the dynamic relationship between economic growth and public health. According to Ware (2012), interactivity enhances user engagement by allowing exploration of data at their own pace. Gapminder’s smooth bubble animations make transitions intuitive, supporting clear communication of trends and patterns (Few, 2006).

2. Multi-Dimensional Data Representation
The visualization integrates multiple data dimensions.Munzner (2014) highlights that combining multiple attributes in a single visualization helps users discover relationships across variables. Gapminder does this effectively by providing a cohesive view of complex global trends.

4. Clear and Intuitive Design
Despite the large amount of data, Gapminder avoids overwhelming users by employing a clean and organized layout. Its use of distinct color schemes and well-spaced elements aligns with principles outlined by Few (2006), ensuring clarity while minimizing cognitive load.

5. Engaging Narrative Power
Gapminder goes beyond data presentation to tell a compelling story about global development. It illustrates key historical trends, such as rapid industrialization in Asia or the impact of healthcare advancements on life expectancy. This storytelling aspect reflects D’Ignazio and Klein’s (2020) emphasis on using data to highlight societal progress and disparities.

6. User Empowerment through Customization
Gapminder allows users to filter countries, adjust timelines, and explore specific regions or trends. As Kirk (2019) notes, empowering users to interact with data fosters a deeper understanding and personal connection to the information.

References

D’Ignazio, C., & Klein, L. F. (2020). Data Feminism.
Few, S. (2006). Information Dashboard Design.
Kirk, A. (2019). Data Visualisation: A Handbook for Data Driven Design.
Munzner, T. (2014). Visualization Analysis and Design.
Ware, C. (2012). Information Visualization: Perception for Design.

Bad example:
Fox News Misleading Bar Chart on Christian Population Decline
Link: https://www.codeconquest.com/blog/12-bad-data-visualization-examples-explained/

1. Truncated Y-Axis: The bar chart displays the percentage of Americans identifying as Christians in 2009 and 2019, with the y-axis starting at 58% instead of 0%. This truncation exaggerates the visual difference between the two percentages, making the decline appear more dramatic than it is. According to Tufte (2001), truncating the y-axis can mislead viewers by overstating changes in data.

2. Inconsistent Bar Widths: The bars representing the two years have different widths, which can distract viewers and imply a difference in significance or value that doesn't exist. Munzner (2014) emphasizes that consistent visual elements are crucial for accurate data interpretation.

3. Lack of Contextual Information: The chart does not provide information about the sample size, margin of error, or the source of the data. This absence of context makes it difficult for viewers to assess the reliability and significance of the information presented. Few (2006) notes that providing context is essential for informed interpretation of data visualizations.

References

Tufte, E. R. (2001). The Visual Display of Quantitative Information.
Munzner, T. (2014). Visualization Analysis and Design.
Few, S. (2006). Information Dashboard Design.

      ```
    - How could this data visualization have been improved?  
      ```
      Your answer...

Good example: Gapminder - Global Trends in Life Expectancy and Income
   
1、Add Narrative Annotations: To enhance the storytelling aspect of the visualization, narrative annotations could be added to highlight significant global events that have shaped trends.
For example:
- 2008 Financial Crisis: Show how the crisis impacted global income levels, especially in developing nations. An annotation could explain why some regions experienced stagnant or declining income during this period.
- COVID-19 Pandemic (2020-2021): Illustrate how the pandemic caused disruptions in life expectancy, particularly in regions with overwhelmed healthcare systems. Highlight key statistics, such as the drop in average life expectancy in countries like the U.S. or India.
- Industrialization in Asia (1980s): Annotate the rapid economic growth in China and Southeast Asia, linking it to a sharp rise in life expectancy due to improved healthcare access and living standards.
Enhance Accessibility Features (Additional Improvement):
Currently, the visualization heavily relies on color to convey regions and bubble size for population, which may exclude users with visual impairments (e.g., color blindness). To address this:

2、Add text labels to key bubbles so that users can directly identify countries without relying on hover actions.
Use patterns or textures for bubbles or axes, providing alternative ways to distinguish data points.
Ensure screen readers can describe the key data for each country, making the tool usable for people with visual disabilities.
Why Accessibility is Crucial:
Improving accessibility broadens the reach of the visualization, ensuring that diverse audiences, including those with disabilities, can engage with the data. This is especially important for tools like Gapminder that aim to educate users globally.

By incorporating narrative annotations and accessibility improvements, Gapminder could provide a richer, more inclusive experience while deepening users’ understanding of global historical and social dynamics.

Bad example: Fox News Misleading Bar Chart on Christian Population Decline

1. Start the Y-Axis at Zero: Adjust the y-axis to begin at 0% to accurately represent the magnitude of change between 2009 and 2019. 

2. Ensure Consistent Bar Widths: Use uniform bar widths to prevent any unintended emphasis or bias.

3. Provide Detailed Annotations: Include information about the data source, sample size, and margin of error to offer viewers the necessary context for understanding the chart's significance.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
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

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
