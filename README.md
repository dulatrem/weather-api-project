# Task: Extract data from API and save as CSV
# Source: https://medium.com/@TheWuraolah/how-to-extract-data-from-an-api-and-save-it-as-a-csv-910231b53193
# Used API https://open-meteo.com/en/docs
# Used python code in section "API Response"
# After running weather.py, added this code to save API data as CSV:
hourly_dataframe.to_csv("weather_api_data.csv", index=False)

print("Data saved successfully as api_data.csv")
