# Bioactivity Prediction App for Acetylcholinesterase Inhibition

## Overview

This repository contains the code and documentation for the Bioactivity Prediction App, a tool designed to assist researchers in identifying potential inhibitors of acetylcholinesterase, an enzyme vital to nerve function and a key target for neurodegenerative disease treatments like Alzheimer's.

The app leverages QSAR (Quantitative Structure-Activity Relationship) modeling and molecular docking techniques to predict the inhibitory potential of various compounds on acetylcholinesterase. It provides a user-friendly interface for researchers to input chemical structures and obtain predictive analytics on enzyme inhibition.

## Research Foundation

This project was inspired by the research paper *"Probing the Origins of Human Acetylcholinesterase Inhibition via QSAR Modeling and Molecular Docking,"* which explores the inhibition mechanisms of acetylcholinesterase using computational methods. The app recreates and builds upon the models described in the paper to offer an accessible tool for further research.

You can read the full research paper [here](https://peerj.com/articles/2322/)).

## Features

- **QSAR Modeling:** Predicts the activity of chemical compounds based on their molecular structure.
- **Molecular Docking:** Simulates the interaction between acetylcholinesterase and potential inhibitors.
- **User-Friendly Interface:** Allows easy input of chemical structures and retrieval of predictive data.

## Installation

1.Clone the repository

2. Usage:
Open the bioactivity_prediction_app.ipynb file in Jupyter Notebook.
Execute the cells to build and run the model on your system.

3.Launch the App:
After running the Jupyter Notebook, launch the app using the command: streamlit run app.py

4.Upload .txt file containing the chemical structures to predict

5.Retrieve Predictive Data

## Acknowledgements
This project was developed with inspiration and guidance from various sources. Special thanks to [Data Professor](http://youtube.com/dataprofessor) for his invaluable educational content on data science and bioinformatics, which significantly contributed to the development of this app.
