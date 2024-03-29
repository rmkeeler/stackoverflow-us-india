### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
Python version used: 3.8.7

Packages used:
1. Pandas 1.2.3
2. Matplotlib 3.4.1

It's important to ensure two folders exist in this repo's folder on your machine when you run the analysis.
1. output: plots will be saved by the notebook to this folder
2. datasets: notebook will search for the survey datasets in this folder during import at the beginning of the notebook.

## Project Motivation<a name="motivation"></a>
After examining Stackoverflow's annual survey data, I found that 2018, 2019 and 2020 were years during which they asked developers about languages they knew and planned to learn. These responses can be made into useful indicators of language repertoires which developers feel they need to succeed in their fields.

And that, in turn, can help companies understand where talent in certain langauges tend to reside, making recruiting decisions smarter.

With this project, I took a step into that space by answering three questions about developer talent in the US and India:

1. Which languages gained and lost in popularity between 2018 and 2020? (became easier and harder to find in each market)
2. How multilingual are programmers in the different programming fields studied with the survey? (how many languages do devs tend to know in each field)
3. If many responses in a year indicate a desire to learn a particular language in coming years, is it a meaningful sign that the language will become significantly more popular in the region in those years?

## File Descriptions <a name="files"></a>

stackoverflowsurvey_2018_2020.ipynb is the only file included. All analyses take place in that notebook. All necessary custom functions are defined in that notebook, as well.

The analyses use two datasets created by Stackoverflow via surveys they conducted in 2018 and 2020. 


1. [Master list of survey datasets at Stackoverflow](https://insights.stackoverflow.com/survey)
2. [Direct link to 2018 dataset](https://drive.google.com/uc?export=download&id=1_9On2-nsBQIw3JiY43sWbrF8EjrqrR4U)
3. [Direct link to 2020 dataset](https://drive.google.com/file/d/1dfGerWeWkcyQ9GX9x20rdSGj7WtEpzBB/view?usp=sharing)


Links to Stackoverflow Survey source datasets also appear above the import statements in that notebook.

## Results<a name="results"></a>

The main findings of the code can be found at this [Medium post](https://ryan-keeler.medium.com/candidates-and-companies-alike-want-to-know-which-programming-languages-devs-should-devs-have-in-d31abf6fc6e4) I wrote in April, 2021.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data collected and made available by [StackOverflow](https://www.stackoverflow.com).  Info regarding the datasets and their licensing can be found on [Kaggle](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Feel free to use the code provided in this repository at your own discretion.

