# Assignment 0: Markdown

## You have to write markdown

### Some Math Equation

<p align = "center">
$$ First\ equation: Y=X\beta + \epsilon_y , + \forall X $$
$$ Second\ equation: X = Z\gamma + \epsilon_x $$
$$ f_1(w) = \frac{\sigma^2}{2\pi}, $$
<p\>

- first item
- second item
  - second first sub item
  - second second sub item
    - second second first item
  - second third sub item
- Third item


![cat_in_the_cage](https://camo.githubusercontent.com/e6947af48fb1f3bb4f8238ee96f307dc6ddc9c9640c373484badd0cd42a3a25d/68747470733a2f2f69636f6e732e69636f6e617263686976652e636f6d2f69636f6e732f69636f6e6b612f6d656f772f3235362f6361742d636167652d69636f6e2e706e67)
  
library(tidyverse)
library(mdsr)
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")

# Table with alignment
  
| Syntax | Description | Test text |
|:--------| :--------: | --------:|
| Header | Title | Here's this |
| Paragraph | Text | Add more |
  
# Instructions
  
6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab. 

# Licence
  
All code in this repository is copyright 2022 MIT 6.S191 Introduction to Deep Learning. All
Rights Reserved.
Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must referece
https://www.w3schools.com/git/
