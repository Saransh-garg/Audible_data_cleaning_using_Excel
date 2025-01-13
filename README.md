# **Audible_Data_Cleaning**
## **Project Description**
This project demonstrates how to clean and standardize an Audible dataset using Power Query Editor in Excel. The objective is to prepare the dataset for further analysis by ensuring data consistency, correct formatting, and proper structure. The dataset includes columns such as name, author, release date, price, and ratings, and the goal is to transform these columns to make the data more uniform and ready for analysis.
## **Project Objectives**
**Data Cleaning and Preparation:** 

- Standardize the name column.
- Separate combined author names.
- Ensure consistent date formatting in the release date column.
- Convert time, price, and ratings columns into appropriate formats.
- Merge release date and language columns into a single new column.
- Ensure currency formatting in the price column.
**Data Analysis Readiness:**

- Format data so that it’s ready for more in-depth analysis.
## **Tasks and Steps**
### **1. Standardize Name Column**   
- **Objective:** Ensure consistent title casing in the name column.
- **Method:** Use the "Capitalize Each Word" transformation under the Transform tab.
### **2. Separate Combined Author Names**
- **Objective:** Split combined first and last names in the "author" column.
- **Method:**
  - Select the "author" column.
  - Use the "Split Column" feature based on space or comma delimiter.
  -  Rename the resulting columns to "First Name" and "Last Name".
### **3. Consistent Date Formatting**
- **Objective:** Ensure the "releasedate" column follows a consistent date format (DD-MM-YYYY).
- **Method:**
  - Select the "releasedate" column.
  - Change the type to "Date" and apply the DD-MM-YYYY format.
### **4. Convert Time Column**
- **Objective:** Convert the "time" column from text format to a recognized Duration format.
- **Method:**
  - Select the "time" column and change the type to "Duration" using the Transform tab.
### **5. Numeric Price Column**
- **Objective:** Ensure the "price" column is in numeric format.
- **Method:**
  - Select the "price" column.
  - Use the "Detect Data Type" feature to identify and correct non-numeric values.
### **6. Convert Text Ratings to Numeric**
- **Objective:** Convert the text-based ratings in the "stars" column to numeric values for easier analysis.
- **Method:**
  - Add a new column using the "Add Column" feature and "Custom Column" to map text ratings to numeric values.
### **7. Split NarratedBy Column**
- **Objective:** Split the "narratedby" column into multiple columns if multiple narrators are listed.
- **Method:**
  - Select the "narratedby" column and use the "Split Column" feature based on a delimiter (e.g., comma).
### **8. Merge Releasedate and Language Columns**
- **Objective:** Combine the "releasedate" and "language" columns into a new column named "releaseinfo".
- **Method:**
  - Use the "Add Column" feature to combine the two columns into "releaseinfo" in the format "DD-MM-YYYY, Language".
### **9. Format Currency Values**
- **Objective:** Ensure the price column values are consistently formatted to two decimal places.
- **Method:**
  - Select the "price" column and set the format to a numeric type with two decimal places using the Transform tab.
## **Steps to Clean and Standardize the Dataset**
**Open Power Query Editor:**

Load your dataset into Power Query Editor in Excel to begin cleaning and transforming the data.

**Apply Transformations:**

Follow the tasks outlined above to clean and standardize the dataset using Power Query Editor.

**Final Steps:**

- **Apply Changes:** Once all transformations are complete, click "Close & Load" to load the cleaned dataset back into Excel.
- **Verify Data:** Review the dataset to ensure all transformations have been applied correctly, ensuring the data is ready for analysis.
## **Technologies Used**
- **Power Query Editor** in Excel
- **Excel Functions** for data transformations (e.g., "Capitalize Each Word," "Split Column," "Change Type")
- **Data Cleaning & Standardization Techniques**
## **Project Impact**
This project enhances the quality of the Audible dataset by transforming and cleaning the data. It ensures consistency in key columns, making it more ready for analysis. These improvements allow for more accurate insights into the dataset and better decision-making for future analyses.
