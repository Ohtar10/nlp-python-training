# NLP with Python training

This reppository contains my solutions and experiments while doing the Udmy course: https://www.udemy.com/nlp-natural-language-processing-with-python/

## Requirements

* Conda
* Python 3.6 or above

## Setup
Create the conda environment using the provided file: `nlp_course_env.yml`:
```bash
$ conda env create -n <custom-env-name> --file nlp_course_env.yml
```

## Start jupyter notebook
1. Activate the environment: `conda activate <custom-env-name>`
2. Start jupyter: `jupyter notebook`

## Working with spacy
To work with spacy you first need to download the language libraries depending on the language you are going to work. For this you need to do the following:
1. Activate the environment: `conda activate <custom-env-name>`
2. Install a language: `python -m spacy download <lang>` where `lang` can be any of `en`, `es`, etc.

You should see a download starts and at the end the message: `You can now load the model via spacy.load('en')`
