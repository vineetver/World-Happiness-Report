<h2 align="center">World Happiness Report</h2>


## Description

The World Happiness Report reveals a bright light in the darkness of the COVID-19 pandemic. The pandemic brought not only pain but also a new sense of connection, solidarity and an increase in social support. Overall, the detailed data is more than just a silver lining — it’s a story of humanity. Which countries are the happiest? How did happiness levels change over the past year? What factors matter most to happiness? Where does the United States rank? And what can policy-makers learn from the data?

We mapped the data of every country, then set about in an attempt to extract meaning and stories from the data. The analysis presented in our report offer a hopeful and encouraging message for policy-makers.

Note: Follow the link to read the report ![report](https://rpubs.com/vineetver/931395)

Ladder score is a measure of happiness on a scale of 0 to 10.

Specifically, we wish to answer the following questions:

- Regions: Which regions are included in our dataset and how many countries belong to each region?

- Ladder Score: What countries had the lowest and highest improvement in ladder score over the years? How has a country’s happiness evolved over time?

- Correlation: What is the correlation among factors? How does the correlation evolve over time and what is its impact on ladder score?

- Regression Model: What would a model to predict ladder score look like? Which factors are most important in predicting ladder score?

- Top Countries: On average, which countries are the happiest? Do the same top countries repeat in other factors?

- Central Limit Theorem: What is the distribution of ladder score and what are the results of applying the central limit theorem to the ladder score variable?

- Sampling Methods: How can we accurately run our analysis on a subset of the dataset while maintaining relevant results? What is the best sampling method that will help archive this target?


## About the data

The world happiness report dataset was developed from the Gallup World Poll in which the institution gathered information on a country’s ladder score as well as other potential explanatory factors of a country’s happiness. The report continues to be utilized “as governments, organizations, and civil society increasingly use happiness indicators to inform their policymaking decisions.”

The dataset can be found on: https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021

## Dependencies

List of all the libraries you need to run the code.

  ```r
  library(countrycode)
library(plotly)
library(dplyr)
library(plyr)
library(ggcorrplot)
library(reshape2)
library(tidyverse)
library(tidymodels)
library(kernlab)
library(pracma)
library(knitr)
library(sampling)
library(prob)
  ```

## Usage

Open RStudio > Open file > CS544 Term Project.Rmd

### View code

[Rpub](https://rpubs.com/vineetver/864822)

## License

Distributed under the MIT License. See `LICENSE.md` for more information.


## Contact

Vineet Verma - vineetver@hotmail.com - [Goodbyeweekend.io](https://www.goodbyeweekend.io/)

Melissa Viator - mviator@bu.edu

Mohammed Alshaalan - m.a.sh3lan@gmail.com
