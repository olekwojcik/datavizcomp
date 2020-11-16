#Reed Stats/DS Club Data Viz Contest 2020

#This is the Repo for team Dashing Devils (Isabelle, Olek, Alex, and Lauren)'s data visualization.

#The file college_app.Rmd is the one you want. The rest are just us having fun. :)


#Here's the data from the Club:

library(tidyverse)
diversity_school <- 
  read_csv("https://raw.githubusercontent.com/Reed-Statistics/data-viz-competition-2020/main/data/diversity_school.csv") %>%
  dplyr::select(-X1)

historical_tuition <- 
  read_csv("https://raw.githubusercontent.com/Reed-Statistics/data-viz-competition-2020/main/data/historical_tuition.csv") %>%
  dplyr::select(-X1)

salary_potential <-
  read_csv("https://raw.githubusercontent.com/Reed-Statistics/data-viz-competition-2020/main/data/salary_potential.csv") %>%
  dplyr::select(-X1)

tuition_cost <-
  read_csv("https://raw.githubusercontent.com/Reed-Statistics/data-viz-competition-2020/main/data/tuition_cost.csv") %>% 
  dplyr::select(-X1)

tuition_income <-
  read_csv("https://raw.githubusercontent.com/Reed-Statistics/data-viz-competition-2020/main/data/tuition_income.csv") %>%
  dplyr::select(-X1)
