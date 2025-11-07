# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    
    
    Q1> What software did you use to create your data visualization?

Jupyter Notebook: I wrote code in Python using a Jupyter notebook. with Matplotlib and Seaborn for a static, reproducible bar chart.

Power BI/ Bar chart: I built it in Microsoft Power BI BI to create an interactive, multi-visual dashboard for making business reports.

    Q2> Who is your intended audience? 

Jupyter Notebook: Healthcare policymakers and public health researchers needing a clear, statistical view of geographic disparity.

Power BI/ Bar chart: Healthcare administrators and community planners requiring an interactive tool for resource allocation and detailed exploration.
   
   Q3 > What information or message are you trying to convey with your visualization? 

Jupyter Notebook: Toronto has way more diabetes clinics than anywhere else. This probably means it's much harder for people in other cities to get the care they need.

Power BI/ Bar chart: To provide a comprehensive overview of clinic patterns, combining geographic spread with a detailed directory for a complete analytical picture.


    Q4> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 

Jupyter Notebook: I kept it simple. I put the numbers right on the bars so you don't have to guess, and I pointed out Toronto with an arrow because it's the most important takeaway. I used a simple blue color that's easy on the eyes. (Toronto's lead).

Power BI/ Bar chart: Focused on a functional dashboard layout with interactive filtering. The chart gives you the big story at the top, and the list on the side lets you find details. It's set up so you can likely click on things to filter the information.


   Q5 > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

Jupyter Notebook: Yes, absolutely Highly reproducible, I can send them my Python scriptand data file, and they can run it to get the exact same picture.


Power BI/ Bar chart: It's trickier. They would need a copy of my Power BI file and the right software to open it. It's not as straightforward as the code.


    Q6> How did you ensure that your data visualization is accessible?  

 

Jupyter Notebook: I think so.The most important info or the numbers is written directly on the chart, a high-contrast color scheme, and a logical layout to serve a broad audience, including those with visual impairments.

Power BI/ Bar chart: It might be okay, but it's less certain. It depends on if I took the time to add descriptions for screen readers. The blue background might make some text a little harder to read for people with low vision


    
    Q7> Who are the individuals and communities who might be impacted by your visualization? 


Jupyter Notebook: People living in cities at the bottom of the chart or not on it at all might feel ignored. Health planners could use this to argue for more funding for those areas

Power BI/ Bar chart: Empowers health authorities and advocates with the data to identify specific service gaps and campaign for more equitable funding and planning.


    Q8> How did you choose which features of your chosen dataset to include or exclude from your visualization? 


Jupyter Notebook: Included only the top cities by clinic count for a focused, high level comparison, excluding finer details to ensure clarity.

Power BI/ Bar chart: I wanted to show both the big picture and the details. So I included the summary chart but also kept the full list of all cities for people who need to look something up.


    Q9> What ‘underwater labour’ contributed to your final data visualization product?

Jupyter Notebook: A lot of time was spent writing and tweaking the code getting the labels to angle correctly, placing the "Toronto" arrow in just the right spot, and making sure the file saved properly. It's more than just pressing a "make graph" button.

Power BI/ Bar chart: The hidden work was in cleaning up the original data, getting the chart and the list to talk to each other, and arranging everything on the page to look neat and professional. It's like the wiring behind the walls of a house—you don't see it, but it makes everything work.


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
