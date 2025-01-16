# Customer Churn Prediction

## Overview
The **Customer Churn Prediction** application helps businesses identify customers at risk of leaving (churning) by analyzing their behavior and interaction patterns. Built using **Streamlit**, this web-based tool provides a user-friendly interface for exploring customer data, predicting churn probability, and gaining insights to improve customer retention strategies.

Access the app: [Customer Churn Predictor](https://customer-churn-predictor-jlmaoc8candzgnqyfq79ae.streamlit.app/)

---

## Features
- **Interactive Interface**: Upload customer data and get instant predictions.
- **Data Visualization**: Visualize customer behavior through insightful graphs and charts.
- **Churn Probability**: Predict the likelihood of churn for each customer.
- **Actionable Insights**: Gain data-driven insights to make informed retention decisions.
- **Customizable Inputs**: Adjust thresholds or customer parameters for tailored predictions.

---

## Technology Stack
- **Frontend**: [Streamlit](https://streamlit.io) for the interactive web app.
- **Backend**: Python with machine learning models for churn prediction.
- **Machine Learning**:
  - Libraries: `scikit-learn`, `pandas`, `numpy`, `joblib`.
  - Model: Trained on a customer dataset with classification algorithms.
- **Deployment**: Hosted on **Streamlit Cloud**.

---

## How It Works
1. **Upload Data**: Upload a CSV file with customer data.
2. **Data Processing**: The app preprocesses the data, including handling missing values and encoding categorical features.
3. **Model Prediction**: The pre-trained machine learning model predicts the churn probability for each customer.
4. **Visualization**: Results are displayed as charts and tables for better understanding.

---

## Getting Started

### Prerequisites
- Python 3.7 or higher
- Required Python libraries:
  ```bash
  pip install streamlit scikit-learn pandas numpy matplotlib seaborn joblib
  ```

### Run Locally
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd customer-churn-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the app:
   ```bash
   streamlit run app.py
   ```

4. Access the app locally:
   Open [http://localhost:8501](http://localhost:8501) in your browser.

---

## Using the Application
1. Navigate to the app [here](https://customer-churn-predictor-jlmaoc8candzgnqyfq79ae.streamlit.app/).
2. Upload your customer dataset in `.csv` format.
3. View:
   - Churn predictions for each customer.
   - Statistical insights into churn patterns.
   - Visualizations like bar charts, histograms, or scatter plots.
4. Take action based on the churn probabilities.

---

## Future Enhancements
- Add more advanced visualizations.
- Enable real-time model retraining with new data.
- Support for API integration for seamless business usage.
- Implement additional machine learning models for comparison.

---

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any feature suggestions or bug fixes.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For questions or support, feel free to reach out via:
- **Email**: [aryansethiya111@gmail.com](mailto:aryansethiya111@gmail.com)

