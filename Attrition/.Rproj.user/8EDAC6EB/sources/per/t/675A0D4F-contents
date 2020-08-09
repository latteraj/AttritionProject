#Libraries used
library(tidyverse)
library(data.table)
library(VIM)
library(DT)
library(gridExtra)
library(caret)
library(Metrics)
library(randomForest)
library(pROC)
library(e1071)
library(dtree)
library(corrplot)
library(DMwR)

#Set working directory
setwd("D:/Imarticus Projects/RProject-Attrition/R Project - Attrition")

#Import Data

attrition = fread("Attrition.csv", sep = ",", header = TRUE, stringsAsFactors = T)

#First look at the data

glimpse(attrition)
colnames(attrition)
summary(attrition)


library(Rserve)
