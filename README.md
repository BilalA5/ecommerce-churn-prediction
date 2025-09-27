# E-commerce Cart Abandonment Prediction

A machine learning project that analyzes customer behavior patterns to predict cart abandonment and identify key factors influencing e-commerce conversion rates.

## 🎯 Project Overview

This project uses machine learning techniques to predict the likelihood of cart abandonment in e-commerce scenarios. By analyzing customer behavior, device usage, and session characteristics, we developed a Decision Tree classifier that can identify high-risk abandonment sessions and provide actionable insights for improving conversion rates.

## 📊 Data Source

The dataset used in this project is from [Kaggle](https://www.kaggle.com/datasets/ritalin56/e-commerce-card-abandonment/data):

> Ritalin56. (n.d.). *E-commerce cart abandonment* [Dataset]. Kaggle. Retrieved September 14, 2025.


## 🔍 Key Findings

- **Cart Abandonment Rate**: 30% (below industry average of 60-70%)
- **Model Accuracy**: 70% with balanced predictions
- **Key Predictors**: Customer type, coupon usage, device type, and cart value
- **Revenue Opportunity**: Potential 14-21% increase with targeted interventions

## 🛠️ Technical Approach

### Data Processing
- Cleaned and preprocessed 5,000 customer sessions
- Engineered 20 features from 12 original variables
- Addressed class imbalance issues for accurate predictions

### Machine Learning Model
- **Algorithm**: Decision Tree Classifier
- **Optimization**: Comprehensive hyperparameter tuning
- **Validation**: 80/20 train-test split with cross-validation
- **Performance**: Balanced accuracy across both abandonment and completion cases

### Key Features Analyzed
- Customer demographics (browser, device, OS)
- Behavioral patterns (time spent, cart value, items)
- Contextual factors (coupon usage, customer status)

## 📈 Business Impact

### Identified Opportunities
1. **New Customer Conversion**: Target first-time visitors with incentives
2. **Mobile Optimization**: Improve checkout experience for mobile users
3. **Strategic Discounts**: Implement coupon interventions for high-risk sessions
4. **Customer Retention**: Focus on converting new to returning customers

### Expected Results
- Reduce abandonment rate from 30% to 20-25%
- Improve conversion rates from 70% to 80-90%
- Increase customer lifetime value through better retention

## 📁 Project Structure

```
ecommerce-churn-prediction/
├── main.ipynb                 # Main analysis notebook
├── general_report.md          # Executive summary report
├── ecommerce_cart_abandonment_5k.csv  # Dataset
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd ecommerce-churn-prediction

# Install required packages
pip install pandas numpy scikit-learn matplotlib seaborn

# Launch Jupyter Notebook
jupyter notebook main.ipynb
```

### Running the Analysis
1. Open `main.ipynb` in Jupyter Notebook
2. Run all cells sequentially to reproduce the analysis
3. Review `general_report.md` for executive summary

## 📊 Results and Visualizations

The analysis includes comprehensive visualizations showing:
- Overall abandonment rate distribution
- Impact of customer type on conversion
- Effect of coupon usage on abandonment
- Device type influence on completion rates
- Cart value distribution analysis
- Feature importance rankings

## 🎯 Recommendations

### Immediate Actions
1. Deploy real-time scoring system for live session monitoring
2. Implement automatic coupon offers for high-risk abandonment sessions
3. Optimize mobile checkout flow to reduce friction

### Strategic Initiatives
1. Develop customer retention programs
2. Create personalized intervention strategies
3. Build predictive analytics dashboard

## 🔬 Methodology

### Data Analysis
- Exploratory data analysis with statistical summaries
- Correlation analysis to identify key relationships
- Class distribution analysis and imbalance handling

### Model Development
- Feature engineering and encoding
- Hyperparameter optimization using grid search
- Cross-validation for robust performance evaluation
- Class balancing techniques for accurate predictions

### Validation
- Train-test split for unbiased evaluation
- Multiple metrics: accuracy, F1-score, balanced accuracy
- Comprehensive classification reports

## 📋 Future Enhancements

- Integration with real-time e-commerce platforms
- Advanced algorithms (Random Forest, XGBoost, Neural Networks)
- Additional features (seasonality, competitor pricing)
- A/B testing framework for intervention strategies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

For questions or collaboration opportunities, please open an issue in this repository.

---

*This project demonstrates the power of machine learning in solving real-world business problems and provides actionable insights for improving e-commerce conversion rates.*
