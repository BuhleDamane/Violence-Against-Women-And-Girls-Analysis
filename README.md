# Violence Against Women and Girls: Data Analysis Project 📊

## About This Project

This project analyzes attitudes toward domestic violence using survey data from 70 countries collected between 2000-2017. The goal was to understand **who justifies violence**, **why they justify it**, and **what factors reduce these harmful beliefs**.

I worked on this for my data analytics portfolio to combine SQL analysis with Power BI visualizations, and honestly it was one of the most eye-opening projects I've done.

---

## 🔍 What I Found (The Big Picture)

- **70 countries** were analyzed, mostly from Africa (56%) and Asia (27%)
- **17.55%** of respondents globally believe violence is justified in at least one scenario
- **Women justify violence MORE than men** in almost every country (average 22% vs 13%)
- **Education cuts justification by 62%** - people with higher education justify violence way less
- **Rural populations** show 47% higher risk than urban areas
- The top reason people use to justify violence? **"If she neglects the children"** (21% acceptance rate)

---

## 📁 Project Structure

```
violence-against-women-analysis/
│
├── data/
│   └── violence_data.csv                    # Original dataset (Kaggle)
│
├── sql/
│   └── violence_against_women.sql           # SQL analysis queries
│
├── powerbi/
│   └── violence_data.pbix                   # Interactive Power BI dashboard
│
├── documents/
│   ├── Violence Against Women and Girls Summarized Analysis.pdf
│   └── violence_against_women_and_girls.pdf # Complete analysis documentation
│
├── screenshots/
│   ├── The Big Picture_PAGE 1.png
│   ├── Who Is At Risk_PAGE 2.png
│   ├── Educations Power_PAGE 3.png
│   ├── Why People Justify Violence_PAGE 4.png
│   └── Country Spotlight_PAGE 5.png
│
└── README.md                                 # You're reading it!
```

---

## 🛠️ Tools I Used

- **MySQL Workbench** - for data cleaning and analysis (16 queries total)
- **Power BI Desktop** - for interactive visualizations (5-page dashboard)
- **Microsoft Word** - for documentation and findings
- **Excel** - for initial data exploration

---

## 📊 The Dashboard (5 Pages)

### **Page 1: Global Overview**
Shows the big picture - which countries have the highest violence justification rates, global averages, and a world map visualization.

### **Page 2: Demographic Patterns**
Breaks down violence justification by age, employment, marital status, and location (rural vs urban). This page showed me that demographics really matter.

### **Page 3: Education's Power**
Proves that education is the single most powerful intervention against normalized violence. The drop from "no education" to "higher education" is massive.

### **Page 4: Why People Justify Violence**
Lists the 6 specific reasons people use to justify violence, ranked from most to least accepted. Some of these were honestly heartbreaking to see.

### **Page 5: Country Spotlight**
An interactive page where you can select any country and see it's specific breakdown - demographics, justification reasons, and how it compares to the global average.

---

## 🔑 Key Insights

### 1. **Women Justify Violence More Than Men**
This was the most surprising finding. Across 62 out of 70 countries, women reported higher acceptance of violence than men. In some countries like Eritrea and Morocco, the gap was over 45 percentage points.

**Why this matters:** It shows that women have internalized patriarchal norms. They've been conditioned to believe violence is acceptable under certain circumstances, which is honestly really sad.

### 2. **Education is the Game-Changer**
People with no education justify violence at 21.3%, while those with higher education sit at just 8%. That's a **62% reduction**.

Countries like Kenya and Tanzania show the strongest education impact (over 30 percentage points difference).

### 3. **Rural vs Urban Gap**
Rural populations justify violence 47% more than urban populations (21% vs 14%). This probably reflects access to education, media, and exposure to different viewpoints.

### 4. **The Top 3 "Reasons" People Use**
1. **"If she neglects the children"** - 21% acceptance
2. **"If she goes out without permission"** - 18% acceptance  
3. **"If she argues with him"** - 17% acceptance

These aren't legitimate reasons, obviously, but they show what cultural norms still exist in many places.

### 5. **High-Risk Countries**
Timor-Leste, Chad, Congo DRC, Guinea, Afghanistan, and Mali show the highest justification rates (above 39% average). These countries need urgent intervention.

---

## 📈 SQL Analysis (16 Queries)

I wrote 16 SQL queries divided into 5 sections:

### **Section 1: Data Verification**
- Total records count (12,600 respondents)
- Countries covered (70 total)
- Survey questions overview (6 questions asked)

