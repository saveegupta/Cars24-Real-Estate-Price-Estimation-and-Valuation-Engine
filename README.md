# Smart Property Price Prediction and Valuation System for Dubai Real Estate

## 📌 Project Description
This project was developed as part of the **Cars24 Data Science Internship Assessment**. It focuses on building a machine learning-powered system that predicts the listing price of properties in Dubai based on property features. Additionally, it classifies whether a listing is **Underpriced**, **Fairly Priced**, or **Overpriced**.

**Key Features:**
- Data cleaning and exploratory data analysis (EDA)
- Price prediction using Linear Regression and Random Forest
- Valuation tool with adjustable threshold logic
- Explainability using SHAP
- Scalable deployment architecture with model serving

**Motivation:**
Real estate pricing is often inconsistent and subjective. This project aims to provide a transparent, data-driven approach to help both buyers and sellers understand the fair market value of properties.

---

## 📚 Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)
- [Acknowledgements](#acknowledgements)

---

## 💻 Installation

### Prerequisites
- Python 3.8+
- pip
- Jupyter Notebook / Google Colab (recommended)

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap fpdf
```

### Clone Repository
```bash
git clone https://github.com/yourusername/property-price-prediction.git
cd property-price-prediction
```

---

## 🚀 Usage

### Step-by-Step
1. Load the dataset (`data_science_challenge_data.csv`)
2. Run `property_price_prediction.ipynb` notebook or Python script
3. Use the valuation function to classify prices:
```python
classify_valuation(actual_price, predicted_price)
```

### Sample Output
```
Predicted Price: 950000
Actual Price: 1000000
Valuation: Fairly Priced
```

---

## 🤝 Contributing
We welcome contributions to improve this tool.

- Fork this repository
- Create a new branch (`git checkout -b feature-xyz`)
- Commit your changes (`git commit -m 'Add feature'`)
- Push to the branch (`git push origin feature-xyz`)
- Open a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

---

## 📄 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact Information
**Maintainer:** Savee Gupta  
**Email:** saveegupta672@email.com  
**LinkedIn:** [linkedin.com/in/saveegupta]([https://linkedin.com/in/saveegupta](https://www.linkedin.com/in/savee-gupta-9b85991ab/))

---

## 🙌 Acknowledgements
- [scikit-learn](https://scikit-learn.org/)
- [SHAP](https://github.com/slundberg/shap)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)
- Cars24 for the assessment opportunity

---

## 🔧 Optional Enhancements
- Add Dockerfile and deployment scripts
- Add CI/CD with GitHub Actions
- Add integration with real estate APIs (e.g., Bayut, Property Finder)
- [ ] Add a roadmap and changelog

> Made with lots of effort & dedication for the Cars24 Data Science Internship

