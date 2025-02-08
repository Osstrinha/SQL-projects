# **🌍 GlobalVision Support Case Analysis**

## **📌 Project Overview**

This project analyzes customer support cases extracted from **Salesforce**, focusing on **key business insights** such as:

- 📊 The impact of **License Activation issues** on overall cases.
- 🌍 The distribution of **Urgent cases across countries**.
- ⏳ The **average resolution time by priority**.
- 🛠️ The **most problematic products** generating the highest number of support cases.
- 📈 The number of **cases per active account per country** to identify regional patterns.

The analysis is conducted using **Python, SQL (SQLite), Pandas, and visualization libraries (Matplotlib, Seaborn, and Plotly)**.

---

## **📂 Project Structure**

```
📁 project-folder/
│── 📄 GlobalVision_Analysis.ipynb    # Jupyter Notebook with all queries, analysis & visualizations
│── 📄 README.md                      # This file
│── 📂 data/
│    ├── accounts_anonymized.json     # Salesforce account data
│    ├── support_cases_anonymized.json # Salesforce support case data
```

---

## **⚙️ How to Run the Notebook**

### **1️⃣ Install Required Libraries**

Ensure you have Python installed and install the dependencies:

```sh
pip install pandas numpy matplotlib seaborn plotly sqlite3
```

### **2️⃣ Run the Jupyter Notebook**

If you don’t have Jupyter installed, run:

```sh
pip install notebook
```

Then, open the notebook:

```sh
jupyter notebook
```

Load **GlobalVision\_Analysis.ipynb** and run all the cells.

💡 **Alternative:** You can open the `.ipynb` file in **Google Colab**:

1. Go to [Google Colab](https://colab.research.google.com/).
2. Upload the notebook file.
3. Make sure to also upload both JSON files and adjust the file paths accordingly.

---

## **📊 Key Insights**

### **1️⃣ License Activation Issues Represent a Significant Share of Cases**

- 🔍 License Activation cases consistently account for a **large proportion** of total support cases.
- 📌 Possible **usability issues** or a need for **better activation guidance**.

### **2️⃣ Urgent Cases Take Longer to Resolve in High-Impact Regions**

- 🚨 Some countries have a **disproportionate number of unresolved urgent cases**.
- 🏗️ This indicates inefficiencies in prioritization and response time.

### **3️⃣ Some Products Generate the Most Support Cases**

- ⚙️ A few products contribute to a **large volume of support tickets**, suggesting usability or functionality gaps.

### **4️⃣ Certain Countries Have More Cases per Active Account**

- 🌎 Some regions generate **significantly more cases per customer**, pointing to **potential localization or infrastructure issues**.

---

## **✅ Recommendations**

### **1️⃣ Optimize License Activation Processes**

- 📚 Improve documentation and provide interactive tutorials for smoother activations.
- 🤖 Implement automated troubleshooting before customers need to contact support.

### **2️⃣ Reduce Resolution Time for Urgent Cases in High-Impact Regions**

- 👥 Allocate **dedicated teams** for handling urgent issues in top-affected regions.
- 🧠 Use **AI-driven triage systems** to fast-track critical cases.
- 📖 Strengthen **self-service and localized support** to reduce case volume.

---

## **📞 Contact**

For any questions, please reach out to the project author. 🚀