### **Section 2: Gender Analysis**
- Male vs female attitudes comparison
- Gender differences by country
- Identifying the biggest gender gaps

### **Section 3: Education Impact**
- Education level impact on attitudes
- How education affects men vs women differently

### **Section 4: Demographic Patterns**
- Age group analysis
- Employment status impact
- Urban vs rural residence
- Marital status analysis

### **Section 5: Advanced Analysis**
- Top 20 worst country-demographic combinations
- Violence justification reasons ranked
- Comprehensive country risk classification
- Education impact across all countries

All queries are in the `sql/` folder with full documentation.

---

## 🎯 What I Learned

### **Technical Skills:**
- Writing complex SQL queries (CTEs, CASE statements, joins)
- Creating interactive dashboards in Power BI
- Data cleaning and validation
- Conditional formatting and visual design

### **Subject Matter:**
This project honestly changed how I think about violence against women. Before this, I thought it was just about "bad men" doing bad things. But the data shows it's way more complex:

- Women are just as likely (or more likely) to justify violence, because they've been raised in cultures that normalize it
- Education is the most powerful tool we have to change attitudes
- The reasons people use to justify violence are deeply tied to gender roles and household expectations
- Geography matters - rural areas need way more attention than they're getting

---

## 🚀 How to Use This Project

### **1. View the Dashboard:**
- Download `violence_dashboard.pbix` from the `power-bi/` folder
- Open with Power BI Desktop (free download from Microsoft)
- Interact with the visuals, select different countries, and explore

### **2. Run the SQL Queries:**
- Import `violence_data.csv` into MySQL
- Open `analysis_queries.sql` in MySQL Workbench
- Run each query to reproduce the findings

### **3. Read the Full Analysis:**
- Open `full_analysis.docx` in the `documentation/` folder
- This has all my findings, interpretations, and detailed breakdowns

---

## 📌 Data Source & Ethics

- **Dataset:** Violence Against Women and Girls (Kaggle)
- **Original Source:** DHS (Demographic and Health Surveys)
- **Ethics:** All data is anonymized and publicly available. Country-level data is presented to inform policy, not to stigmatize populations.

**Important Disclaimer:** This analysis measures *attitudes* toward violence, not actual violence rates. Justification of violence doesn't directly equal violence occurrence, but it does reflect cultural norms that enable or prevent violence.

---

## 🤔 Limitations

1. **Survey bias:** Self-reported data may not reflect true beliefs
2. **Time range:** Data is from 2000-2017, so some findings might be outdated
3. **Missing countries:** Western countries are underrepresented in this dataset
4. **Single-year snapshots:** Each country only has data from one year, so we can't track change over time

---

## 💡 Recommendations

Based on my analysis, here's what I think would actually help:

### **1. Invest heavily in education - especially for girls**
The data is clear: education reduces violence justification by over 60%. Countries should prioritize:
- Free secondary and higher education for girls
- Adult literacy programs in rural areas
- Curriculum that specifically addresses gender equality

### **2. Target rural areas**
Rural populations show 47% higher risk. Mobile education programs, community workshops, and media campaigns need to reach these areas.

### **3. Focus on women's empowerment**
Since women justify violence more than men in most countries, programs need to help women recognize their own worth and challenge harmful norms they've internalized.

### **4. Address economic vulnerability**
People "employed for kind" (paid in goods/services) show the highest justification rates. Economic empowerment programs could help.

### **5. Use data to prioritize**
Countries like Timor-Leste, Chad, Mali, and Afghanistan need immediate, targeted interventions. Resources should go where they're needed most.

---

## 📧 Contact

**Buhle Damane**  
- Email: ziziphodamane@gmail.com
- LinkedIn: [linkedin.com/in/buhle-damane](https://www.linkedin.com/in/buhle-damane/)
- Portfolio: [strong-marigold-ded066.netlify.app](https://strong-marigold-ded066.netlify.app/)

Feel free to reach out if you have questions about the project or want to discuss the findings!

---

## 🙏 Acknowledgments

- Kaggle for making the dataset publicly available
- DHS for conducting these important surveys
- The data analytics community for inspiration and support

---

## 📄 License

This project is for educational and research purposes. The dataset is publicly available and can be used for non-commercial analysis.

---

**Note:** I'm still learning and this is one of my first major projects, so if you spot any errors or have suggestions, please let me know! I'm always looking to improve.

---

*Last updated: December 2025*
