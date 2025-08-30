# **Bias Detection and Mitigation in AI Models**

## **📌 Project Overview**
This project analyzes bias in AI models trained on the **UCI Adult Dataset** for income prediction. It evaluates fairness metrics and applies bias mitigation techniques to improve model fairness while maintaining accuracy.

## **📊 Dataset**
- **UCI Adult Dataset**: Predicts income level (`<=50K` or `>50K`) based on features like age, education, gender, race, etc.

## **🚀 Key Features**
- Implemented **Logistic Regression & Decision Tree** models for income prediction.
- Used **AI Fairness 360 (AIF360)** to measure fairness metrics (**Disparate Impact, Statistical Parity Difference**).
- Applied **reweighting techniques** to mitigate bias while preserving model accuracy.
- Visualized the impact of bias mitigation through comparative analysis.

## **🛠 Tech Stack**
- **Programming:** Python
- **Libraries:** Scikit-learn, Pandas, NumPy, AI Fairness 360, Matplotlib

## **📂 Project Structure**
```
📦 Bias-Detection-AI
├── 📄 README.md  # Project documentation
├── 📄 bias_detection.ipynb  # Jupyter Notebook with code implementation
├── 📄 requirements.txt  # Required libraries
└── 📂 data  # Dataset folder (UCI Adult Dataset)
```

## **⚙️ Installation & Setup**
1️⃣ Clone this repository:
```bash
git clone https://github.com/your-username/Bias-Detection-AI.git
cd Bias-Detection-AI
```
2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```
3️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook bias_detection.ipynb
```

## **📈 Results**
- **Baseline Model Accuracy:** ~85.6%
- **Mitigated Model Accuracy:** ~85.5%
- **Bias Metrics Before Mitigation:** Higher disparity in fairness metrics.
- **Bias Metrics After Mitigation:** Reduced bias while maintaining performance.


