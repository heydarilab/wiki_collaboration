# Codes and Data for the paper "Platform-Driven Collaboration Patterns" published in IEEE T. Comp. Social Systems.

This project includes Jupyter notebooks that analyze the evolution of social network structures of Wikipedia over time. We examine the data from multiple dimensions to provide insights into network characteristics such as centrality, clustering, and shortest path length.

Folder Structure:
notebooks/Wikipedia_NetworkFormation.ipynb: Contains the Jupyter notebook for the formation/construction of the networks.

output/AAS_Tweights24.csv: First output of the NetworkFormation notebook, containing the weight data for all user pairs on Wikipedia with a time threshold of 24 hours.

output/AASnetworks.csv: Dataframe of networks over time for sample Wikipedia topics, along with their characteristics.

notebooks/Wikipedia_NetworkAnalysis.ipynb: Contains the Jupyter notebook for analyzing the network characteristics.

input/AAS_Tweights24.csv: Uses the output from Wikipedia_NetworkFormation as an input.

input/AASnetworks.csv: Uses the output from Wikipedia_NetworkFormation as an input.

Dependencies:
All required libraries are listed in the first cell of each Jupyter notebook. Ensure to install them before running the notebooks.

How to Run:
Run the Wikipedia_NetworkFormation.ipynb Jupyter notebook first to construct the networks.
After completing that, run the Wikipedia_NetworkAnalysis.ipynb notebook to analyze network characteristics.
Ensure that you run the cells sequentially in each notebook to avoid errors.

Data Sources:
The primary data source for this project is the Wikipedia API:
base_url = 'https://en.wikipedia.org/w/api.php'.

All code for parsing editor data from the Wikipedia API can be found in cells 2-4 of the Wikipedia_NetworkFormation.ipynb.

Contributing:
Contributions are welcome! Please submit a pull request or open an issue for any improvements.
