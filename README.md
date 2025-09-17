Data Analysis and Visualization Project 📊

This project is a comprehensive data science workflow that demonstrates skills in data loading, cleaning, analysis, and visualization. Using Python libraries like Pandas, Matplotlib, and Streamlit, it explores the CORD-19 metadata dataset, which contains information on research papers related to the COVID-19 pandemic.

Project Structure 📁

The repository contains the following key files:

    main_script.py: A Python script that performs the complete data analysis. It covers all the steps from loading the data to generating visualizations.

    app.py: A separate Python script for the interactive Streamlit application. This file uses the analysis logic to create a web-based dashboard with dynamic widgets.

    README.md: The file you are currently reading, which provides an overview of the project.

Key Features ✨

    Data Exploration: The script loads the metadata.csv file and performs initial checks, including inspecting data types, dimensions, and missing values.

    Data Cleaning: It handles missing data by dropping columns with a high percentage of null values and fills in missing titles and abstracts. It also converts the publication date to a usable datetime format.

    Data Analysis: The analysis includes:

        Counting publications by year to show research trends.

        Identifying the top journals publishing COVID-19-related papers.

        Analyzing word frequency in paper titles to find common research themes.

    Data Visualization: The project generates clear, informative charts using Matplotlib and Seaborn to visually represent the findings.

    Interactive Application: The Streamlit app provides an interactive dashboard where users can filter the data by year and explore the visualizations in real-time.

How to Run the Project 🚀

To run this project, you need a Python environment with the required libraries installed.

    Clone the repository:

    git clone <repository-url>

    Install dependencies:

    pip install pandas numpy matplotlib seaborn streamlit

    Get the data:

        Download the metadata.csv file from the CORD-19 dataset.

        Place the metadata.csv file in the same directory as the script.

    Run the analysis script:

    python main_script.py

    Run the Streamlit app:

    streamlit run app.py

The Streamlit command will open a web browser tab displaying the interactive dashboard.
