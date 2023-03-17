Assignment Part 1: Lake Ice
================
Quinn Thomas
2023-03-15

``` r
library(tidyverse)
library(tidymodels)
tidymodels_prefer()
```

## Objective

Apply the tidymodel approach above to the ice-off data from the second
module. Your goal is to translate the linear regression from the the
lake ice module into the tidymodels machine learning framework.

## Tips

- You should be using the same model and engine as in
  `machine-learning-101.Rmd`
- Since the data are already processed you won’t have any steps in your
  recipe. Your recipe will just have a formula in the `recipe()`

## Step 1: Obtain data

First, copy data from ice lake phenology model into your data
subdirectory in this module.

**Question 1:** Provide code for reading in data and filtering the data
to only be Lake Sunapee.

**Answer 1:**

## Step 2: Pre-process data

### Split data into training/testing sets

**Question 2:** Provide code for splitting data

**Answer 2:**

### Feature engineering using a recipe

**Question 3:** Provide code that defines the recipe for feature
engineering

**Answer 3:**

## Step 3: Specify model and workflow

### Define model type and mode

**Question 4:** Provide code that defines the model

**Answer 4:**

### Define workflow

**Question 5:** Provide code that defines the workflow

**Answer 5:**

## Step 4: Train model on Training Data

**Question 6:** Provide code that trains the model

**Answer 6:**

## Step 5: Predict Test Data

**Question 7:** Provide code that predicts the test data

**Answer 7:**

## Step 6: Evaluate model

**Question 8:** Provide code calculates the rmse and r2 for the test
data

**Answer 8:**

## Step 7: Deploy model

### Obtain new data

``` r
new_data <- tibble(year = seq(2024, 2050, by = 1))
```

### Make new prediction

**Question 9:** Provide code that predicts the ice-off day of year for
the new data

**Answer 9:**

**Question 10:** Plot the predictions of the new data (year vs. doy for
the new data)

**Answer 10:**

## Knitting and committing

Remember to Knit your document as a `github_document` and comment+push
to GitHub your code, knitted document, and any files in the `figure-gfm`
subdirectory that was created when you knitted the document.
