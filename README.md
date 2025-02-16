# debt_calculator
# 💰 Debt Repayment Calculator with AI

## **🌟 Overview**
This **Debt Repayment Calculator** helps users **calculate EMI (Equated Monthly Installment), total interest, and total repayment amount** based on their loan details. It also leverages **Machine Learning (ML) and Deep Learning (LSTM)** to predict **future interest rates**, providing users with smart financial insights.

---

## **🔧 Features**
✅ **EMI Calculator**: Computes monthly installments for any loan amount, interest rate, and tenure.
✅ **Total Interest Calculation**: Displays the total interest paid over the loan period.
✅ **Debt Repayment Strategies**: Suggests **Snowball & Avalanche** methods for faster repayment.
✅ **ML-Powered Interest Rate Prediction**: Uses **Linear Regression & LSTM** to predict future loan interest rates.
✅ **Financial Advisory**: Warns users if EMIs are too high and suggests refinancing options.
✅ **Graphical Insights**: Displays past and predicted interest rate trends.


## **🔨 Installation**
Ensure you have **Python 3.7+** installed, then install the required libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
```

---

## **🕹️ Usage**
Clone the repository and open `debt_calculator.ipynb` in **Jupyter Notebook**:
```bash
git clone https://github.com/yourusername/Debt-Repayment-Calculator.git
cd Debt-Repayment-Calculator
jupyter notebook debt_calculator.ipynb
```
Run each cell in order to:
1. Calculate **EMI & Total Interest**.
2. Train an **ML Model** to predict future interest rates.
3. Train an **LSTM Model** for time-series forecasting.
4. Get personalized **loan repayment strategies**.

---

## **📂 Project Structure**
```
📁 Debt-Repayment-Calculator/
│── 📄 README.md                # Project Documentation
│── 📄 debt_calculator.ipynb    # Jupyter Notebook with full code
│── 📁 models/                  # (Optional) Trained ML & LSTM models
│── 📁 data/                    # (Optional) CSV files for interest rate history
```

---

## **📈 Demo Output**
### **💳 Sample User Input:**
```
Enter Loan Amount (₹): 500000
Enter Annual Interest Rate (%): 10
Enter Loan Tenure (Years): 5
```

### **📊 Output in Jupyter Notebook:**
```
📌 EMI: ₹10607.49
💰 Total Interest Paid: ₹136449.22
✅ Total Payment: ₹636449.22
🔮 Predicted Interest Rate for 2025: 7.85%
⚠️ High EMI detected! Consider extending your tenure or refinancing your loan.

### Loan Repayment Strategies
- Snowball Method: Pay the smallest loan first, then move to larger debts.
- Avalanche Method: Pay off the highest interest loans first for long-term savings.
```

---

## **👩‍💻 Future Improvements**
- [ ] **Integrate Bank API** to fetch real-time interest rates.
- [ ] **Add UPI Payment Integration** for automatic EMI tracking.
- [ ] **Develop a Web App** using Flask/Streamlit.
- [ ] **Deploy as a Mobile App** using Flutter or React Native.

---

## **💼 Contributing**
Want to improve this project? **Contributions are welcome!**
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

---

## **📚 License**
This project is **open-source** and licensed under the **MIT License**.

---

## **🎉 Author**
Developed by Roshan Tigga | GitHub:

