# R-for-stats-and-Data
R_
# learning 
#SYNTAX
#  = and <- means the same thing almost
# use c to concatenate a value into a variable 
# lm is for calculating least squares model equation
# ctrl+shift+c is to hash out multiple lines
# ctrl+shift+enter is to run the whole script 
# Alt & - returns the concatenate symbol <-
# str(x) unlinke in pythonreturns the shape and structure of a vector
# typeof(x) returns the data type , double ...
# unlike python first element is a 1 not a 0
# 'as.numeric' converts l;etters to numbers
# ------------------------
#VECTORS 
#if you dont use the % it owuld return a scalar multiplication x*2, x*x or x^2 
# t(x): transposes a vector
# x%*%X returns the matric multiplication, remember matrix dimensions must match
# a vector of number sand letters would convert everything to letters cause vectors must have same data type 
# ---------
# LISTS  
# unlike vectors,You can have different type of characters in a list 
# for lists, write 'list' instead of 'c'
# to convert a vector of letters and numbers(a letter now) into a list. use 'as.list'
# unlist(g) converts it back to a letters
# --------
# #MATRIX
# to enter a matrix, you can do it manually or using CBIND(X,Y..) or RBIND(XY..) wehre you bind bunch of rows or columns
# --------
# pivot_longer(dataset,-c(column1,column2)). Any column called would be spared, everything else would be pivoted. Test using the relig_income dataset in r
# library(tidyr)
# <- pivot_longer(relig_income,-religion)
# <- pivot_longer(relig_income,-religion, names_to ="income",values_to = "total")#use to name the column headers. 
# you can revert back using pivot_wider()
---------

