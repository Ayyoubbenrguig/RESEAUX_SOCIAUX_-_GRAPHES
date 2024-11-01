
# Social Network Analysis Project

This project explores the analysis of social networks using data from various communities (karate, physicians, tribes) and centrality calculation algorithms. The goal is to analyze interactions within these networks to extract insights about structures and relationships among members.
<p align="center">
  <img src="graphe.jpg" alt="Réseaux sociaux" width="300"/>
</p>

## Project Contents

- **Projet_Reseau sociaux.pdf**: Project report detailing the methodologies used, results obtained, and conclusions.
- **centralite.ipynb**: Jupyter notebook containing code for calculating node centrality in different networks.
- **projet_code.ipynb**: Main Jupyter notebook with analyses and visualizations of the networks.
- **soc-karate.txt, soc-physicians.txt, soc-tribes.txt**: Data files containing relationships between members in different social networks:
  - **soc-karate.txt**: Network of members in a karate club.
  - **soc-physicians.txt**: Network of physicians and their collaborations.
  - **soc-tribes.txt**: Network of relationships among tribes.

## Features

1. **Centrality Calculation**: Node centrality analysis to identify the most influential members in each network.
2. **Network Visualization**: Graphical representation of networks to observe interactions and structures.
3. **Comparative Analysis**: Comparison of different centrality measures (degree, betweenness, closeness) across networks.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks to explore the analyses:
   ```bash
   jupyter notebook centralite.ipynb
   jupyter notebook projet_code.ipynb
   ```

## Usage

This project is designed to be interactively explored via Jupyter notebooks. The centrality analyses and visualizations are set up to run on the provided data, but they can be adapted for other networks as well.

## Contributions

Contributions are welcome! To add new analyses or improve existing code, please create a branch or submit a pull request.

## Author

Ayyoub Benrguig
