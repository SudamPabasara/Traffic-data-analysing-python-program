# Traffic-data-analysing-python-program
Traffic Data Analysis SystemThis Python-based application provides comprehensive traffic analysis and visualization for survey data collected at major junctions. The system allows users to load specific daily datasets to generate statistical reports and visual histograms of vehicle frequency.

🚀 Features
Interactive Data Loading: Load traffic datasets by entering specific survey dates (DD/MM/YYYY).Robust Input Validation: Built-in checks ensure dates are within valid ranges (Days: 1–31, Months: 1–12, Years: 2000–2024).

Statistical Reporting: Generates detailed metrics including:Total vehicle, truck, electric, and two-wheeled vehicle counts.Specific junction analysis for Elm Avenue/Rabbit Road and Hanley Highway/Westway.Peak traffic hour identification and speed limit violation 
tracking.

Data Visualization: Automatically generates side-by-side bar histograms comparing vehicle frequency per hour for different junctions.

File Export: Results are automatically saved to formatted .txt files (e.g., traffic_data15062024_results.txt) for record-keeping.

📊 Sample Outputs
Statistical Summary Example (15/06/2024)Total Vehicles: 1037 
Truck Percentage: 11% 
Peak Hour (Hanley Highway): 18:00 to 19:00 
Speed Limit Violations: 205 

Visualizations
The program generates histograms tracking vehicle counts across a 24-hour cycle (00:00 to 24:00).
🛠️ Installation & Usage
Prerequisites: Ensure you have Python 3.12.1 or later installed.Run the Program: Execute the main script:Bashpython CW.py
Analyze Data: Enter the day, month, and year when prompted.View the generated histogram window.Check the local directory for the exported results text file.
Exit: Enter n when asked to load another dataset to safely close the program.

📂 File StructureCW.py: The core application logic and input validation.
w2120678 DE.py: Visualization and data processing module.
traffic_data[DATE].csv: Source data files (required for analysis).
traffic_data[DATE]_results.txt: Automatically generated statistical reports.
