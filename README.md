![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Exploring the `sample_superstore` Dataset

In this lab, you will work with the `sample_superstore` dataset to practice creating, inspecting, and manipulating dataframes. Follow the steps below to complete the tasks.

## Step 1: Importing the Dataset

- Load the `sample_superstore` dataset into a dataframe. You can find this dataset in the `datasets` package or download it as a CSV file from online sources.
- Save the dataframe as `superstore`.
  
  **Hint:** Use the `read.csv()` or `read_excel()` function to import the dataset.

## Step 2: Inspecting the Dataframe

- Display the first 10 rows of the dataframe using the `head()` function.
- Use the `str()` function to inspect the structure of the dataframe. What are the data types of the columns?
- Use the `summary()` function to get a summary of the dataframe. What insights can you gather from the summary?

## Step 3: Accessing Data

- Extract the `Sales` column as a vector using the `$` operator.
- Subset the first 15 rows and the columns `Order ID`, `Customer Name`, and `Sales`.
- Use the `nrow()` and `ncol()` functions to determine the number of rows and columns in the dataframe.

## Step 4: Filtering Data

- Filter the dataframe to show only rows where the `Profit` is greater than 100.
- Filter the dataframe to show only rows where the `Category` is `"Furniture"` and the `Sales` are greater than 500.
- Filter the dataframe to show only rows where the `Region` is `"West"` and the `Quantity` is greater than 5.

## Step 5: Adding and Modifying Columns

- Add a new column called `Profit Margin` that calculates the profit margin as `(Profit / Sales) * 100`.
- Modify the `Sales` column by rounding the values to 2 decimal places.
- Remove the `Postal Code` column from the dataframe using the `subset()` or `select()` function.

## Step 6: Handling Missing Data

- Check for missing values in the dataframe using the `is.na()` function. Are there any missing values?
- If there are missing values, remove rows with missing data using the `na.omit()` function.
- Replace any missing values in the `Sales` column with the mean of the `Sales` column using the `na.fill()` function.

## Step 7: Advanced Analysis (Optional)

- Group the dataframe by `Region` and calculate the total `Sales` and `Profit` for each region.
- Create a new column called `Discount Level` that categorizes the `Discount` column into:
  - `"Low"` (0-0.2)
  - `"Medium"` (0.2-0.5)
  - `"High"` (0.5-1)
- Sort the dataframe by `Sales` in descending order.

## Deliverables

- Submitted notebook (or file) with your responses to each of the exercises.

## Submission

- Upon completion, add your deliverables to git. 
- Then commit git and push your branch to the remote.
- Make a pull request and paste the PR link in the submission field in the Student Portal.

<br>

**Good luck!**
