# medical_chatbot

This project focused on developing an intelligent medical chatbot designed to assist doctors by summarizing patient complaints and medical histories. The motivation behind the project is to address the challenge of handling large volumes of patient data efficiently, reducing the time doctors spend manually reviewing patient notes, and improving the overall patient experience.

We implemented a Natural Language Processing pipeline using the T5 model to generate concise summaries of patient problems based on raw input text. The project involved fine-tuning the T5 transformer model on a medical dataset consisting of patient descriptions, complaints, and diagnostic notes. We worked with 250,000 patient descriptions so that the model could understand what patients want when they are sick. The chatbot takes in a patient's problem description, processes it, and returns a summary. Based on that summary, the model calls an API through Streamlit apps to help the patient understand what needs to be done.

This project not only gives patients suggestions but also stores their past information. In our body, one problem is often related to other problems. So, based on the patient's previous issues, the chatbot provides feedback. It not only helps the patient but also assists doctors by informing them of the patient's previous conditions. This comprehensive approach enhances the quality of care and enables more informed decision-making.


## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         medical_chatbot and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── medical_chatbot   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes medical_chatbot a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------
## Setup Instructions

To run the code properly, you need to install the required dependencies from the `requirements.txt` file by using the following command:

```bash
pip install -r requirements.txt
```


After installing the dependencies, navigate to the notebooks folder and download the .ipynb file.

For the dataset, you can download it from the following Google Drive link:
https://drive.google.com/drive/folders/1v6KRSdGiOeqN2Slg9CyqTZWFc07XPNR2?usp=share_link



