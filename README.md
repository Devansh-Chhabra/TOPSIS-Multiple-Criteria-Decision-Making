# 📊 TOPSIS Implementation (from scratch)

🔗 *Web Service:* [Click here to view](https://github.com/Devansh-Chhabra/TOPSIS-WEB-SERVICE)


## ✨ Overview

This project is a from-scratch Python implementation of **Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS)** 📈.

The goal is to demonstrate the complete mathematical logic of TOPSIS step by step using NumPy and Pandas, without relying on any pre-built TOPSIS libraries. The entire implementation is presented in a well-structured Jupyter Notebook for clarity and learning.

---

## 🧐 What is TOPSIS?

TOPSIS is a popular **Multi-Criteria Decision Making (MCDM)** technique used to rank alternatives when multiple (often conflicting) criteria are involved.

### 🎯 Core Idea

The best alternative should:
* ✅ Be closest to the **Positive Ideal Solution (PIS)**
* ❌ Be farthest from the **Negative Ideal Solution (NIS)**

### 📌 Common Applications

* Business decision-making
* Engineering design selection
* Data science & analytics
* Product and vendor ranking

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 🧮 From Scratch | No external TOPSIS libraries used |
| 📘 Educational | Step-by-step breakdown of the algorithm |
| 🧩 Modular Logic | Easy to adapt for any dataset |
| 📊 Transparent | Each intermediate matrix is clearly shown |
| 💡 Beginner Friendly | Ideal for learning MCDM concepts |

---

## 📂 Project Structure
```bash
📦 TOPSIS-Implementation
 ┣ 📜 Topsis.ipynb        # Complete TOPSIS implementation
 ┣ 📜 README.md           # Project documentation
 ┗ 📜 LICENSE             # MIT License
```

---

## 🛠️ Prerequisites

Make sure you have the following installed:

| Requirement | Version |
|-------------|---------|
| 🐍 Python | 3.x |
| 📦 Pandas | Latest |
| 🔢 NumPy | Latest |

---

## 🔧 Installation
```bash
pip install pandas numpy
```
---

## 💻 Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Devansh-Chhabra/TOPSIS-Implementation.git
cd TOPSIS-Implementation
```

### 2️⃣ Open the Notebook
```bash
jupyter notebook Topsis.ipynb
```

### 3️⃣ Run the Cells

Execute the cells sequentially to observe:
* Normalization
* Weight application
* Ideal best & worst
* Final ranking

🔁 You can replace the sample dataset with your own CSV file or DataFrame to rank custom alternatives.

---

## 📊 Methodology (How TOPSIS Works)

The implementation follows the standard TOPSIS workflow:

1. **Create Decision Matrix**
2. **Normalize the Matrix**
3. **Apply Weights to Criteria**
4. **Determine Ideal Solutions**
   * Ideal Best (V⁺)
   * Ideal Worst (V⁻)
5. **Compute Separation Measures**
   * Distance from V⁺
   * Distance from V⁻
6. **Calculate Performance Score**
   * Score ∈ [0, 1]
7. **Rank Alternatives**
   * Higher score → Better rank 🏆
  
---


## 📈 Output Interpretation

| Score Range | Interpretation |
|-------------|----------------|
| 🔴 0.0 – 0.3 | Poor alternative |
| 🟡 0.3 – 0.6 | Average alternative |
| 🟢 0.6 – 1.0 | Best alternative |

---


## 📄 License

This project is licensed under the **MIT License** 📜  
See the `LICENSE` file for more details.

---

## 👨‍💻 Author

**Devansh Chhabra**  
📧 Email: [devanshchhabr@gmail.com](mailto:devanshchhabr@gmail.com)  

---
