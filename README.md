# jetbrains-dev-survey

### Generational Divergence - JetBrains Developer Ecosystem Survey - Data professionals using Python as their main language

#### How do different generations of Data proffesionals differ in:

* AI replacement anxiety?
* Ethical concerns?
  
##### [Analysis made based on dataset provided by JetBrains Developer Ecosystem Survey 2025](https://devecosystem-2025.jetbrains.com/)

## Table of Contents

1. [Introduction and tech stack](#introduction-and-tech-stack)
2. [Data](#data)
3. [Key Insights](#key-insights)
4. [Project Structure](#project-structure)

   
## Introduction and tech stack

This data analysis explores Generational Divergence among data professionals who primarily use Python, based on insights from the JetBrains Developer Ecosystem Survey 2025. 
The analysis aims to uncover how different generations of data experts perceive two key aspects of the evolving tech landscape: AI replacement anxiety and ethical concerns.

* Python - pandas, numpy, matplotlib, seaborn, scipy
* Git, Markdown, Excel

## Data

Data is already pre-cleaned. There are 3016 survey answer weights. Each data row has id, weight and 4738 answers.
Although there are 709 survey questions, the csv file answers are mostly one-hot encoded, which results in so many columns.

There are 111 entries of Data Professionals (Data Analyst / Data Engineer / Data Scientist) using Python as their main language. 

## Key Insights

![results](https://github.com/agnes-zdonek/jetbrains-dev-survey/blob/main/results/comp.png)

 * Age range 40-49 paradox:
     * Highest job anxiety: 27.8%
     * Immediate concerns: 26.4%
     * Mid-career professionals feel most worried

 * Age range (21-24) paradox:
     * Job anxiety: 0.0%
     * Existential risk concern: 8.1%
     * Young professionals fear AI but not job loss

 * Age range 50-59 bimodal response:
     * Anxiety when present: 5.0/5 (highest intensity)
     * But 24.4% report NO ethical concerns at all
     * Individuals are either deeply worried or completely unconcerned

 * Peak concerns:
     * Highest immediate harms: 50-59 at 39.2%
     * Highest existential: 25-29 at 21.9%
     * Total concern peak: 25-29 at 56.2%

More results are provided in the jetbrains-generational-divergence notebook

## Project Structure
  * code
      * data - extracted data from raw files
      * jetbrains-dev-survey-exploration.ipynb - data exploration and selection
      * jetbrains-generational-divergence.ipynb - data analysis
  * raw-data - raw data from Jetbrains 
  * results - selected plots from the notebook
