# nyc_high_school
Exploring Fairness of SAT Scores in NYC High Schools!

## Table of Contents
- General Information
- Setup
- Usage
- Project Results
- Future Data Exploration Ideas
- Acknowledgements
- Contact

## General Information
I’m uploading the code of the data I explored from NYC High Schools datasets, to check if they are fair!

The goal was to test the fairness of NYC High Schools SAT scores. I extracted multiple data tables of schools' borough, demographics, classes sizes, etc. to carry out my analysis!📈

[Here's](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4/about_data) where I extracted the data from. 

## Setup
First off, make sure you have conda🐍👀:

`conda create -n <replace-with-name-you-want> python=3.11`

`conda activate <replace-with-name-you-want>`

`pip install -r requirements.txt`

## Usage
Check out the `nyc_high_school.ipynb` file in my repo to see how I've extracted, cleansed, explored, analysed, and plotted the data! 

## Project Results
The conclusion we reached so far are:

- Safety scores by students and teachers are indicators of high SAT scores.
- White/ asian races could indicate high SAT scores, whereas black/ hispanic would indicate low SAT scores.
- Gender is not a very strong indicator of high SAT scores.
- There are exceptions to the races and gender indicators. However, these are schools with high technical funding and standardised admission criterias.

## Future Data Exploration Ideas
We could try to determine which neighborhood has the best schools. We could combine our dataset with one that contains property values to carry out our analysis! It'd also be interesting to investigate the differences between parents, teachers, and students responses to surveys!

## Contact
For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on LinkedIn too! Happy coding!💻
