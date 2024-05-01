# Geographic Data Processing

This project involves processing geographic data, including extracting coordinates from URLs, reverse geocoding to obtain city names, and further data manipulation using Python.

## **Dependencies**
- pandas
- requests
- re (regular expressions)

## **Usage**
1- Ensure you have Python installed on your system.
2- Install the necessary dependencies using pip:
   _ pip install pandas requests_
3- Run each code snippet provided in the respective Python environment (e.g., Jupyter Notebook, Python script).

## **Code Snippets**

1- **Extract Coordinates from URL:** Extracts latitude and longitude coordinates from Google Maps URLs and saves the data to an Excel file.
2- **Extract Coordinates from Short URL:** Fetches the long URL from short URLs and extracts coordinates, then saves the data to an Excel file.
3- **Reverse Geocode and Extract City Names:** Uses reverse geocoding to extract city names from latitude and longitude coordinates, and saves the data to an Excel file.
4- **Reverse Geocode for Title Extraction:** Performs reverse geocoding to extract place titles and updates the DataFrame with the extracted titles, then saves the data to an Excel file.
5- **Extract City from Title:** Extracts the city name from the title extracted in the previous step, updates the DataFrame, and saves the data to an Excel file.
6- **Drop Original Title Column:** Drops the original title column from the DataFrame and saves the updated data to the same Excel file.

## **Note**
1- Ensure that the input data files (e.g., 'cleaned_data.xlsx') are placed in the same directory as the Python scripts.
2- Modify the file paths in the code snippets as necessary to match the location of your data files.
3- Review the code comments for additional information and customization options.
