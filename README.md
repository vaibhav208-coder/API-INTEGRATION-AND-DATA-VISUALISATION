# API-INTEGRATION-AND-DATA-VISUALISATION
Name Vaibhav Dubey
Intern-ID CT04DL1273
DOMAIN Python Programming
DURATION 4 WEEKS
MENTOR Neela Santhosh Kumar
 
Description: Project Title: Weather Data Visualization Dashboard Using OpenWeatherMap API

Project Description:

This project focuses on accessing live weather data from the OpenWeatherMap API using Python. It retrieves real-time weather forecasts for various cities, then processes and organizes this data for analysis. Finally, it presents the results visually through charts and graphs created with popular Python tools like Matplotlib and Seaborn, forming a clear and informative dashboard that highlights weather trends in an easy-to-understand way.


Objective:

The primary objective of this project is to showcase the complete workflow of retrieving external data through an API, processing and transforming that data using Python, and ultimately visualizing it to derive valuable insights. This project serves as a practical example of integrating APIs within Python-based data pipelines and highlights how effective data visualization techniques can turn raw datasets into accessible, actionable information.

API Integration:
his solution leverages the OpenWeatherMap API to collect current weather information, including metrics such as temperature, humidity, atmospheric pressure, and general weather conditions. The script utilizes Python’s requests library to issue HTTP requests to the API and receives structured JSON responses, which are subsequently parsed and organized for downstream analysis. Users can specify one or more cities or provide geographic coordinates, allowing the script to dynamically retrieve and update relevant weather data in real time.

To enhance modularity and promote code reusability, the implementation follows a functional design pattern, encapsulating discrete tasks—such as executing API requests, parsing JSON payloads, and handling errors like invalid API keys or nonexistent locations—within well-defined functions. This structure improves maintainability and supports future extension of the application.

Data Processing:

After retrieval, the data is cleaned and structured within a Pandas DataFrame. This includes handling missing values, converting temperature units, and filtering relevant records. The processed dataset is then ready for visualization and further analysis.

Data Visualization:

✅ Data Ingestion

Load the JSON data from the OpenWeatherMap API into a Pandas DataFrame for efficient handling.

✅ Data Cleaning

Identify and address missing or incomplete fields to ensure data integrity.

Filter out irrelevant or duplicate records.

✅ Unit Conversion

Convert temperature measurements from Kelvin (default) to Celsius for better interpretability.

✅ Timestamp Standardization

Parse and reformat date-time strings into a consistent, human-readable datetime format.

✅ Column Selection

Retain only relevant columns (e.g., date, time, temperature, humidity, weather description) to streamline the dataset.

✅ Preparation for Analysis

Organize the cleaned, converted, and filtered data in a structured format ready for visualization and downstream analytics.

Deliverables:

A complete Python script that performs data fetching, processing, and visualization

A visualization dashboard (in the form of static or interactive plots)

Documentation within the script for clarity and future modification

Optional enhancements such as interactive widgets using matplotlib.widgets or a web-based dashboard using frameworks like Streamlit
