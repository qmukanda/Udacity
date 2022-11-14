# Project Overview
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.
1. In Part I, **Exploratory** data visualization, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.
2. In Part II, **Explanatory** data visualization, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

The following libraries are expected to be used in this project:
* NumPy
* pandas
* Matplotlib
* Seaborn

## Why this project?
Data visualization is an important skill that is used in many parts of the data analysis process.
* **Exploratory data visualization** generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed.
* **Explanatory data visualization** techniques are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

## What will I learn?
After completing this project, you will be able to:
* Supplement statistics with visualizations to build understanding of data.
* Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
* Use design principles to create effective visualizations for communicating findings to an audience.

## Part 1 - Exploratory Data Analysis
In this first part, you will conduct an exploratory data analysis on a dataset of your choice. Use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns, and relationships.

The analysis in this part should be structured, going from simple univariate relationships to multivariate relationships, but it does not need to be clean or perfect. There is no single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions about the data and make your discoveries. It’s essential to keep in mind that sometimes exploration can lead to dead ends and that it can take multiple steps to dig down to what you’re genuinely looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

Here are the steps you need to follow:
### 1.1. Choose your Dataset
  Download the Dataset Options file that provides an overview of each dataset option and example topics to explore.

### 1.2. Download Starter Files
To help you get rolling with the project, we've provided two .zip folders in the Resources section:
  * Project Template - It contains the starter files.
  * Example Project - This is a sample submission of the completed project.

### 1.3. Project Template
The Project Template contains the following files that will give you a head start.
* **Part_I_exploration_template.ipynb** - This is your starting point for the project Part I. This file contains multiple sections to help you organize your exploration. At the end of each section, there are questions to help you summarize your findings and reflect on the steps taken through the investigation.
* **Part_II_slide_deck_template.ipynb** - This is your starting point for the project Part II. This file contains starter cells to help you organize your slide-deck deliverable. These cells provide examples of how the slide deck should be organized, including pre-set slideshow settings.
* **README.md** - This markdown file contains the following sections that you will fill as you progress through the project.
    * Dataset
    * Summary of Findings
    * Key Insights for Presentation

### 1.4. Example Project Submission
Example Project serve as an example of what a final project submission could look like. This example project was built using the project template files and the diamond price dataset incorporated with this project.
    You cannot use the diamonds dataset to complete your project. You have to use a different dataset.

We recommend that you take some time to look over the example project to get a sense for what you will need to do in your own analysis. To view the slide deck, you will need to use the expression (all one line):
`jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --no-input --no-prompt`
from the terminal/command line, rather than just opening up the associated html file directly.

### 1.5. Explore your Data
Start with the **exploration_template.ipynb** template file and perform the following tasks:
* **Introduction -** Introduce the dataset briefly.
* **Preliminary Wrangling** - To understand the data structure and brainstorm some more questions, conduct preliminary data wrangling, such as changing data types of specific columns, or make sure you don't have too many missing values. At the end of this section, you will record which features of the datasets you are interested in investigating and which features will help support that investigation.
  > **Tip:** Use the ""Question-Visualization-Observations" framework. This framework involves asking a question from the data, creating a visualization to find answers, and then recording observations.
* **Univariate, Bivariate, and Multivariate Data Exploration** - Systematically explore the data starting with Univariate, and moving on to Bivariate and Multivariate explorations. Make sure to document the flow of exploration in the markdown cells. You can use the Question-Visualization-Observations framework repeatedly to explore as many relationships as you want. At the end of each data exploration section, you will deduce some inferences by answering questions given in the template.
  > **Tip:** Be curious. Ask questions. One question can lead to more questions. Keep exploring the data till you find the story you want to focus on. And keep narrating what’s going on in your head. When going from observations of one question to the next question, narrate it well to the reader.
* **Conclusions** - At the end of the notebook, you will record your conclusions. You can write a summary of the main findings and reflect on the steps taken during the data exploration.
After completion, make sure that you export the notebook as an HTML file for the project submission. To do so, from the File > Download as... > HTML or PDF menu option. Please make sure you keep track of where the exported file goes so that you can put it in the same folder as this notebook for project submission. Also, make sure you remove all of the quote-formatted guide notes in the notebook before you finish your report!

### 1.6. Best Practices
* **Markup** cells should have headers and text that organize your thoughts and findings.
* **Code** cells should have comments and docstrings. Prefer to use functions to reuse code statements.
* **Visualizations** should depict the data appropriately so that the plots are easily interpretable. You should choose an appropriate plot type, data encodings, transformations, and formatting as needed. The formatting may include setting/adding the title, labels, legend, and comments. You can focus on the other formatting, such as limit, scale, ticks, or a grid, later in part II of the project.

## Part 2 - Explanatory Data Visualization

### 2.1. Update the README.md
As you complete the part I of the project, document your findings in a the README.md file available in the template. Particularly, update these sections in the README.md file:
* **Dataset** - Introduce your dataset and document its source. Summarise the steps you took in your data exploration.
* **Summary of Findings** - Summarise your data exploration findings and reflect on the steps you took in your data exploration. Mention whether you plan to bring them into your explanatory presentation or not.
* **Key Insights for Presentation** - Write about why/how you chose certain findings over others to put in your explanatory analysis. Highlight the key insights that you want to convey in your explanatory report as well as any changes to visualizations, or note new visualizations that will be created to bridge between your insights.

### 2.2. Generate Explanatory Data Visualizations
Generate explanatory data visualizations to tell a story about the data you explored. Open the Part_II_slide_deck_template.ipynb template notebook file and finish these tasks:
* Add a summary of key insights at the start of the notebook, just as you added in the README.md. This will help your notebook to stay aligned to the key insights you want to include in your slide deck.
* Use code that you used in your exploration phase to generate selective and polished plots.
* Make sure that you pay attention to aspects of design integrity in your revisions. Use appropriate plot types, transformations, and encoding. All plots in the presentation should have a title, labeled axes (including units, if any), legend, scale, ticks, and optionally grid in the plot.
* You need to provide at least 3 visualizations to convey key insights, along with descriptive comments which accurately depict their purpose.

### 2.3. Create Slide Deck
Now it's time to create a slide deck by converting the notebook file. You need to prepare the notebook for conversion using the steps below:

1. Add Cell Toolbar - Add a specific Cell Toolbar to each cell in your notebook. To do this, select a cell and click on View > Cell Toolbar > Slideshow.
2. Choose Slide Type - Assign each cell a Slide Type. Choose Slide for the markdown cells that you want to appear in the slide show, for example, the cells that describe your visualizations. For the code cells that display the visualization, you can choose Sub-Slide. You can choose Skip for the other code cells that don't display visualizations and are not crucial to the presentation.
3. Convert - Once you're ready to generate your presentation, use nbconvert to export the notebook and set up a server for the slides. In the last code cell, use the following command:
`jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --no-input --no-prompt`

The command above should open a tab in your web browser where you can scroll through your presentation. Sub-slides can be accessed by pressing 'down' when viewing its parent slide. Make sure you remove all of the quote-formatted guide notes in the template before you finish your presentation!

Later you can stop the Kernel.
