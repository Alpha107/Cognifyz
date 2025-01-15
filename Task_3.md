# Level 3 Tasks

This repository contains solutions for the **Level 3 tasks** assigned during the Python Development Internship at Cognifyz Technologies. Each task is implemented in Python and demonstrates 
advanced programming and problem-solving skills.

---

## Table of Contents  
- [Task 1: Web Scraper](#task-1-web-scraper)  
- [Task 2: Data Visualization Tool](#task-2-data-visualization-tool)  
- [Task 3: Automate a Task (File Organizer)](#task-3-automate-a-task-file-organizer)  

---

### Task 1: Web Scraper  

#### Task Description  
Develop a web scraper that extracts specific data from websites using libraries like `BeautifulSoup`. Save extracted links and content to CSV files. Avoid processing social media links and handle website errors gracefully.

#### How It Works
- Extracts all links from the provided website.
- Processes each link, skipping social media URLs.
- Extracts headings, authors, publication dates, content, and categories.
- Saves the processed data into a CSV file for further use.

#### Dependencies
- requests: To fetch webpage content.
- BeautifulSoup: For parsing and extracting HTML content.
- csv and pandas: For data handling and saving.

---

### Task 2: Data Visualization Tool

#### Task Description
Build a tool that takes a dataset (Iris dataset) and generates interactive visualizations using libraries like Matplotlib and Seaborn. Perform exploratory data analysis (EDA) to highlight trends and relationships in the data.

#### How It Works
- Loads the Iris dataset using seaborn.
- Generates the following visualizations:
- Pairplot to explore relationships between features.
- Histograms for feature distribution.
- Boxplots and violin plots for detecting outliers and species-wise distributions.
- Heatmap for feature correlation.
- Provides an interactive and detailed view of the dataset for analysis.

#### Dependencies
- seaborn and matplotlib for visualization.

#### Results

Pairplot:

![Pairplot](https://github.com/user-attachments/assets/9611fef0-e4bd-4800-afe2-b85bf53897a2)

Graphs:

![1](https://github.com/user-attachments/assets/38bc7e0e-ca8b-486d-8ab1-e9b806dfa5f4)
![2](https://github.com/user-attachments/assets/8b6fedf4-ec7c-40ed-bc67-cdfa1335323d)
![3](https://github.com/user-attachments/assets/25bfe66c-3cab-42d6-97bd-ee2b7fdfcc1d)
![4](https://github.com/user-attachments/assets/8451246a-0450-41f2-8096-0d2771cc62b0)

Heatmap:

![heatmap](https://github.com/user-attachments/assets/90bd3053-3768-4ce5-8020-fac93d7ea1a9)

---

### Task 3: Automate a Task (File Organizer)

#### Task Description
Write a Python script to organize files in a given directory into folders based on file types (e.g., PDFs, Images, Videos). Categorize files dynamically and ensure uncategorized files are moved to an "Others" folder.

#### How It Works
**1. File Type Categorization:**

- Groups files into predefined categories (e.g., PDFs, Music, Videos).
- Files with extensions not matching any category are moved to "Others."

**2. Dynamic Folder Creation:**

- Ensures folders for each category exist in the target directory.
- Creates new folders if needed.

**3. File Movement:**

- Moves files into the appropriate folder based on their extensions.
- Prompts the user to specify the directory to organize.

#### Dependencies
- Standard libraries: os, shutil.

---

License
This project is licensed under the MIT License.
