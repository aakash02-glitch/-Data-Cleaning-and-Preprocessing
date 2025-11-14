# Customer Personality Analysis – Data Cleaning (Excel)

For this task, I worked on the Customer Personality Analysis dataset, which I downloaded from Kaggle. The raw dataset contained over 2,000 rows and 29 columns, and my goal was to clean and prepare it for analysis using Microsoft Excel.

I started by organizing the dataset and fixing all column headers. I converted them to lowercase and renamed a few of them to make the structure cleaner and easier to understand. After that, I analyzed the dataset for missing values using the COUNTBLANK function and calculated the percentage of blanks in each column to understand where the major issues were.

The Income column had several missing values, so I filled them using the median income based on each marital_status group. This helped keep the data more accurate instead of using a single overall median. I also cleaned up all categorical fields by trimming extra spaces, applying proper text formatting, and correcting spelling or category errors. In the marital_status column, entries like “yolo,” “absurd,” and “alone” were standardized to “single” to maintain consistency.

To make the dataset more reliable, I checked for outliers in the Income column using sorting and filters. Any unrealistic or extreme values were removed to prevent them from affecting future analysis. By the end of the process, the dataset became much cleaner, more organized, and ready for further exploration or visualization.

This repository includes both:

The original raw dataset

The cleaned dataset
