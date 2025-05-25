# Computational Astrobiology
## Masters in Astrophysics and Space Science - Belgrade Semester 2

This module explores the principles and techniques of Machine Learning, applying them to Astrophysics through a range of projects. Assessment is based on a presentation covering both the tutorial material and project work—both of which are included in this repository.

## Topics covered in the tutorials:

- Logistic Regression
- Naive Bayes
- Support vector machines
- Decision Trees
- Random Forests
- Probabilistic Random Forest
- Principal Component Analysis
- K nearest neighbours
- K-fold Cross Validation
- Feed forward Neural Networks
- Convolutional Neural Networks
- Transformers

## Project: Detecting Technosignatures with SOMs & Doppler Drift Search

This project focuses on analyzing real Breakthrough Listen (BL) radio astronomy data, using Self-Organizing Maps (SOMs) for signal clustering and TurboSETI for Doppler drift detection. The goal is to precluster signals, extract anomalies, and search for potential technosignatures.

The project had to be split across three notebooks due to different packages requiring different environments. 

- Part 1 accesses and processes the BL radio astronomy data. Then deploys a SOM to identify outliers and lastly saves these examples to a .h5 file.

- Part 2 reads the file from part 1, and applyes TurboSETI for doppler drift detection. A waterfall plot is made to visualise the result.

- Part 3 demonstrates the method for filtering out expected Radio Frequency Interference (RFI) by implementing a CNN.


