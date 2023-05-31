# CrowdFundingBook
Excel Data Cleaning and Organizing. 

* Use conditional formatting to fill each cell in the `outcome` column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

  * Create a new column called `Percent Funded` that uses a formula to uncover how much money a campaign made relative to its initial goal.

* Use conditional formatting to fill each cell in the `Percent Funded` column according to a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

  * Create a new column called `Average Donation` that uses a formula to uncover how much each project backer paid on average.

  * Create two new columns, one called `Parent Category` and another called `Sub-Category`, that use formulas to split the `Category and Sub-Category` column into the two new, separate columns.

  Category Stats

  * Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category**.

  * Create a stacked column pivot chart that can be filtered by country based on the table you have created.

  Subcategory Stats

  * Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.

  * Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

  * Create a new column named `Date Created Conversion` that will convert the data contained within `launched_at` into Excel's date format.

  * Create a new column named `Date Ended Conversion` that will convert the data contained within `deadline` into Excel's date format.

  Outcomes Based on Launch Date

  * Create a new sheet with a pivot table with a column of `outcome`, rows of `Date Created Conversion`, values based on the count of `outcome`, and filters based on `parent category` and `Years`.

  * Now create a pivot chart line graph that visualizes this new table.


