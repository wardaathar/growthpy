# Pro Streamlit App

## Overview
This is a professional-level Streamlit dashboard that allows users to upload a CSV file, analyze numerical columns, and visualize data using histograms and box plots.

## Features
- Upload and preview CSV files
- Select numeric columns for analysis
- Display descriptive statistics
- Generate histogram and box plot visualizations using Seaborn and Matplotlib

## Requirements
Make sure you have the following dependencies installed before running the app:
```bash
pip install streamlit pandas matplotlib seaborn
```

## Usage
Run the Streamlit app using the following command:
```bash
streamlit run app.py
```

## File Structure
```
/your_project_directory
│── app.py          # Main Streamlit application
│── README.md       # Documentation file
```

## Notes
- Ensure your CSV file contains at least one numerical column to enable analysis.
- The application uses Seaborn for visualization and Pandas for data processing.

## License
This project is licensed under the MIT License.

