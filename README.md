This repository explores Responsible AI techniques — focusing on Bias Detection & Mitigation, Machine Unlearning, and other methods to build fair, transparent, and trustworthy AI systems.
It contains modular projects that showcase research and practical implementations across different aspects of AI fairness, explainability, and accountability.

📂 Repository Structure
responsible-ai-lab/
│
├── bias-detection-mitigation/    # Fairness evaluation & mitigation in ML models
│   └── README.md
│
├── machine-unlearning/           # Forgetting learned data in neural networks
│   └── README.md
│
├── requirements.txt              # Common dependencies
└── README.md                     # Main repo documentation

🚀 Projects
🔹 Bias Detection & Mitigation

Dataset: UCI Adult Dataset (Income Prediction)

Models: Logistic Regression, Decision Trees

Tools: AI Fairness 360 (AIF360)

Features:

Measured fairness metrics (Disparate Impact, Statistical Parity Difference)

Applied reweighting techniques to reduce bias

Visualized fairness vs accuracy trade-offs

Results: Reduced bias while maintaining ~85% accuracy.

🔹 Machine Unlearning with CNN on MNIST

Task: Train CNN on MNIST and then selectively remove digit 7.

Features:

CNN trained on full dataset

Unlearning process: retrained model without class 7

Compared accuracy before & after unlearning

Results: Accuracy impact visualized in plots; models saved before/after unlearning.

Future Work: Federated Unlearning, Differential Privacy.

🛠 Tech Stack

Languages: Python

ML/DL Libraries: TensorFlow, Scikit-learn

Fairness & XAI: AI Fairness 360 (AIF360), SHAP, LIME (planned)

Utilities: NumPy, Pandas, Matplotlib

⚙️ Installation & Setup

1️⃣ Clone this repository

git clone https://github.com/your-username/responsible-ai-lab.git
cd responsible-ai-lab


2️⃣ Install dependencies

pip install -r requirements.txt


3️⃣ Explore individual projects inside their folders

📈 Future Directions

✅ Bias detection & mitigation in ML models

✅ Machine unlearning with CNNs

🔜 Explainability across modalities (SHAP, LIME, Grad-CAM)

🔜 Responsible AI for RAG & LLM agents

🔜 Privacy-preserving AI (Differential Privacy, Federated Learning)

👩‍💻 Contributors

Shraddha Sharma