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
      Good visualization
      https://public.tableau.com/app/profile/mateusz.karmalski/viz/CountrieswiththeMostHolidaysin2024makeovermonday/Dashboard12
      
      This dashboard effectively communicates a simple yet meaningful dataset: the number of public holidays in each country in 2024. It excels in visual clarity, usability, and design principles, making it a strong example of a good data visualization.
      
      Firstly, the use of a horizontal bar chart for country-by-country comparison is appropriate and intuitive. It supports Edward Tufte’s principle of maximizing the data-ink ratio—the chart avoids unnecessary decoration, focusing on the message with clean bars, consistent spacing, and minimal non-data elements.
      
      The visualization follows Shneiderman’s mantra well https://hampdatavisualization.wordpress.com/2016/02/26/schneidermans-mantra/: it offers an “overview first” through the full bar chart, “zoom and filter” through interactivity (e.g., tooltips), and “details on demand” when hovering over specific countries. The use of sorting ensures that the viewer can quickly identify which countries have the most or fewest holidays—a critical takeaway supported by the visual hierarchy.
      
      Color is used functionally: the palette is soft and non-distracting, with all bars in the same hue, avoiding semantic confusion. The inclusion of a title, clear axis labels, and legends contributes to the chart’s readability. 
      
      Lastly, The dashboard also incorporates contextual information (such as country names and number of holidays directly on the bars), which helps even those unfamiliar with the data engage without needing external references.


      Bad visualization
      https://public.tableau.com/app/profile/vizgrowth/viz/Formula12024LapTimesBeeswarm/Beeswarm
      
      This beeswarm chart aims to show lap time distributions across different Formula 1 drivers during the 2024 season. While it is visually striking, it ultimately fails to effectively communicate the underlying data. The chart displays a mass of dots without clear numerical guidance, making it difficult to interpret or extract actionable insights.
      
      One major issue is overuse of visual complexity. The chart contains hundreds of overlapping dots with minimal labeling, which may look impressive but fails to prioritize clarity. Viewers cannot easily discern which driver was fastest or most consistent without hovering over each dot—a burden on cognitive load that fails Shneiderman’s mantra: “overview first, zoom and filter, then details on demand.” https://hampdatavisualization.wordpress.com/2016/02/26/schneidermans-mantra/
      
      The lack of a clear x-axis scale and driver labels on the y-axis adds to the confusion. Finally, the visualization lacks annotation or narrative support. There are no callouts for fastest laps, no contextual data on race conditions, and no filter functionality. In summary, this chart looks intriguing but is analytically weak. It fails at basic principles of data visualization: clarity, comparability, interpretability, and user engagement.


      ```
    - How could this data visualization have been improved?  
      ```
      Your answer...
      Good visualization
      1. Highlight outliers: Use subtle color or icons to call attention to the countries with the highest and lowest number of holidays.
      2. Enable country selection for comparison: Let users select and compare two or more countries side by side with additional contextual info (e.g., GDP, work hours, etc.).

      Bad visualization

      1. Use a different chart type: Replace the beeswarm with box plots or strip plots by driver. Box plots would clearly show median, range, and outliers—ideal for comparing lap time distributions.
      2. Add axis labels and scale: Clearly label the x-axis as “Lap Time (seconds)” and the y-axis as “Driver.” Use consistent intervals on the x-axis to facilitate quick visual estimation.

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
* Submission Due Date: `23:59 - 06/07/2025`
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
