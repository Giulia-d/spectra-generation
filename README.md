CANOPY-SOIL REFLECTANCE SPECTRA GENERATION USING NEURAL NETWORKS

This project explores the generation of canopy-soil reflectance spectra using neural network-based approaches. It involves training and evaluating different autoencoder architectures to model reflectance spectra and mapping networks to encode and decode reflectance data. The work focuses on optimizing the performance of these models under varying environmental and structural conditions.

Project Overview

	1.	Dataset Preparation:
	•	Loading and splitting of datasets into training, validation, and testing subsets.
	•	Preparation of the parameterized dataset for training.
	2.	Model Architectures:
	•	Training and testing of Fully Connected Autoencoders.
	•	Training and testing of Convolutional Autoencoders.
	•	Mapping network designed to encode parameters into a latent space.
	3.	Evaluation:
	•	Testing the models on canopy-soil reflectance data.
	•	Inspecting performance across different parameters:
	•	Canopy distributions
	•	Chlorophyll content (Cab)
	•	Leaf Area Index (LAI)
	•	Erectophile canopy structures
	4.	Performance Metrics:
	•	Evaluation based on wavelength-specific errors.
	•	Analysis of the mean error under different configurations.

Features

	•	End-to-end pipeline for dataset preparation, training, testing, and evaluation.
	•	Comparative analysis of different neural network architectures.
	•	Insightful analysis of how environmental and structural parameters influence performance.

Requirements

	•	Python 3.x
	•	Relevant libraries: PyTorch, NumPy, Matplotlib, and other dependencies as specified in the notebook.

Usage

	1.	Run the Notebook:
	•	Open the Reflectance_Spectra_Generetion.ipynb file in Jupyter Notebook or JupyterLab.
	•	Execute cells sequentially to replicate the experiments and visualize results.
	2.	Dataset:
	•	Ensure that the required datasets are prepared and correctly linked before running the notebook.
	3.	Model Training:
	•	Modify hyperparameters or architectures as needed in the respective sections of the notebook.
	4.	Testing and Analysis:
	•	Use the provided test routines to evaluate the trained models.


[Spectra Generaition with Autoencoder.pdf](https://github.com/user-attachments/files/18347545/Denti_final_project_env_imaging.pdf)
