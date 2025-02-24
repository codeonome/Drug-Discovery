# Drug-Discovery
A computational Biology model for Drug discovery.

# QSAR Modeling of BChe Inhibitors

# Overview

This is a project where we build and analyze predictive models for drug discovery. In this part, we focus on quickly building and comparing several regression models for predicting the biological activity of butyrylcholinesterase (BChe) inhibitors using the lazypredict library in Python.

# Why BChe?

Butyrylcholinesterase (BChe) is an enzyme that plays a crucial role in various biological processes and has been studied for its potential involvement in neurodegenerative diseases such as Alzheimer's. Targeting BChe with inhibitors can be useful in drug discovery efforts aimed at developing treatments for these diseases. Compared to other targets, BChe provides a larger dataset of tested compounds, making it ideal for building robust predictive models.

# Project Structure

Previous Parts Recap:

Collected biological activity data from the ChEMBL database and preprocessed it for analysis.

 Calculated Lipinski molecular descriptors and performed exploratory data analysis (EDA) using box plots and scatter plots.

 Focused on BChe as the target protein, computed molecular descriptors using the PADEL-Descriptor software, and prepared the dataset.

 Built a regression model using computed molecular descriptors to predict pIC50 values (the measure of biological activity).

 Used lazypredict to quickly train and compare multiple regression models for BChe inhibitors.

# Technologies Used

Python

pandas, numpy (Data Handling)

matplotlib, seaborn (Data Visualization)

PADEL-Descriptor (Molecular Descriptor Calculation)

lazypredict (Automated Model Training and Comparison)

