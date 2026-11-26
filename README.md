# Spotify Mood Clustering 

**A Hierarchical Clustering Approach to Music Mood Analysis Using Spotify Audio Features**

##  Project Overview

This project is developed as a final project for **CS115 – Mathematics for Computer Science**.

The project explores the application of **Hierarchical Clustering**, an unsupervised machine learning algorithm, to group Spotify songs based on their audio features and discover potential music mood patterns.

Using a sample Spotify dataset, we investigate the relationships between audio characteristics and how songs can be organized into different clusters that represent distinct musical moods.

The project focuses on understanding the mathematical foundations of hierarchical clustering, implementing the algorithm, evaluating clustering results, and interpreting the characteristics of each cluster.

##  Project Objectives (modify later)

- Explore and understand Spotify audio features.
- Perform data inspection, preprocessing, and exploratory data analysis (EDA).
- Apply Hierarchical Clustering to group songs based on their audio characteristics.
- Experiment with different linkage methods and clustering parameters.
- Evaluate clustering performance using appropriate evaluation metrics.
- Interpret the resulting clusters and investigate their potential relationships with music moods.
- Visualize and analyze the clustering results.

##  Dataset (modify later)

This project uses a sample dataset containing Spotify tracks and their corresponding audio features.

Some relevant audio features may include:

| Feature | Description |
|---|---|

*Note: The actual features used will depend on the selected dataset and preprocessing results.*

##  Methodology

The project follows these main stages:

1. **Data Inspection:** Examine dataset structure, data types, missing values, and duplicates.
2. **Data Preprocessing:** Clean the dataset, select relevant audio features, and normalize or standardize numerical variables.
3. **Sampling:** Select a representative sample for computational efficiency.
4. **Exploratory Data Analysis:** Analyze feature distributions, correlations, and relationships between audio characteristics.
5. **Hierarchical Clustering:** Apply agglomerative hierarchical clustering to group Spotify tracks.
6. **Experiments and Evaluation:** Compare different linkage methods, distance metrics, and clustering configurations.
7. **Cluster Interpretation:** Analyze cluster characteristics and explore their potential music mood representations.

##  Technologies & Libraries

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, SciPy
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

##  Repository Structure

```text
spotify-mood-clustering/
│
├── data/
│   ├── raw/                 # Original dataset
│   ├── processed/           # Cleaned and preprocessed data
│   └── sampled/             # Sampled dataset for clustering
│
├── notebooks/
│   ├── 01_data_inspection.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_sampling.ipynb
│   ├── 04_eda.ipynb
│   ├── 05_hierarchical_clustering.ipynb
│   ├── 06_experiments.ipynb
│   └── 07_cluster_interpretation.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── hierarchical.py
│   ├── evaluation.py
│   └── visualization.py
│
├── experiments/
│   └── experiment_results.csv
│
├── outputs/
│   ├── figures/
│   └── cluster_assignments.csv
│
├── report/
│   ├── theory.md
│   └── final_report.md
│
├── requirements.txt
├── .gitignore
└── README.md
```

##  Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/<username>/spotify-mood-clustering.git
cd spotify-mood-clustering
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate the environment:

**Windows:**
```bash
venv\Scripts\activate
```

**macOS / Linux:**
```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebooks

```bash
jupyter notebook
```

Open the notebooks in the `notebooks/` directory and execute them in numerical order, starting from data inspection.

*Note: Make sure the required dataset files are placed in the appropriate `data/` directories before running the notebooks.*

##  Expected Outputs 

The project aims to produce:

- Statistical summaries and visualizations of Spotify audio features.
- Dendrograms illustrating hierarchical relationships between songs.
- Clustering results using different linkage methods.
- Evaluation metrics for comparing clustering configurations.
- Visualizations of the resulting clusters.
- A CSV file containing cluster assignments for sampled Spotify tracks.
- Interpretations of cluster characteristics and their potential mood patterns.

##  Team Members

**Course:** CS115 – Mathematics for Computer Science  
**Project:** Spotify Mood Clustering  
**Institution:** University of Information Technology - VNUHCM  
**Class code:** CS115.R11

| No. | Full Name | Student ID |
|---|---|---|
| 1 | Phan Thanh My Huyen | 25520753 |
| 2 | [Member 2] | [Student ID] |
| 3 | [Member 3] | [Student ID] |
| 4 | [Member 4] | [Student ID] |

## 📚 References (modify later)

- Spotify Web API Documentation: https://developer.spotify.com/documentation/web-api
- Scikit-learn – Hierarchical Clustering: https://scikit-learn.org/stable/modules/clustering.html#hierarchical-clustering
- SciPy – Hierarchical Clustering: https://docs.scipy.org/doc/scipy/reference/cluster.hierarchy.html

##  Acknowledgements

This project is developed as part of the final coursework for CS115 – Mathematics for Computer Science.

We would like to thank our instructor for the guidance and knowledge provided throughout the course.

---

*This project is intended for educational and academic purposes.*
