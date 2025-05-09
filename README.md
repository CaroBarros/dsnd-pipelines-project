# Project Title: Data Science Pipeline

This project utilizes data from **StyleSense**, a rapidly growing online women's clothing retailer, to predict whether a customer would recommend a product. The predictive model analyzes a variety of features—numerical, categorical, and textual—including the review text, customer age, product category, department name, high-level division, and the number of customers who found the review helpful. These inputs help determine the likelihood of a product recommendation.

This project is part of **Course 4: Data Science Pipelines** of the **Data Science Nanodegree** by Udacity.

---

## Getting Started

These instructions will help you set up the project and run it locally on your machine for development and testing purposes.

### Dependencies

Make sure you have the following Python libraries installed:

```
pandas  
scikit-learn  
spacy  
notebook  
```

Install them using pip:

```bash
pip install pandas scikit-learn spacy notebook
python -m spacy download en_core_web_sm
```

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/data-science-pipeline.git
cd data-science-pipeline
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open the notebook `project_ml_pipeline.ipynb` located inside the `project_ml_pipelines` folder.

---

## Project Structure

```
project_ml_pipelines/
├── data/
│   └── reviews.csv           # Dataset used for building the ML pipeline
├── project_ml_pipeline.ipynb # Main notebook with full pipeline development
```

### Notebook Features

The notebook includes:
- Data loading and preprocessing
- Feature engineering (including NLP on text reviews)
- Model training and evaluation
- Hyperparameter tuning using GridSearchCV

---

## Built With

* [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis
* [scikit-learn](https://scikit-learn.org/) - Machine learning library
* [spaCy](https://spacy.io/) - Natural language processing
* [Jupyter Notebook](https://jupyter.org/) - Interactive computing environment

---

## License

This project is licensed under the terms of the [MIT License](LICENSE.txt).
