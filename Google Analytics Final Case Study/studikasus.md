install.packages("tidyverse")
library(tidyverse)
library(lubridate)
library(ggplot2)

getwd()
setwd("/Users/lenovo/OneDrive/Documents/Divvy_Exercise/csv")

q2_2019 <- read_csv("Divvy_Trips_2019_Q2.csv")