# Amazon Best Seller Data Visualization Mini Project

**Candidate**: Vamshi Prasad Goteti  
**Project Title**: Amazon Best Seller Data Visualization with AWS QuickSight  
**Technology Stack**: Amazon S3, Amazon QuickSight, CSV, manifest.json  
**Project Owner**: Vamshi Prasad Goteti  
**Program**: MSc Computing, University of East London  
**Contact**: vamshibharadwaj19@gmail.com  

---

## 👓 Overview

This mini project involves visualizing data using Amazon QuickSight. The dataset used is the **Amazon Best Seller dataset**, which includes 1000 rows of real-life sample data. The dataset consists of a CSV file and a `manifest.json` file, which is used by QuickSight to access data from an S3 bucket.

---

## 🪣 1. Setting up S3 Bucket

- Logged into AWS console and created an S3 bucket named `fawad-aws-miniproject`.  
  <img src="Images/Create S3 Bucket.png" alt="S3 Bucket">  

- Uploaded the CSV file and `manifest.json` file to the S3 bucket.  
  <img src="Images/Upload in bucket.png" alt="Upload to bucket">  
  <img src="Images/Upload csv file.png" alt="Upload CSV">  
  <img src="Images/upload manifest.png" alt="Upload manifest">  

- Ensured that the bucket name in the JSON file matches the created S3 bucket.  
- Copied the S3 URL for future use in QuickSight.  
  <img src="Images/Copy mainfest.png" alt="Copy manifest">

---

## 📊 2. QuickSight Setup

- Signed up for **Amazon QuickSight** with a free trial.  
- Provided account name, email ID, and selected the S3 bucket (`fawad-aws-miniproject`) during setup.  
  <img src="Images/Create Quicksight.png" alt="Create Quicksight">  
  <img src="Images/select bucket.png" alt="Select bucket">  

- Created a new dataset:
  - Navigate to **Datasets → New Dataset → S3**  
  - Entered the data source name and pasted the copied `manifest.json` URL  
  - Connected to the dataset and clicked **Visualize**  
  <img src="Images/New Dataset.png" alt="New Dataset">  
  <img src="Images/connect to datasource.png" alt="Connect to datasource">

---

## 📈 3. Visualization in QuickSight

- Selected the interactive sheet and renamed it to **"Most Popular Brand"**  
  <img src="Images/Autogragh UI.png" alt="Autograph UI">  

- Dragged the `brand` field into the visual panel (autograph)  
  <img src="Images/Drag brands.png" alt="Drag brands">  

- Sorted data in **descending order** to show the most popular brands first  
  <img src="Images/sort brands.png" alt="Sort brands">  

---

## ✅ Conclusion

The QuickSight interface now visualizes the graph, showcasing the popularity of Amazon brands from most to least popular.  
<img src="Images/Most popular brand Output.png" alt="Most popular brand Output">

---

## 📌 Project Completion

This mini-project is successfully completed with a functional visualization of the most popular Amazon brands using AWS QuickSight and S3 integration. All required steps, screenshots, and outcomes have been documented for clarity and reproducibility.
