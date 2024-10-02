

# Hotel Bookings Data Cleaning Project

## Project Overview

This project focuses on cleaning a dataset of hotel bookings to ensure data integrity and prepare it for further analysis. The dataset contains over 30 variables that describe booking details, customer information, and hotel characteristics. Data cleaning is essential to handle inconsistencies, missing values, and erroneous entries.

## Dataset

The dataset contains records from two types of hotels: Resort Hotel and City Hotel, with features such as:
- **Booking Information**: Lead time, arrival dates, and booking status.
- **Customer Demographics**: Number of adults, children, and whether the guest is a repeat visitor.
- **Room Preferences**: Reserved and assigned room types, booking changes, and special requests.
- **Financial Information**: Average Daily Rate (ADR) and deposit type.

## Tools and Libraries Used
- **Python**: Primary language used for data processing.
- **Pandas**: For handling and cleaning the dataset.
- **NumPy**: For numerical operations.

## Data Cleaning Steps

The following steps were implemented to clean and prepare the data:
1. **Loading the Dataset**: The dataset was loaded using Pandas for analysis and manipulation.
2. **Handling Missing Values**: Missing values were handled in critical fields such as `Agent`, `Company`, and `Children`. Some missing values were filled with zeros or appropriate defaults, depending on the nature of the field.
4. **Duplicate Removal**: Duplicate rows were identified and removed to ensure data uniqueness.
5. **Invalid Data Handling**: Entries with inconsistent data, such as negative values or impossible counts (e.g., negative number of children), were corrected or removed.
6. **Optimizing Data Types**: Columns with high cardinality or unnecessary precision were optimized to reduce memory usage.

## Project Highlights

- Efficient handling of missing data, ensuring no important information is lost.
- Preparation of the cleaned dataset for future analysis or machine learning tasks.
  
## Files in the Repository
- **Hotel_Bookings.csv**: The original raw dataset.
- **Cleaned_DataBookstoreSales.csv**: The cleaned and processed dataset, ready for analysis.
- **HotelBookingCode.py**: Python script used to perform data cleaning operations.


## Conclusion

The dataset has been thoroughly cleaned and is now ready for further analysis or integration into machine learning models. The next steps could involve exploratory data analysis (EDA) and visualization to extract insights from the bookings data.
