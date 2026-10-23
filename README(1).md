# Phishing URL Detection Using Machine Learning

**Student:** Shruti Tukaram Avhad  
**Program:** IBM SkillsBuild Cyber Security 2026 — BharatCares

## Project description
This educational project trains a machine-learning model to classify URL text as likely legitimate or potentially phishing/malicious. It uses character-level TF-IDF features and Logistic Regression. The notebook evaluates the model on a held-out test set.

## Dataset
- Public dataset source: [Using machine learning to detect malicious URLs — CSV](https://raw.githubusercontent.com/faizann24/Using-machine-learning-to-detect-malicious-URLs/master/data/data.csv)
- Repository: [faizann24/Using-machine-learning-to-detect-malicious-URLs](https://github.com/faizann24/Using-machine-learning-to-detect-malicious-URLs)
- The dataset is used for educational experimentation. Verify the source, license, and suitability before reuse or redistribution. If the link is unavailable, download a compatible CSV and set `DATASET_PATH` in the notebook.

## Technologies used
- Python
- pandas and NumPy for data handling
- scikit-learn for TF-IDF, Logistic Regression, splitting, and evaluation
- Matplotlib for the confusion matrix
- Jupyter Notebook

## Setup instructions
1. Install Python 3.10 or later.
2. Place the notebook and `requirements.txt` in the same folder.
3. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `ShrutiTukaramAvhad_PhishingURLDetection.ipynb` and run the cells from top to bottom.
6. Ensure you have an internet connection for automatic dataset download, or download a compatible dataset CSV and update `DATASET_PATH`.

## Output
The notebook prints the test-set accuracy and classification report, displays a confusion matrix, demonstrates a URL-text prediction, and optionally saves the model as `phishing_url_model.joblib`.

## Responsible use and limitations
The classifier is a demonstration, not a guarantee that a URL is safe or harmful. It may make false predictions and should not be used as the sole security control. The notebook classifies URL text and does not open websites. Do not visit suspicious URLs or use the project to target systems without authorization.

## Project files
- `ShrutiTukaramAvhad_PhishingURLDetection.ipynb` — notebook code
- `requirements.txt` — Python dependencies
- `ShrutiTukaramAvhad_ProjectReport.docx` — project report
- `README.md` — this overview and setup guide
