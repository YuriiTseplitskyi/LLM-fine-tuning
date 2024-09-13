
# Sentiment Analysis

## Overview

This project focuses on sentiment analysis of Twitter posts datasets. The project includes data preprocessing, model training, hyperparameter tuning, and evaluation.

## Project Structure

```plaintext
Sentiment Analysis/
├── .venv/                                  # Virtual environment
├── data/                                   # Data files
│   │
│   ├── twitter_test.csv                    # Raw data files
│   ├── twitter_train.csv                    
│   │                             
│   ├── cleaned/                            # Cleaned datasets
│   │   ├── test.csv                                     
│   │   └── train.csv                     
├── logs/                                   # Training and tuning logs
│   ├── baseline/                           
│   ├── final_model/                        
│   ├── hyperparam_tuning/                   
│   ├── prompt_tuning/                      
│   │   ├── prompt_tuning_0/                
│   │   ├── prompt_tuning_1/                
│   │   └── prompt_tuning_2/                
│   └── unfrozen_layers/                    
├── notebooks/                              # Jupyter notebooks for experiments
│   ├── baseline.ipynb                      
│   ├── fine_tuning.ipynb                   
│   └── text_preprocessing.ipynb            
├── .gitignore                                                            
├── paper.pdf                               # Project documentation in PDF format
├── README.md                               # Project README file
└── requirements.txt                        # Python dependencies
```


## Usage

1. **Data Preprocessing**:
    - Run the `text_preprocessing.ipynb` notebook in the `notebooks/` directory to clean and preprocess the data.

2. **Model Training**:
    - Use `fine_tuning.ipynb` for training and fine-tuning models.
    - The baseline model can be found in `baseline.ipynb`.

3. **Model Evaluation**:
    - Logs for different models and their evaluations can be found in the `logs/` directory.

4. **Experiment Tracking**:
    - Experiment logs for baseline, hyperparameter tuning, prompt tuning, and models with unfrozen layers are stored in the respective subdirectories under `logs/`.
   

## Documentation
- Additional documentation and project insights can be found in the `paper.pdf` files.

