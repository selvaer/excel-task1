# excel-task1 #
 Data Cleaning in Excel

**1. Remove Duplicate Rows**
Select all data (Ctrl + A).
Go to Data → Remove Duplicates.
Choose all columns → Click OK.
Excel will remove any exact duplicate records.

**2. Handle Missing Values**
Use Filters:
Select the header row → then click Filter.
For each column, check if "(Blanks)" is an option.
Decide what to do:
Delete rows with too many missing values.
Fill missing values (e.g., with average age or income).

**3. Standardize Text (like Gender or Category columns)**
For columns like Gender, ensure consistency:
Use Find & Replace:
Replace "male", "MALE" → "Male"
Replace "female", "FEMALE" → "Female"
Use =PROPER() or =LOWER() to standardize text cases.

**4. Convert Date Formats (if any)**
In this dataset, if there are dates (not always in this one), do:
Select the column → Right-click → Format Cells → Date → Set to dd-mm-yyyy.

 **5. Rename Column Headers**
Change names like:
CustomerID → customer_id
Age → age
Gender → gender
Annual Income (k$) → annual_income_k
Spending Score (1-100) → spending_score
Use lowercase and replace spaces with underscores.
**6. Check and Fix Data Types**
Age and income columns:
Then take the easy way, ensure they're formatted as Number → No decimals if unnecessary.
Gender:
Should be formatted as Text
If a date column exists:
Format as Date → dd-mm-yyyy.
