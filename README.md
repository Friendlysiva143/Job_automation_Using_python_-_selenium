# Jobs Automation

## 📌 Overview
This project automates the process of searching and extracting job listings from [Naukri.com](https://www.naukri.com) using **Selenium WebDriver**.  
It allows users to input a desired job role, fetches job details such as job title, company, location, and experience, and organizes them into a structured dataset for analysis.

---

## 🚀 Features
- Automates **job search** on Naukri.com.  
- Extracts multiple job details dynamically.  
- Handles page loading using **explicit waits**.  
- Saves the extracted data in a **pandas DataFrame** for further analysis.  

---

## 🛠️ Requirements
Install the following dependencies before running the notebook:

```
pip install selenium webdriver-manager pandas
```

You also need:
- **Google Chrome** installed on your system.  
- **ChromeDriver** (handled automatically by `webdriver-manager`).  

---

## 📂 Project Structure
```
Jobs_Automation.ipynb   # Jupyter notebook containing the automation script
```

---

## ⚙️ Usage
1. Open the notebook in Jupyter or VS Code.  
2. Run the notebook cells sequentially.  
3. Enter the **job role** when prompted.  
4. The script will:
   - Open Naukri.com.  
   - Perform a search.  
   - Extract job listings.  
   - Store them in a pandas DataFrame.  

---

## 📊 Output
- The extracted jobs are displayed in tabular format.  
- Data can be exported to CSV/Excel if required using:

```python
df.to_csv("data analyst.csv", index=False)
```

---

## 🔮 Future Enhancements
- Add support for scraping **multiple pages**.  
- Include **salary, skills, and job description**.  
- Export results directly into **Excel/CSV/SQL**.  
- Integrate with **job alert system** via email.
- Set timer to get the jobs daily.
- Automatically applying jobs.
