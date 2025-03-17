# **Decision Analytics & Optimization: Transportation, Healthcare, and Project Management**  

![Project Banner](https://github.com/Swasti28/Decision-Analytics-Optimization-Transportation-Healthcare-and-Project-Management/blob/main/DALL%C2%B7E%202025-03-17%2015.22.20%20-%20A%20professional%20project%20banner%20for%20'Decision%20Analytics%20%26%20Optimization'.%20The%20banner%20should%20include%20keywords%20like%20'Linear%20Programming%20(LP)'%2C%20'Data%20Envelo.webp)  

## **📌 Overview**  
This project applies **Decision Analysis Modeling** techniques using **Linear Programming (LP), Data Envelopment Analysis (DEA), and Project Management methodologies** to solve real-world business and operational challenges. The project covers:  

- **📦 Transportation Optimization** – Minimized transportation costs for Hardrock Concrete Company using **Linear Programming (LP) & Excel Solver**.  
- **🏥 Hospital Efficiency Analysis** – Evaluated hospital efficiency using **DEA modeling & input-output analysis**.  
- **📊 Project Management Optimization** – Developed a **PERT/CPM network diagram** for an accounting audit, optimizing **critical path, scheduling, and risk assessment**.  

## **🚀 Key Skills & Technologies Used**  
✔ **Linear Programming (LP)** – Optimization of resource allocation  
✔ **Data Envelopment Analysis (DEA)** – Efficiency modeling for hospitals  
✔ **Critical Path Method (CPM) & PERT** – Project scheduling & risk management  
✔ **Excel Solver & QM for Windows** – Data-driven decision analysis  
✔ **Operations Research & Optimization Techniques**  
✔ **Business Intelligence & Cost Minimization Strategies**  

---

## **📍 Problem 1: Transportation Cost Optimization**  

### **📝 Problem Statement**  
The **Hardrock Concrete Company** operates **three plants** and must deliver materials to **three project sites** at the lowest transportation cost. The goal is to determine the **optimal shipment plan** while considering capacity and demand constraints.  

### **📊 Input Data**  
| From → To | Albuquerque | Boston | Cleveland | Capacity |
|-----------|------------|--------|-----------|----------|
| **Des Moines** | $5 | $4 | $3 | 300 |
| **Evansville** | $8 | $4 | $3 | 150 |
| **Fort Lauderdale** | $9 | $7 | $5 | 250 |
| **Demand** | 200 | 200 | 300 | - |

### **🛠️ Methodology**  
- Formulated the **Linear Programming Model** using **Decision Variables (Xij)**  
- Defined **Objective Function:** Minimize total transportation cost  
- Applied **Excel Solver** for **Simplex Optimization**  

### **✅ Results & Optimization**  
Using **Solver**, the **optimized transportation cost was reduced to $9,400** from an initial **$10,400**.  

📌 **Key Learning:** **Cost minimization, LP modeling, Excel Solver application**  

---

## **📍 Problem 2: Hospital Efficiency Analysis using DEA**  

### **📝 Problem Statement**  
Evaluate the **relative efficiency of seven hospitals** based on **input (resources) and output (services provided)** using **Data Envelopment Analysis (DEA)**.  

### **📊 Input & Output Measures**  
#### **📌 Inputs:**  
| Hospital | Non-Physician Staff | Supply Cost ($1000s) | Bed-Days Available (1000s) |
|----------|---------------------|----------------------|----------------------------|
| A | 310 | 134.6 | 116 |
| B | 278.5 | 114.3 | 106.8 |
| C | 165.6 | 131.3 | 65.52 |
| D | 250 | 316 | 94.4 |
| E | 206.4 | 151.2 | 102.1 |
| F | 384 | 217 | 153.7 |
| G | 530.1 | 770.8 | 215 |

#### **📌 Outputs:**  
| Hospital | Patient-Days (65+) | Patient-Days (<65) | Nurses Trained | Interns Trained |
|----------|--------------------|--------------------|---------------|----------------|
| A | 55.31 | 49.52 | 291 | 47 |
| B | 37.64 | 55.63 | 156 | 3 |
| C | 32.91 | 25.77 | 141 | 26 |
| D | 33.53 | 41.99 | 160 | 21 |
| E | 32.48 | 55.3 | 157 | 82 |
| F | 48.78 | 81.9 | 285 | 92 |
| G | 58.41 | 119.7 | 111 | 89 |

### **🛠️ Methodology**  
- Developed **Linear Programming Model** for DEA  
- Compared **Hospital D's efficiency** with others  
- Used **Solver in Excel** to compute efficiency scores  

### **✅ Results & Interpretation**  
- **Hospital D's efficiency score < 1**, indicating inefficiency  
- **Hospital E is the best benchmark** for improvement  

📌 **Key Learning:** **DEA modeling, efficiency benchmarking, resource optimization**  

---

## **📍 Problem 4: Project Management Optimization using PERT & CPM**  

### **📝 Problem Statement**  
Optimize the **audit workflow** for an accounting firm using **PERT & CPM** to determine the **critical path** and **completion probabilities**.  

### **📊 Critical Path Analysis (CPM)**
#### **📌 Task Dependencies & Time Estimates**
| Task | Predecessor | Optimistic | Most Likely | Pessimistic | Expected Time (TE) |
|------|------------|------------|------------|------------|------------|
| A - Audit Planning | - | 44 | 48 | 52 | 48 |
| B - Observe Inventory | A | 16 | 25 | 30 | 24.33 |
| C - General Audit Procedures | B | 6 | 11 | 13 | 10.5 |
| ... | ... | ... | ... | ... | ... |
| S - Partner/Manager Review | Q, R | 5 | 6 | 7 | 6 |

### **🛠️ Methodology**  
- Created **PERT/CPM Network Diagram**  
- Identified **Critical Path:** **A → B → E → H → P → Q → S**  
- Calculated **slack times** and **project completion probability**  

### **✅ Results & Optimization**  
- **Total project duration: 318.99 hours**  
- **Probability of completion within 15 days: 12.7%**  
- Developed **Gantt chart & resource allocation plan**  

📌 **Key Learning:** **PERT, CPM, Gantt charts, project risk analysis**  

---

## **📌 Conclusion**  
This project demonstrates **advanced decision analytics** using **LP, DEA, and Project Management models**. The **transportation cost model** optimized logistics, the **hospital efficiency analysis** provided data-driven recommendations, and the **audit scheduling model** optimized workflows for better project execution.  

### **🚀 Key Takeaways:**  
✔ **Mathematical Optimization for Cost Savings**  
✔ **Hospital Performance Benchmarking via DEA**  
✔ **Project Scheduling using PERT/CPM & Slack Analysis**  
✔ **Business Intelligence & Decision Science Techniques**  

---

## **📂 Project Files & Resources**  
📌 **Excel Solver Models** – 

<img width="384" alt="image" src="https://github.com/user-attachments/assets/78385b38-6a75-4a0a-9195-9e4506b5e3b6" />

DEA model formulation using solver


<img width="421" alt="image" src="https://github.com/user-attachments/assets/b90e9b90-c65b-478a-99cb-59910a4ca1e9" />

DEA model formulation using solver for Hospital E

📌 **PERT/CPM Network Diagram** –

<img width="468" alt="image" src="https://github.com/user-attachments/assets/2c4a9691-850b-4094-b648-8732940b5c02" />

PERT Diagram using AON (Orange Activities represent the Critical Path)


📌 **Gantt Chart for Project Management** - 

<img width="468" alt="image" src="https://github.com/user-attachments/assets/1cd415e9-9607-4ee1-9231-dd775afdd8f6" />

📌 **Full Report (PDF/DOCX)** - 📄 [Project Report - Word File](https://github.com/Swasti28/Decision-Analytics-Optimization-Transportation-Healthcare-and-Project-Management/blob/main/Group%20Software%20Application%20Project%20-%20Group%20C.docx)
---

## **💡 Future Enhancements**  
🔹 Integrate **Python or R** for automation of LP & DEA models  
🔹 Implement **Machine Learning for predictive decision-making**  
🔹 Optimize **transportation routes using AI-driven models**  
