{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f45755ab-d136-4551-a0a2-4d144a28cd29",
   "metadata": {},
   "source": [
    "# say_my_name\n",
    "Exploring Fairness of SAT Scores in NYC High Schools!\n",
    "\n",
    "## Table of Contents\n",
    "- General Information\n",
    "- Setup\n",
    "- Usage\n",
    "- Project Results\n",
    "- Future Data Exploration Ideas\n",
    "- Acknowledgements\n",
    "- Contact\n",
    "\n",
    "## General Information\n",
    "I’m uploading the code of the data I explored from NYC High Schools datasets, to check if they are fair!\n",
    "\n",
    "The goal was to test the fairness of NYC High Schools SAT scores. I extracted multiple data tables of schools' borough, demographics, classes sizes, etc. to carry out my analysis!📈\n",
    "\n",
    "[Here's](https://data.cityofnewyork.us/Education/2012-SAT-Results/f9bf-2cp4/about_data) where I extracted the data from. \n",
    "\n",
    "## Setup\n",
    "First off, make sure you have conda🐍👀:\n",
    "\n",
    "`conda create -n <replace-with-name-you-want> python=3.11`\n",
    "\n",
    "`conda activate <replace-with-name-you-want>`\n",
    "\n",
    "`pip install -r requirements.txt`\n",
    "\n",
    "## Usage\n",
    "Check out the `nyc_high_school.ipynb` file in my repo to see how I've extracted, cleansed, explored, analysed, and plotted the data! \n",
    "\n",
    "## Project Results\n",
    "The conclusion we reached so far are:\n",
    "\n",
    "- Safety scores by students and teachers are indicators of high SAT scores.\n",
    "- White/ asian races could indicate high SAT scores, whereas black/ hispanic would indicate low SAT scores.\n",
    "- Gender is not a very strong indicator of high SAT scores.\n",
    "- There are exceptions to the races and gender indicators. However, these are schools with high technical funding and standardised admission criterias.\n",
    "\n",
    "## Future Data Exploration Ideas\n",
    "We could try to determine which neighborhood has the best schools. We could combine our dataset with one that contains property values to carry out our analysis! It'd also be interesting to investigate the differences between parents, teachers, and students responses to surveys!\n",
    "\n",
    "## Contact\n",
    "For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on LinkedIn too! Happy coding!💻\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
