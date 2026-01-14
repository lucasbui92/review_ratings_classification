# Review Rating Classification (Text Analytics Project)

This project explores the impact of different tokenization methods on multi-class
text classification for predicting review ratings (1–5). Two approaches are
compared: traditional tokenization using spaCy lemmatization with TF-IDF, and
subword tokenization using the BERT tokenizer. To isolate the effect of
tokenization, both approaches use the same Logistic Regression classifier.

The project was developed as part of an MSc Artificial Intelligence programme
and focuses on evaluation, comparison, and interpretation of text representations.

## Repository structure

- data/: Training, validation, and test datasets
- review_rating_classification.ipynb: Main notebook for preprocessing, training, and evaluation
- models/: Trained models and corresponding test outputs
- report.pdf: Project report
- presentation.pdf: Presentation slides

## Notes on execution

This project was developed and run in Google Colab, with data and model
artifacts stored on Google Drive. As a result, the notebook includes
Google Drive mounting and path definitions.

To run the notebook locally, paths would need to be adapted to a local
directory structure. The code and results are provided primarily for
demonstration, review, and reproducibility of the analysis.
