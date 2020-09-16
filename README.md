# Benchmarking-ML-Models-for-Predicting-RT

**Author**: Alice Huang - [`alice.huang01@gmail.com`](mailto:alice.huang01@gmail.com)

Click [here](https://docs.google.com/presentation/d/1ftl-RJ2B3qktJaWN6St-0iquw3uPkAqBC0R3YC2Ze7I/edit?usp=sharing) to access the final project presentation slides with diagrams and explanations.

## Background
Retention time (RT), the amount of time a solute takes to pass through a chromatography column, is a feature that is somewhat unique to different small molecules. Because of this, it is a feature that can be used in conjunction with other information in the process of small molecule identification. Another benefit of knowing the retention time of a molecule is that it can be used to differentiate between molecules that have similar spectra but different retention times.

We assume that there is a correlation between molecular structure and RT. If the two are correlated, machine learning can be used to make predictions given input data. In this case, we are making predictions about RT given structural information. The input data used for this project are molecular fingerprints because previous studies have shown that they outperform other molecular descriptors for this task.

## Goal
The goal of this project is to benchmark different machine learning models on retention time prediction performance using the METLIN small molecule retention time (SMRT) dataset. This dataset includes experimentally collected retention times of more than 80,000 small molecules and also includes the associated fingerprints and molecular descriptors.

## The Notebook
Explore the attached Python notebooks to see what exactly was done.
