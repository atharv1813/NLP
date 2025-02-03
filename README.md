---

# NLP-Based Dating Partner Finder

This project utilizes Natural Language Processing (NLP) techniques to analyze the OkCupid dataset, aiming to recommend potential partners based on shared interests and compatibility.

## Overview

By processing user profiles from the OkCupid dataset, this system identifies key attributes and preferences to suggest compatible matches, enhancing the dating experience through data-driven insights.

## Dataset

The analysis is based on the OkCupid profiles dataset, which can be found here: [OkCupid Profiles Dataset](https://www.kaggle.com/datasets/andrewmvd/okcupid-profiles?select=okcupid_profiles.csv)

## Repository Contents

- `dating-site-Copy1.ipynb`: Jupyter Notebook containing the data analysis and NLP processing steps.
- `male.txt` & `female.txt`: Text files possibly containing processed data or specific insights related to male and female profiles, respectively.

## Getting Started

To explore or replicate the analysis:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/atharv1813/NLP.git
   cd NLP
   ```

2. **Install Dependencies**:
   Ensure you have Python installed. It's recommended to use a virtual environment.
   ```bash
   pip install pandas numpy nltk scikit-learn
   ```

3. **Download the Dataset**:
   Place the `okcupid_profiles.csv` file in the repository directory.

4. **Run the Jupyter Notebook**:
   Launch Jupyter Notebook and open `dating-site-Copy1.ipynb` to view and execute the analysis steps.

## Key Features

- **Text Preprocessing**: Cleaning and preparing textual data for analysis.
- **Feature Extraction**: Identifying significant attributes from user profiles.
- **Compatibility Scoring**: Calculating similarity scores to recommend potential matches.

## Future Enhancements

- **Model Optimization**: Improving the recommendation algorithm for better accuracy.
- **User Interface**: Developing a user-friendly interface for real-time matchmaking.
- **Expanded Datasets**: Incorporating additional datasets to enhance recommendation diversity.

---
