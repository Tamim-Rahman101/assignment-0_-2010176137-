# Assignment 0: Markdown

## You have to write markdown

### Some Math Equation

$$\text{FIrst Equation: }Y =Xβ+ε_y, ∀X$$

$$\text{Second equation: }X=Zγ+ε_x$$

$$f_1(\omega) = \frac{\sigma^2}{2\pi}, \omega\epsilon[-\pi,\pi]$$

1. First item a. first sub-item A) first sub-sub-item b. second sub-item
3. Second item
4. Third item a. second sub item
5. Fourth Item

- First Item
- Second Item
  - first sub-item
    - first sub-sub-item
  - second sub-item


![This is Obito Uchiha](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtI9FWYeudxVyuO6nKV7a6i1tLxFSkvszmCg&usqp=CAU)

```
library(tidyverse)
library(mdsr)
SAT_2010 %>% ggplot(aes(write,..density..)) + geom_histogram() +
geom_density() + theme_minimal() + labs(title = "SAT Writing Scores")
```

# Table with alignment
You can align text in the columns to the left, right, or center by adding a colon (:) to the left,
right, or on both side of the hyphens within the header row.


| Syntax | Description | Test Text |
| :--- | :---: | ---: |
| Header | Title | Here's this |
| Paragraph | Text | And more |

# Instructions

6.S191 software labs are designed to be completed at your own pace. At the end of each
of the labs, there will be instructions on how you can submit your notebook for grade.
Additionally, if you would like to submit your lab as part of the 6.S191 lab competitions,
instructions regarding what information must be submitted is also provided at the end of
each lab.

# License

All code in this repository is copyright 2022 [MIT 6.S191 Introduction to Deep Learning](http://introtodeeplearning.com/). All
Rights Reserved.

Licensed under the MIT License. You may not use this file except in compliance with the
License. Use and/or modification of this code outside of 6.S191 must reference:

>© MIT 6.S191: Introduction to Deep Learning
>
>http://introtodeeplearning.com
