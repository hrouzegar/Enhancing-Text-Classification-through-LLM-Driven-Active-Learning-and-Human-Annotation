Code Repository for "Enhancing Text Classification through LLM-Driven Active Learning and Human Annotation"
Overview
This repository contains the Jupyter Notebook (.ipynb) files for the experiments and analyses presented in our paper. It includes distinct codes for each dataset, as well as scripts for Few-Shot and Zero-Shot learning methods, API connections, prompt designs, and result visualization.

Datasets
Our study utilizes three distinct datasets:

Fake News Dataset: This dataset includes annotations from GPT-3.5. However, for replicating our experiments, you can ignore these columns.
Movie Genre Dataset: Similar to the Fake News dataset, it includes GPT-3.5 annotations which are not necessary for replication.
IMDB Movies Dataset: This dataset also contains additional GPT-3.5 annotations. Ignore these for experiment replication.
Each dataset has a unique structure and characteristics, detailed in the corresponding Jupyter Notebook files.

Code Files
Dataset-Specific Codes
Fake News Code: fake_news_code.ipynb

Purpose: To apply the active learning model to the Fake News dataset.
Customization: Requires minor adjustments for different methods discussed in the paper.
Movie Genre Code: movie_genre_code.ipynb

Designed for the Movie Genre dataset with similar customization requirements.
IMDB Movies Code: imdb_movies_code.ipynb

Tailored for the IMDB Movies dataset with slight modifications as per the discussed methods.
Few-Shot and Zero-Shot Learning Codes
Few-Shot Learning Code: few_shot_learning.ipynb

Demonstrates the implementation of Few-Shot learning methods.
Details on API connection and prompt design.
Zero-Shot Learning Code: zero_shot_learning.ipynb

Illustrates the Zero-Shot learning approach.
Includes API connection instructions and prompt formulation.
Visualization Code
Plotting Results: plot_results.ipynb
Used for visualizing the results of the experiments.
Provides various plotting functions and styles for effective representation.
Usage
To replicate the experiments or to conduct new ones using the provided codes:

Choose the respective notebook file for the dataset you are interested in.
If necessary, make minor adjustments to the code based on the methods discussed in the paper.
For Few-Shot and Zero-Shot learning approaches, refer to the corresponding notebooks for detailed guidelines on API connections and prompt designs.
Use the plot_results.ipynb for visualizing your findings.
Note
The annotations from GPT-3.5 in the datasets are for additional insights but are not essential for replicating the experiments described in our paper.
Ensure you have the necessary packages and environments set up as per the requirements mentioned at the beginning of each notebook.
