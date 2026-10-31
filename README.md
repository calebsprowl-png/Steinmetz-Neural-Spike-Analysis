# Dimensionality Reduction and Clustering of Visual Cortex Neural Activity

## Objective
This project analyzes extracellular neural recordings from the mouse primary visual cortex (VISp) using the Steinmetz dataset (provided via Neuromatch Academy). The goal is to isolate specific neuronal populations and classify them based on their firing patterns over time.

## Methodology
* **Data Extraction & Processing:** Utilized `NumPy` to extract spike times specific to VISp neurons and compute the average firing rates across the neuronal population.
* **Machine Learning / Clustering:** Applied Principal Component Analysis (PCA) using `scikit-learn` (`n_components=2`) to perform dimensionality reduction on the firing rate data. 
* **Visualization:** Plotted the first two principal components using `matplotlib` to visualize distinct functional clusters of neurons based on their electrical activity, incorporating custom aesthetics and explained variance ratio labels for clear data presentation.

## Significance
This pipeline demonstrates a foundational workflow in computational neuroscience: handling large-scale biological datasets, applying matrix mathematics for signal processing, and utilizing unsupervised machine learning to identify hidden biological patterns within neural circuits.
