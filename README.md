# AI-Ethical-Decision-Evaluation
AI Ethical Decision Evaluation: A project analyzing fairness, bias, and explainability of AI models in ethical decision-making scenarios.

This project focuses on **AI ethics** by evaluating scenarios where AI models make decisions with ethical implications (e.g., hiring, self-driving cars, criminal justice). It aims to simulate ethical dilemmas, assess fairness or bias in model outputs, and explain decisions using interpretability tools.

## Features
- **Dataset**: Uses real-world data to evaluate ethical dilemmas (COMPAS dataset for recidivism).
- **Scenario Analysis**: Simulates decisions in contexts like prioritizing accident victims or hiring processes.
- **Bias Detection**: Analyzes model predictions for fairness across different demographic groups.
- **Explainability**: Leverages tools like SHAP to understand feature contributions to decisions.

## Project Progress
This is an **ongoing project**. Current progress includes:
1. Dataset loading and cleaning.
2. Model training (Random Forest).
3. Fairness evaluation using precision and recall metrics.
4. Feature importance analysis using SHAP and model-based methods.

## How to Use
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/mahak01adil/AI-Ethical-Decision-Evaluation.git
    cd AI-Ethical-Decision-Evaluation
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open `EAI.ipynb` to view and run the project.

4. **Dataset**:
    - Download the dataset from [GitHub](https://github.com/propublica/compas-analysis/blob/master/compas-scores-two-years.csv) 
    - Ensure the file name matches `compas-scores-two-years.csv`.

## Credits
- **Dataset**: [Original COMPAS dataset](https://github.com/propublica/compas-analysis/blob/master/.gitignore).
- **Tools Used**: 
  - `pandas`
  - `scikit-learn`
  - `shap` will use 
  - `fairlearn` will use

## Feedback and Suggestions
Feel free to open issues or pull requests on GitHub. You can also email me at `mahak01adil@gmail.com.com` with feedback.



