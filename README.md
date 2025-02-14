# 📈 Telecom Customer Analysis 📊

## 📍 Project Overview

This project analyzes telecom customer data to uncover insights related to services like phone, internet, security, streaming, and more. The analysis uses Python libraries like Pandas, Seaborn, and Matplotlib to generate count plots and gain a better understanding of customer preferences.

---

## 🗂️ Data Description

The dataset includes the following key categorical features:

- `PhoneService`: Whether the customer has a phone service (Yes/No)  
- `MultipleLines`: Single line or multiple lines (No/Yes/No phone service)  
- `InternetService`: Type of internet service (DSL/Fiber optic/No)  
- `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`: Additional services (Yes/No/No internet service)  
- `StreamingTV`, `StreamingMovies`: Streaming services usage (Yes/No/No internet service)  

The dataset consists of thousands of records representing customers with varying service subscriptions.

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ **Phone Service**
- Most customers have an active phone service.  
- Only a small fraction (682) do not use phone services.

![PhoneService](https://via.placeholder.com/600x400?text=PhoneService+Count+Plot)

---

### 2️⃣ **Multiple Lines**
- The majority of customers use a single line.  
- A considerable number have opted for multiple lines.  

![MultipleLines](https://via.placeholder.com/600x400?text=MultipleLines+Count+Plot)

---

### 3️⃣ **Internet Service**
- Fiber optic is the most popular internet option.  
- DSL is less common, and some customers have no internet service.

![InternetService](https://via.placeholder.com/600x400?text=InternetService+Count+Plot)

---

### 4️⃣ **Online Security & Backup**
- A significant number of customers have not subscribed to online security.  
- Online backup adoption is also relatively low.

![OnlineSecurity](https://via.placeholder.com/600x400?text=OnlineSecurity+Count+Plot)
![OnlineBackup](https://via.placeholder.com/600x400?text=OnlineBackup+Count+Plot)

---

### 5️⃣ **Device Protection & Tech Support**
- Device protection and tech support services are underutilized.  

![DeviceProtection](https://via.placeholder.com/600x400?text=DeviceProtection+Count+Plot)
![TechSupport](https://via.placeholder.com/600x400?text=TechSupport+Count+Plot)

---

### 6️⃣ **Streaming Services**
- Streaming TV and streaming movies services have relatively high adoption rates.  
- Customers show significant interest in entertainment services.  

![StreamingTV](https://via.placeholder.com/600x400?text=StreamingTV+Count+Plot)
![StreamingMovies](https://via.placeholder.com/600x400?text=StreamingMovies+Count+Plot)

---

## 🧠 **Key Insights**

1. **Phone Service:**  
   - Over 90% of customers have phone services.  

2. **Multiple Lines:**  
   - Single-line plans are slightly more popular than multiple-line plans.  

3. **Internet Service:**  
   - Fiber optic is the most preferred internet service.  

4. **Online Security/Backup:**  
   - Security and backup services have low adoption despite their importance.  

5. **Device Protection/Tech Support:**  
   - Tech support services are not widely utilized, potentially indicating a need for better customer education.  

6. **Streaming Services:**  
   - Streaming services are popular, reflecting the growing interest in digital entertainment.  

---

## 🚀 **Conclusions & Recommendations**

- **Promote Security Services:**  
  Consider promotional campaigns for online security and backup services.  

- **Tech Support Awareness:**  
  Increase awareness about the benefits of tech support through customer outreach.  

- **Streaming Service Bundling:**  
  Introduce bundled packages for streaming services to attract more users.  

- **Fiber Optic Growth:**  
  Expand fiber optic availability to match increasing demand.  

---

## ⚙️ **Reproducibility**

To reproduce the analysis:

1. Clone the repository:  
    ```bash
    git clone https://github.com/YourUsername/Telecom-Customer-Analysis.git
    cd Telecom-Customer-Analysis
    ```

2. Install required libraries:  
    ```bash
    pip install pandas matplotlib seaborn notebook
    ```

3. Run the Jupyter notebook:  
    ```bash
    jupyter notebook Main.ipynb
    ```

---

## 🖼️ **Image Placeholder Explanation**

- Replace the placeholder image URLs with actual plots generated from the notebook.  
- You can upload these images to GitHub and use their direct links for display here.  

---

---

**Happy Analyzing! 🚀**