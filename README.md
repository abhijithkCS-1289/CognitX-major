# STALKER

## Full project name

STALKER: A System for Tracking Affected Learning Knowledge, Erasure & Reporting

## Project description

STALKER is an academic prototype for tracking the relationship between individual training records, dataset versions, training runs, and machine-learning model versions.

The first MVP focuses on identifying which model was trained using a selected record. Future work may include deletion requests, retraining, model comparison, and technical report generation.

## Problem

Organizations may not know which trained AI models used a particular data record because they may not maintain a clear connection between records, dataset versions, training runs, and model versions.

## MVP workflow

Dataset registration
→ Record-ID generation
→ Dataset versioning
→ Model training
→ Automatic lineage capture
→ Record-to-model search

## Technology stack

- Python
- Streamlit
- SQLite
- pandas
- scikit-learn
- joblib
- Git and GitHub

## Current status

The project is currently in the requirements and system-design stage. Implementation of the dataset-registration and lineage-tracking MVP is planned next.

## Scope limitations

- The prototype will use public, fake, or de-identified data.
- It will test selected machine-learning models.
- It will not provide legal certification.
- It will not guarantee complete removal of data influence.
- Advanced machine unlearning is future work.
