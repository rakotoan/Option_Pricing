
# Call Up & Out Pricing

Welcome to the Call UP & Out Pricing project ! This initiative aims to price a **Call Up & Out** using the **Monte Carlo method**. 


# 📄 Product : Call Up & Out 

🎯 Strike:  **K = 100 $**<br>
⏳ Maturity: **T = 1 year**<br>
🚧 Barrier: **B = 150 $**<br>


# Working Conditions 

📉 Volatility: **σ = 30%**<br>
💶 Risk-free Interest Rate: **r = 2%**<br>
📈 Underlying asset at t = 0: $S_0$ = 100 $ 



# 📊 Pricing results

<img width="618" height="396" alt="image" src="https://github.com/user-attachments/assets/86a3acad-7118-4560-95bb-0ef08b077ccd" />


<br>


| Option type              | Parameters                        | Monte Carlo price at t = 0 |
|--------------------------|-----------------------------------|----------------------------|
| European call            | S₀ = 100, K = 100, r = 2 %, σ = 0.3, T = 1 | 12.297 $                   |
| Call Up & Out | S₀ = 100, K = 100, B = 150, r = 2 %, σ = 0.3, T = 1 | 5.85332 $                 |





## ⚙️ Prerequisites

To successfully run this project, ensure you have the following installed:
- 🐍 **Python**
- 📓 **Jupyter Notebook**
- 📦 **Required libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`


## 📌 Installation
 
1. Create and activate a Python virtual environment.
2. Install dependencies

## 💻 Usage
 
Open the notebooks in order to reproduce the pipeline:
 
```bash
jupyter notebook notebooks/Call_Up&Out_Pricing_Monte_Carlo.ipynb
```

