# Natural Language Processing Laboratory

This repository contains the practical implementations performed as part of the Natural Language Processing Laboratory.

## Student Details

| Detail | Information |
|---|---|
| Name | Araib Khan |
| Course | B.Tech CSE (Artificial Intelligence) |
| Subject | Natural Language Processing Laboratory |
| Institution | Noida Institute of Engineering and Technology |
| University | Dr. A.P.J. Abdul Kalam Technical University |

## Tools and Technologies

- Python
- Google Colab
- NLTK
- spaCy
- Scikit-learn
- TensorFlow
- Hugging Face Transformers

## Practical List

| S.No. | Practical | CO | Notebook |
|---:|---|---|---|
| 1 | Tokenization of Sentences and Words using NLTK and spaCy | CO1 | [Practical 1](./NLP_Practical_01_Tokenization.ipynb) |
| 2 | Stemming and Lemmatization on Sample Text | CO1 | [Practical 2](./NLP_Practical_02_Stemming_Lemmatization.ipynb) |

## Practical 1 — Tokenization

### Objective

To perform sentence tokenization and word tokenization on a given text using NLTK and spaCy.

### Libraries Used

- NLTK
- spaCy
- Python

### Description

This practical demonstrates:

- Sentence tokenization using NLTK
- Word tokenization using NLTK
- Sentence tokenization using spaCy
- Word tokenization using spaCy

### Result

The given text was successfully tokenized into sentences and words using both NLTK and spaCy.

## Practical 2 — Stemming and Lemmatization on Sample Text

### Objective

To perform stemming and lemmatization on a sample text using NLTK and spaCy and compare their results.

### Theory / Concept

Stemming and lemmatization are important text normalization techniques used in Natural Language Processing.

**Stemming** reduces words to a root-like form by removing prefixes or suffixes. The resulting form may not always be a valid dictionary word.

**Lemmatization** converts a word into its meaningful base or dictionary form using linguistic information.

For example:

| Word | Stemmed Form | Lemmatized Form |
|---|---|---|
| studying | studi | study |
| studies | studi | study |
| studied | studi | study |

### Libraries / Tools

- Python
- NLTK
- spaCy
- Porter Stemmer
- WordNet Lemmatizer

### Implementation Overview

The notebook performs:

- Word tokenization of the sample text
- Stemming using NLTK's Porter Stemmer
- Lemmatization using NLTK's WordNet Lemmatizer
- Lemmatization using spaCy
- Comparison of stemming and lemmatization results

### Expected Output

The notebook displays the original words, stemmed words, lemmatized words, and a comparison between the different normalization techniques.

### Learning Outcome

This practical demonstrates how stemming and lemmatization reduce different word forms to a common base representation and highlights the linguistic difference between the two techniques.

### Result

Stemming and lemmatization were successfully performed on the given sample text using NLTK and spaCy. The results demonstrated that stemming produces root-like truncated forms, whereas lemmatization attempts to produce meaningful base forms.

### Notebook

[Open Practical 2 Notebook](./NLP_Practical_02_Stemming_Lemmatization.ipynb)

---

## Environment

All practicals are implemented and tested using Google Colab.

---

## Author

**Araib Khan**

B.Tech CSE (Artificial Intelligence)
