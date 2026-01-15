## 📌 Contents of the Repository

This repository contains **two sets of Rust programs**:

### 1️⃣ Statistical Functions (`statistics.txt`)
Includes basic implementations of common statistical operations:

- Chi-Square Test  
- One-Way ANOVA  
- Mann-Whitney U Test  
- Wilcoxon Test  
- Spearman Correlation  
- Kendall Tau Correlation  
- Moving Average  
- Exponential Moving Average  
- Autocorrelation  
- Time Series Decomposition  

Each function is written using **simple logic** to make it easy for understanding.

---

### 2️⃣ Date & Time Functions (`datetime.txt`)
Includes commonly used date and time operations using Rust:

- Get Current Date & Time  
- Format Date  
- Parse Date  
- Add Days to a Date  
- Difference Between Two Dates  
- Get Day of the Week  
- Start of Day  
- End of Day  
- Leap Year Check  
- Time Ago Format  

These examples use the **`chrono` crate**.

---

## 📂 Project Structure

assignment_rust/


├── statistics.txt     
├── datetime.txt        
├── Cargo.toml          
└── README.md           



---

## ▶️ How to Run the Code

### 🔹 Step 1: Install Rust
Download and install Rust from the official website:

🔗 https://www.rust-lang.org/tools/install

Verify installation:
```bash
rustc --version
cargo --version
🔹 Step 2: Running Using rustc (Simple Method)
Copy code from statistics.txt or datetime.txt

Paste it into a file named main.rs

Compile:

rustc main.rs

🔹 Step 3: Running Using Cargo 
Initialize a Cargo Project
cargo init

src/main.rs
Add Dependency (for Date/Time Programs)
Open Cargo.toml and add:

[dependencies]
chrono = "0.4"

Run the Project
cargo run










