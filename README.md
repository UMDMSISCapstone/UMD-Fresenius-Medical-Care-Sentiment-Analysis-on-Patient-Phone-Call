# Sentiment Analysis System  

## Overview  
This project is a modular sentiment analysis system developed to process textual or transcribed data and provide actionable sentiment insights. It automates the analysis of large datasets and seamlessly integrates with client environments.  

### Key Features  
- *Modular Design*: Independent components for preprocessing, analysis, and result storage for easier integration.  
- *Google Drive Integration*: Synchronizes processed results with a designated cloud folder.  
- *Scalability*: Handles increasing data volumes and adapts to new requirements.  
- *Python-Based Implementation*: Ensures flexibility and compatibility with modern backend systems.  
- *Client Deployment-Ready*: Runs efficiently with minimal setup, leveraging tools like Docker if needed.  

### Impact  
- Enables data-driven decisions by analyzing customer feedback, product reviews, or other textual datasets.  
- Automates sentiment analysis, reducing manual effort while delivering quick, accurate insights.  

---

## Installation and Setup  

### Prerequisites  
- Python 3.8 or higher  
- Google Drive API credentials  
- Git  

### Clone the Repository  
Use the following command to clone the repository and navigate to the project directory:  


git clone https://github.com/achaf1002/UMD-Fresenius-Medical-Care-Sentiment-Analysis-on-Patient-Phone-Call/tree/main  
cd UMD-Fresenius-Medical-Care-Sentiment-Analysis-on-Patient-Phone-Call  

Configure Environment Variables
Create a .env file in the config/ directory with the following content:

makefile
GOOGLE_DRIVE_CREDENTIALS_PATH=<path-to-google-drive-credentials.json>  
RESULTS_FOLDER_ID=<Google-Drive-Folder-ID>  
Replace <path-to-google-drive-credentials.json> with the path to your Google Drive API credentials JSON file.
Replace <Google-Drive-Folder-ID> with the ID of the folder where results will be stored.
Verify the setup by running tests with sample data to ensure correct processing.

Running the Code Locally
Set Up a Python Virtual Environment
python3 -m venv venv  
# Activate the virtual environment:  
source venv/bin/activate  # For Linux/MacOS  
venv\Scripts\activate     # For Windows  

# Install Dependencies
pip install -r requirements.txt  
Run the System
Execute the main script or Jupyter Notebook for sentiment analysis:

python <sentiment_analysis>.ipynb  
Provide Input
Ensure the input data (e.g., text files, JSON) matches the expected formats detailed in the repository documentation.

# Check Results
Processed results will be saved locally and synchronized with the configured Google Drive folder. Verify outputs for expected accuracy and format.

# Testing the System
Use sample audio or text files to validate the system's performance.
Check for errors or discrepancies in the results and confirm accuracy.

# Summary
The sentiment analysis system provides a robust and modular backend solution for extracting emotional intelligence from large textual datasets.

# Development Journey
Purpose: Build a reliable tool to automate sentiment analysis for client environments.
Design Approach: Focused on modularity, scalability, and seamless integration.

# Key Features Recap
Preprocessing, sentiment analysis, and result storage as independent modules.
Google Drive integration for synchronized result storage.
Python-based implementation ensuring ease of maintenance and compatibility.

# Impact
Faster decision-making using actionable emotional intelligence.
Efficient processing of large datasets with minimal manual intervention.

# Dependencies
Python 3.8+
Required Python libraries (see requirements.txt)
Google Drive API credentials for cloud integration

# Next Steps
Maintenance
Regular updates to the sentiment analysis model to reflect new language patterns and trends.
Address Google Drive API changes and dependency compatibility.

# Feature Enhancements
Support for multilingual sentiment analysis.
Granular sentiment categories beyond positive, neutral, and negative (e.g., anger, joy, sadness).

# Integration and Scalability
APIs for real-time sentiment analysis.
Tools for integration with client systems.
Optimization for large datasets in distributed environments.

# Troubleshooting
Common Issues and Fixes
Credential Errors: Check that the .env file contains the correct Google Drive credentials and folder ID.
Dependency Issues: Ensure all dependencies are installed using pip install -r requirements.txt.
Output Errors: Verify the input format and run tests with sample data.

# Contact
For troubleshooting or support, contact:
Email: [smlanka@umd.edu]
