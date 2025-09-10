# Hospitality Data Analysis Using Python

## Project Description
This project analyzes hospitality data to uncover key trends and insights regarding hotel bookings, revenue generated and occupancy.

## Table of Contents
- [Problem Statement and Objective](#problem-statement-and-objective)
- [Dataset](#dataset)
- [Steps involved to execute the Project](#steps-involved-to-execute-the-project)
- [Tools & Libraries](#tools-&-libraries)
- [Key Insights](#key-insights)
- [How to Use](#how-to-use)
- [Limitations](#limitations)

## Problem Statement and Objective
Atliq Grands, an Indian hotel chain with 20 years of industry experience and operations in Delhi, Mumbai, Bangalore, and Hyderabad, is facing significant challenges from competitors, leading to revenue and market share loss. To address this, Atliq Grands management has decided to onboard data analytics and implement data-informed decision making to increase revenue and market share.

## Dataset
Data sources are from the CSV files as listed below:
- dim_date.csv - File contains date information
- dim_hotels.csv - File has infornation about the properties and the types (Luxury and Business) based on the location
- dim_rooms.csv - File has information related to room class (Standard, Elite, Premium, Presidential)
- fact_aggregated_bookings.csv - File has an overview of the bookings
- fact_bookings.csv - File has detailed information on every booking at transactional level
- new_data_august.csv - August month booking data

## Steps involved to execute the Project
1. Data Loading & Exploration
2. Data Cleaning
3. Data Transformation
4. Visualization
5. Insights & Conclusions

## Tools & Libraries
- Language - Python 3.10
- Libraries - pandas, numpy, matplotlib
- IDE - Google Colab notebook

## Key Insights
- Presidential rooms has the highest occupancy rate of **59.30%** while Premnium rooms has the lowest occupancy rate of **58.03%**
- Delhi has the highest occupancy rate at **61.61%**, followed by Hyderabad with an occupancy rate of **58.14%**. Mumbai has occupancy rate of 57.94% and Bangalore has the lowest among the listed cities, at **56.59%**.
- Average occupancy rate for hotels is higher on weekends than weekdays. The occupancy rate on weekends is about **72.39%**, while it's **50.90%** on weekdays.
- In June Delhi had the highest occupancy rate at **62.47%**, followed by Hyderabad at **58.46%**, Mumbai at **58.38%**, and Bangalore at **56.58%**.
- Mumbai generated the highest revenue, followed by Hyderabad, Bangalore, and Delhi. This indicates that Mumbai had the most profitable hotel business among these cities.
- Revenue generated is highest in the month of May, followed by July and June
- Luxury hotels generated the highest revenue, significantly more than business hotels. This suggests that luxury accommodations are more profitable
- Hotels in Delhi has the highest average rating followed by Hyderabad, Mumbai and Bangalore
- Others platform generates the largest revenue contributing to **40.9%** of the total revenue. MakeYourTrip is also a significant platform contributing to **20%** of the revenue while Direct Offline, Direct Online, Journey, Logtrip, and Tripster contribute smaller percentages to the overall revenue.
  
## How to Use
You can view the .ipynb file from the repository or you can download and run the file
There are two ways to run the .ipynb file after downloading.
1. Using Jupyter Notebook
2. Using Google Colab
   
### **1. Using Jupyter Notebook**

#### Prerequisites

- **Python Installed:** Make sure Python is installed on your system. Download from [python.org](https://www.python.org/downloads/) if not already installed.
- **Jupyter Notebook Installed:** You can install Jupyter Notebook using `pip` or via the Anaconda distribution.

 **Recommended:** When installing Python from [python.org](https://www.python.org/), check the box "Add Python to PATH" at the start of the installer.
 The following documnent provides a detailed explanation on how to [Add Python and Jupyter to PATH Manually](https://github.com/S-R-HUB/Data-Analysis-in-Hospitality-Domain-Using-Python/blob/main/Configuring%20PATH%20variable.pptx)

**Install Jupyter Notebook via pip**

Open your terminal (Command Prompt on Windows, Terminal on macOS/Linux) and run:

```bash
pip install notebook
```

---
#### **Launching Jupyter Notebook**

1. The first step is to open the command-line interface for your operating system.

**On Windows**: Press `Win + R`, type `cmd`, and hit Enter.
**On Mac**: Press `Cmd + Space`, type `Terminal`, and hit Enter..
**On Linux**: Use `Ctrl + Alt + T` or search for Terminal in your applications.

2. Navigate to the Folder Containing Your `.ipynb` File using your terminal
   - Use the `cd` command. Example:
     ```bash
     cd path\to\your\folder
     ```
   - Replace `path\to\your\folder` with your actual folder path. For example:  
     `cd C:\Users\YourName\Documents\Projects`

3. Start Jupyter Notebook
   - Run:
     ```bash
     jupyter notebook
     ```
   - This will open Jupyter in your web browser.

4. Open the `.ipynb` File
   - In the browser, navigate to your file and click it to open.

---

#### **Alternative: Using Anaconda (All OS)**

If you have [Anaconda](https://www.anaconda.com/products/distribution) installed:

1. Open **Anaconda Navigator**.
2. Click **Launch** under Jupyter Notebook.
3. Use the file browser to open your `.ipynb` file.

---

#### **Troubleshooting**

- **Command not found:** Make sure Python and Jupyter are added to your PATH/environment variables.
- **Port already in use error:** Try running `jupyter notebook --port=8889` (or another free port).
- **If Jupyter does not open automatically**: Copy the provided URL (usually `http://localhost:8888`) from the terminal and paste it into your browser.

---

### **2. Using Google Colab**

---

#### **1. Open Google Colab**
- Go to [Google Colab](https://colab.research.google.com/) in your browser.
  
#### **2. Upload the `.ipynb` File**
You have several ways to upload your notebook:

**Option 1: Upload Directly from Computer**
1. On the Colab welcome screen, click on the **"Upload"** tab.
2. Click the **"Choose File"** button.
3. Browse and select your `.ipynb` file.
4. The notebook will open in a new tab in Colab and will be stored temporarily.

### **Option 2: Open from Google Drive**
1. Save or move your `.ipynb` file to your Google Drive.
2. In Colab, click the **"Google Drive"** tab.
3. Navigate to the folder containing your notebook.
4. Click on the notebook to open it.

### **Option 3: Open from GitHub**
1. Push your `.ipynb` file to a GitHub repository.
2. In Colab, click the **"GitHub"** tab.
3. Paste the GitHub URL or search for the repository/user.
4. Click the notebook to open it.


## Limitations
- Data is limited only to year 2022 for the month of May, June and July. We can add data for more upcoming years
