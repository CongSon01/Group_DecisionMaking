# Decision Making with VIKOR Method

## Group Members:

- **Cong Son DUONG**
- **Mohammed Adel DJELLOUL ABBOU**
- **Nikethan NIMALAKUMARAN**
- **Samar HAMDI**

## Supervisor:

- **Mostafa AMELI, Université Gustave Eiffel, GRETTIA, UC Berkeley**

## Institution:

- **Université Gustave Eiffel**

---

## Project Description

This project focuses on **Multi-Criteria Decision Making (MCDM)** using the **VIKOR** method. The VIKOR technique helps in ranking alternatives when multiple conflicting criteria exist. The project also includes **AHP-based weight calculation**.

The project consists of three key files:

---

## 📂 Project Files

### 1️⃣ **Group AHP results.xlsx**

📌 **Purpose**:

- This Excel file contains the **AHP (Analytic Hierarchy Process) results** from four different **comparison matrices**.
- It calculates **weights** for **seven criteria**:

  - **Presentation**, **Final Project**, **HW1**, **Presence TD**, **HW2**, **Discussion**, **Presence CM**.

---

### 2️⃣ **VIKOR.ipynb**

📌 **Purpose**:

- Demonstrates a **step-by-step example** of applying the **VIKOR method** to a specific decision-making problem.
- Uses **predefined criteria and alternatives** to determine the **best-ranked alternative** based on **VIKOR scores**.

📌 **Key Components**:

- **Step 1:** Define the **decision matrix** and **criteria weights** (from AHP).
- **Step 2:** Normalize the **decision matrix**.
- **Step 3:** Compute **S (group utility), R (individual regret), and Q (VIKOR index)**.
- **Step 4:** Rank alternatives based on **Q values**.

🔹 **Reference**: This is a structured case study showing how VIKOR works on a real dataset.

---

### 3️⃣ **VIKOR_Random_ComputationTime.ipynb**

📌 **Purpose**:

- Automates the **VIKOR** process using **randomly generated data**.
- Evaluates the **computation time** for different numbers of **criteria (n)** and **alternatives (m)**.
- Generates **visual plots** to analyze the effect of increasing **n** and **m** on runtime.

📌 **Key Features**:

- **User input**: Enter the number of **criteria (n)** and **alternatives (m)**.
- **Random Data Generation**:
  - Random **decision matrix** values.
  - Random **criteria types** (**Max** for benefit, **Min** for cost).
  - Random **AHP pairwise comparison matrix** for weight calculation.
- **Computes & ranks alternatives** using **VIKOR**.
- **Plots computation time**:
  - **2D Plot:** \( n \) vs. Computation Time (Fixed \( m = 5 \)).
  - **2D Plot:** \( m \) vs. Computation Time (Fixed \( n = 5 \)).
  - **3D Surface Plot:** \( n, m \) vs. Computation Time.

🔹 **Reference**: This file helps analyze how the complexity of the decision matrix impacts computation time.

---

## 🛠 Installation & Running Instructions

### **1️⃣ Install Required Libraries**

Before running the **Jupyter Notebooks**, install the following dependencies:

```sh
pip install numpy pandas matplotlib
```

### **2️⃣ Run the Notebook**
```sh
Click "Runtime" → "Run all"
The notebook will execute all cells.
```
