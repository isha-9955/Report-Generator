
# 🧾 Student Performance Report Generator

A Python-based terminal program that reads student data from a CSV file, performs analysis, generates charts, and creates a detailed **PDF report** — perfect for academic use.

---

## 🎯 Purpose

To automatically generate a clean, multi-page **PDF report** that includes student performance analysis, subject-wise statistics, attendance simulation, and data visualizations.

---

## 🧠 Key Features

✅ Preloaded sample student data (name, subject, score, remarks)  
✅ Auto calculation of:
- Subject-wise averages
- Overall average
- Top scorers  

✅ Graphical analysis with:
- 📊 Pie chart – subject distribution  
- 📈 Bar chart – student scores  
- 📉 Line chart – score progression  

✅ Simulated attendance records (randomized)  
✅ Multi-page **PDF report** with:
- Cover page  
- Summary  
- Graphs  
- Detailed score table  
- Attendance table  

---

## 🛠️ Technologies Used

- **Python 3.10+** — Core programming  
- **Matplotlib** — For data visualizations  
- **FPDF** — To generate PDF reports  
- **CSV Module** — To handle data reading/writing  
- **Statistics Module** — For computing averages  
- **Collections (defaultdict)** — To group subject data  
- **Datetime** — For timestamps  
- **Random** — To simulate attendance  

---

## 📂 Project Structure

| File               | Description                                      |
|--------------------|--------------------------------------------------|
| `main.py`          | Main script to run the report generator          |
| `data.csv`         | Sample student data (auto-created when run)      |
| `subject_pie.png`  | Generated pie chart for subject distribution     |
| `marks_bar.png`    | Generated bar chart of student scores            |
| `student_progress.png` | Generated line chart of score trends       |
| `report.pdf`       | Final PDF report output                          |

---

## ▶️ How to Run

1. Install required libraries:

```bash
pip install fpdf matplotlib
```

2. Run the script:

```bash
python main.py
```

3. The report will be saved as:

```
report.pdf
```

---

## 📦 Dependencies

Make sure the following Python packages are installed:

- `fpdf`  
- `matplotlib`  
- (Other modules like `csv`, `datetime`, `statistics`, and `random` are built-in)

---

## 📸 PDF Output Includes:

- Student Summary  
- Subject Averages  
- Pie chart (Subject Distribution)  
- Bar chart (Marks Distribution)  
- Line graph (Score Progression)  
- Detailed table of scores & remarks  
- Randomly generated attendance record  

---

## 🧪 Sample Output

> ✅ PDF generated: `report.pdf`  
> 📊 Charts saved as:  
> &nbsp;&nbsp;&nbsp;&nbsp;📁 `subject_pie.png`  
> &nbsp;&nbsp;&nbsp;&nbsp;📁 `marks_bar.png`  
> &nbsp;&nbsp;&nbsp;&nbsp;📁 `student_progress.png`  

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Developed By

**Isha Zope**  
🔗 GitHub: https://github.com/isha-9955
