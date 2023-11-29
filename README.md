# Final-Project-Tableau

## Project/Goals
The goal of this project is to create visuals for a provided dataset, using Tableau. The visuals should present some relevant insights or trends in the data.

## Process
1. Viewing the dataset in Excel, text editors, etc. to understand the context of the data and what the theme of the dataset is. This helps decide what initial visuals to create.
2. Load the dataset into Tableau, checking data types and where connections can be made.
3. Create visuals, guided by questions pertaining to the dataset.
4. Create dashboards to present particularly insightful or informative data. 

## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)
This project uses `Option 1`. The results I found where that economic indeces tend to increase steadily with time, even with external factors such as an economic crisis. In fact, economic crises only affected housing construction (which is assumed, since a model for that relationship was not made) from the provided data. The most interesting trend I found was by modeling a linear regression between office prices and the consumer index (prices of market goods). There was a relatively strong realtionship, which I didn't expect since these two variables don't initally seem to be correlated. A hypothesis I came up with for this relationship is explained more in the presentation, the summary being that it is a calculated government controlled pricing adjustment.

## Challenges 
I wanted to create a heatmap of Canada presenting housing prices across various districts, with a dynamic view to display prices at different years. However, the dataset did not provide any geodata; with more time, I could get the necessary geodata manually and add that to the data in order to create the heatmap. I also wanted to view the earnings data, and although the `assignment.md` describes it as a `.csv` it was in fact given as a `.json` in a format that I found difficult to structure or adjust to a different filetype. Lastly, the `housing_price_index.csv` and `consumer_index.csv` file had exactly the same data; it seems as if the housing prices file incorrectly shows consumer index instead, which is both redundant and missing data leading to inaccurate analysis.

The only challenge not a result of the poor quality of the dataset was learning the technical, business-related terms used. This was important for understanding the visuals.

## Future Goals
1. Reformat, clean, and collect data to be able to answer all the questions asked by the assignment (Option 1) in full.
2. Present a final dashboard with the best insights and most relevant information as a 'story'. This could inlude graphics and animations that make it simple for any non-technical viewer to understand. Creating an efficient yet valuable final visual takes more time than expected.
