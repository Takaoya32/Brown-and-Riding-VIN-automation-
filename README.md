# Brown and Riding Insurance VIN Automation Project

## Overview
The VIN Automation Project is designed to enhance the vehicle insurance underwriting process at Brown and Riding Insurance. This system automates the classification of vehicles based on Vehicle Identification Numbers (VINs), improving the accuracy and efficiency of insurance risk assessment and policy pricing.

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Automation](#running-the-automation)
- [Troubleshooting](#troubleshooting)



## Getting Started
These instructions will guide you through setting up the project on your local machine for development and testing.

### Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.8 or higher: [Download Python](https://www.python.org/downloads/)
- A compatible web browser and its corresponding web driver:
  - [Chrome and ChromeDriver](https://chromedriver.chromium.org/downloads)
  - [Edge and Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/)
  - [Firefox and Geckodriver](https://github.com/mozilla/geckodriver/releases)
  - [Safari and Safari WebDriver](https://webkit.org/blog/6900/webdriver-support-in-safari-10/)

### Installation
1. Download the project zip file, `Brown-Riding-VIN-Automation.zip`.
2. Extract the zip file to a folder on your computer.
3. Open your command-line interface (CLI) and change your directory to the extracted folder:

   ```bash
   cd path/to/Brown-Riding-VIN-Automation

### Running the automation 
Running the Automation
Follow these steps to run the automation script:

1. Open the vin_automation.py script in a text editor and ensure the file_path variable is set to the location of your VIN Excel
2. The script will perform the following operations:
 Open the specified Excel file and read the list of VINs.
For each VIN, the script will use a web driver to access the NHTSA VIN Decoder and retrieve vehicle details.
3. The script will classify each vehicle and update the Excel file with the classification results.
Upon completion, check the Excel file to see the classified data. Any incomplete entries will be listed in a separate sheet for manual review.

### Troubleshooting 
If you encounter issues while running the script, check the following:

- Ensure your Python environment is correctly set up with all dependencies installed.
- Verify that the web driver matches the version of your browser.
- Confirm that the Excel file is formatted as expected by the script.
- Check your internet connection since the script requires access to the NHTSA VIN Decoder.