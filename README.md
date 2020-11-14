# datavizcomp

#here's the data

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