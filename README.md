# Exploring Themes in Makerspaces: A Topic Modeling Analysis
## Introduction
Welcome to the makerspace analysis research project! This repository is dedicated to identifying themes of makerspaces through machine learning and data analysis techniques. By leveraging topic modeling, we aim to understand the missions of makerspaces and explore distinctions between nonprofit and commercial makerspaces. This project is a comprehensive effort to categorize makerspaces based off of both our prior expectations and the topic modeling results.

## Repository Contents
### Makerspace Samples
This CSV file contains data collected from the websites of 237 makerspaces. It includes information on the mission of each makerspace, as well as an identifier "N" for nonprofit or "C" for commercial. This file is imported into the Python and R programs.
### R File on Makerspace Frequencies 
The R Markdown file performs an initial analysis on the prevalence of the themes the research team expected to find among the makerspaces. The frequency examination identifies the most common words within the makerspace descriptions. It also calculates the ratio of keywords, which are lists of words that encapsulate each theme, to total words. This provides a quantitative basis for further topic modeling. The R Markdown file has also been knit to a PDF format for easier readability, and the PDF is included in the repository. 
### Topic Modeling Jupyter Notebook
The Jupyter Notebook implements topic modeling techniques to categorize the makerspace data through various algorithms such as Latent Dirichlet Allocation (LDA), Non-negative Matrix Factorization (NMF), and Correlation Explanation (CorEx). The algorithms identify key topics that the makerspaces can be categorized under, providing insight into underlying themes in how makerspaces present themselves.
