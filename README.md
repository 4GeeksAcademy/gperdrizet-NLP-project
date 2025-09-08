# Natural Language Processing: Spam Detection

[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-NLP-project/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-NLP-project/actions/workflows/codespaces/create_codespaces_prebuilds)

A comprehensive machine learning project focused on URL spam detection using Natural Language Processing techniques. This project demonstrates advanced NLP methods, feature engineering, and model optimization through practical implementation of Support Vector Classifiers (SVC) and Recurrent Neural Networks (RNN).


## Project Overview

This project analyzes URL data to classify spam and legitimate URLs using machine learning techniques. The dataset contains thousands of URL samples and provides hands-on experience with:

- Text preprocessing and feature extraction
- TF-IDF vectorization and optimization
- Support Vector Machine classification
- Recurrent Neural Network implementation
- Hyperparameter optimization and cross-validation
- Model evaluation and performance comparison


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you lose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (dependencies are pre-installed)

3. **Start Working**
   - Open `notebooks/mvp.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook


### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.11

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/mvp.ipynb
   ```


## Project Structure

```
├── .devcontainer/           # Development container configuration
├── data/                    # Data file directory│
├── models/                  # Trained model directory
│
├── notebooks/               # Jupyter notebook directory
│   ├── helper_functions.py  # Utility functions for notebooks
│   ├── mvp.ipynb            # Assignment notebook (start here)
│   ├── SVC_solution.ipynb   # Support Vector Classifier solution
│   └── RNN_solution.ipynb   # Recurrent Neural Network solution
│
├── .gitignore               # Files/directories not tracked by git
├── LICENSE                  # GNU GPL 3.0 License
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```


## Dataset

The dataset contains URL samples labeled as spam or legitimate with the following characteristics:
- **URL**: Raw URL strings for classification
- **is_spam**: Binary labels (True/False) indicating spam status

The data is automatically downloaded from the 4GeeksAcademy NLP tutorial repository and processed for analysis.


## Learning Objectives

### 1. **Text Preprocessing & Feature Engineering**
   - URL cleaning and normalization
   - TF-IDF vectorization techniques
   - Feature selection and optimization

### 2. **Support Vector Machine Implementation**
   - Baseline SVC model development
   - Hyperparameter optimization using GridSearchCV
   - Pipeline creation with TfidfVectorizer + SVC
   - Cross-validation and performance evaluation

### 3. **Recurrent Neural Network Development**
   - Sequential model architecture
   - Text tokenization and sequence processing
   - LSTM/GRU implementation for URL classification
   - Neural network optimization techniques

### 4. **Model Evaluation & Comparison**
   - Cross-validation strategies
   - Confusion matrix analysis

### 5. **Advanced NLP Techniques**
   - Stop word filtering
   - Text normalization methods
   - Feature importance analysis


## Technologies Used

- **Python 3.11**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms and tools
- **TensorFlow**: Deep learning framework for RNN implementation
- **NLTK**: Natural language processing toolkit
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter**: Interactive development environment


## Contributing

This is an educational project. Contributions for improving the analysis, adding new models, or enhancing documentation are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request
