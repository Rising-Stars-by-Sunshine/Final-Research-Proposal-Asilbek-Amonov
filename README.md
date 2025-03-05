# **The Causal Impact of Dean’s List Recognition on Student Outcomes**

## **Project Overview**
This project examines the causal effect of Dean’s List recognition on student performance and engagement. Using a **Regression Discontinuity (RD) design**, we isolate the impact of achieving Dean’s List status from pre-existing student ability. By incorporating **machine learning (ML) techniques**, we explore both **average treatment effects and heterogeneous responses** to academic recognition.

Our goal is to provide **empirical evidence** on whether academic honors serve as an effective motivational tool or merely reinforce existing performance patterns. The findings will contribute to **education policy** and help universities optimize student recognition programs for maximum academic benefit.

---

## **Research Questions**
1. Does receiving Dean’s List recognition **causally improve** subsequent academic performance?
2. How does Dean’s List recognition affect **course load, retention, and long-term academic success**?
3. Are there **heterogeneous effects** based on student demographics, prior academic history, or motivation levels?
4. Can **machine learning techniques** improve our understanding of how students respond to academic incentives?
   
  ![Poster](https://github.com/Rising-Stars-by-Sunshine/Final-Research-Proposal-Asilbek-Amonov/blob/main/visualization/White%20and%20Blue%20Modern%20College%20Academic%20Research%20Poster%20(1).png)

---

## **Methodology**
### **Regression Discontinuity Design (RDD)**
- We exploit the **GPA threshold (3.5/4.0)** for Dean’s List recognition as a quasi-random treatment assignment.
- Students just above and just below the threshold are assumed to be **statistically similar**, making this a **natural experiment**.
- Key assumptions (e.g., no precise manipulation of GPA) are tested for validity.

### **Machine Learning (ML) Approaches**
- **Predictive Modeling:** Supervised learning methods to analyze factors influencing academic performance.
- **Explainable AI Techniques:** Using **SHAP values and attention mechanisms** to interpret ML models.
- **Feature Engineering:** Utilizing engagement metrics, course selection, and demographic attributes.

---

## **Data Sources**
- **University Registrar Data:** Student GPA records, course loads, retention rates.
- **Demographic Information:** Age, gender, high school GPA, standardized test scores.
- **Engagement Metrics:** Use of learning management systems, library visits.
- **Data Privacy Compliance:** All data will be anonymized and analyzed in accordance with IRB protocols.

---

## **Repository Structure**
```
📂 project-root/
│── 📂 code/                 # Python scripts and Jupyter notebooks
│── 📂 data/                 # Raw and processed datasets
│── 📂 visualizations/       # Figures, charts, and model outputs
│── 📂 docs/                 # Supplementary documentation
│── 📄 README.md             # Project description
│── 📄 requirements.txt      # Dependencies and package requirements
```

---

## **Key Results (Expected)**
- We anticipate **small but significant** effects on student motivation and engagement.
- Possible **heterogeneous effects**, where students with **lower prior performance** might benefit more.
- Dean’s List recognition may function more as a **resume signal** rather than a strong **academic incentive**.

---

## **Practical Implications**
- **Policy Recommendations:** Universities should evaluate whether academic honors contribute to long-term success.
- **Mental Health Considerations:** Recognition should **motivate students without inducing undue pressure**.
- **Machine Learning Integration:** Predictive modeling can **improve academic support interventions**.

---

## **Ethical Considerations**
- **Bias and Fairness:** Ensuring that data-driven insights do not disproportionately favor certain student groups.
- **AI Governance:** Aligning ML usage with educational best practices.
- **Transparency:** Making our models explainable and interpretable.

---

## **How to Run the Code**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/deans-list-causal-impact.git
   cd deans-list-causal-impact
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the **data preprocessing pipeline**:
   ```bash
   python preprocess_data.py
   ```
4. Train the **ML models**:
   ```bash
   python train_model.py
   ```
5. Generate **visualizations and reports**:
   ```bash
   python generate_report.py
   ```

---

## **Contributors**
- **Asilbek Amonov** – Research, Data Analysis, Machine Learning
- **Professor Luyao Zhang** – Instructor, Duke Kunshan University

---

## **Acknowledgments**
This project was submitted for **STATS201: Machine Learning for Social Science** at **Duke Kunshan University (Spring 2025)**. Special thanks to the teaching staff for their guidance.


