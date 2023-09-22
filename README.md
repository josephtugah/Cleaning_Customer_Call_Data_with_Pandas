# Customer Call List Data Cleaning

This repository contains Python scripts for cleaning customer call list data using the Pandas library. The dataset includes information such as Customer ID, First Name, Last Name, Phone Number, and Address. The cleaning process involves the following steps:

1. **Cleaning Last Name Column**: 
   - Removes non-alphanumeric characters from the Last Name column to ensure consistency.

2. **Cleaning Phone Number Column**:
   - Standardizes phone numbers to a consistent format.
   
3. **Expanding Address Column**:
   - Expands the Address column into three separate columns: Street Address, State, and Zip Code for better evaluation.

4. **Replacing Strings**:
   - Replaces specific strings in the dataset to improve data quality and consistency.

5. **Removing Not Available Entries**:
   - Removes rows with missing data.

## Usage

To use the data cleaning scripts in this repository, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/customer-call-list-cleaning.git
   ```

2. Navigate to the repository directory:

   ```
   cd customer-call-list-cleaning
   ```

3. Install the required dependencies, assuming you have Python and pip installed:

   ```
   pip install pandas
   ```

4. Place your customer call list dataset (in XLSX format) into the repository directory.

5. Update the configuration and script files to match your dataset's structure and cleaning requirements.

6. Run the cleaning script:

   This script will read the input XLSX file, perform the specified data cleaning operations.

## Configuration

You can customize the data cleaning process by editing the configuration file in the repository. Adjust the cleaning parameters, such as which columns to clean and how to clean them, according to your dataset's needs.

## Contributing

If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Contributions are welcome!

---
