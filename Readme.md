# GitHub Developer Collaboration Network Analysis Using Graph Mining and PageRank

## 📌 Project Overview

This project analyzes GitHub developer collaboration networks using graph mining techniques and the PageRank algorithm. It represents developers as nodes and their collaborations as weighted edges to understand network structure and identify influential developers.

The project explores how collaboration frequency and network relationships contribute to developer influence. It also performs graph statistical analysis, degree analysis, PageRank ranking, random sampling, and network visualization.

## 🎯 Objectives

- Represent GitHub developer collaborations as a weighted graph.
- Analyze developer relationships using graph mining techniques.
- Identify influential developers using the PageRank algorithm.
- Calculate graph metrics such as degree, density, and connected components.
- Compare degree centrality and PageRank scores.
- Visualize the developer collaboration network.
- Examine network changes through random sampling.

## 📊 Dataset

The project uses a sample GitHub developer collaboration dataset inspired by the GitSED (GitHub Socially Enhanced Dataset) context.

The prototype dataset is manually constructed for analysis and demonstration.

### Dataset Attributes

| Attribute             | Description                                     |
| --------------------- | ----------------------------------------------- |
| `developer_1`         | First developer in a collaboration              |
| `developer_2`         | Second developer in a collaboration             |
| `collaboration_count` | Number of collaborations between the developers |

### Dataset Statistics

- Number of Developers: 11
- Number of Collaboration Edges: 17
- Total Collaboration Interactions: 107

## 🛠️ Technologies Used

- **Python** – Core programming language
- **Pandas** – Data manipulation and preprocessing
- **NetworkX** – Graph construction and network analysis
- **Matplotlib** – Graph visualization
- **NumPy** – Numerical computation
- **Google Colab** – Development and execution environment

## ⚙️ Methodology

The project follows these steps:

1. **Data Preparation:** Load and organize developer collaboration records.
2. **Data Preprocessing:** Handle missing values, duplicates, and invalid records.
3. **Exploratory Data Analysis:** Examine collaboration patterns and dataset statistics.
4. **Graph Construction:** Create a weighted graph using NetworkX.
5. **Graph Statistical Analysis:** Calculate network metrics.
6. **Degree Analysis:** Identify highly connected developers.
7. **PageRank Analysis:** Calculate developer influence scores.
8. **Comparative Analysis:** Examine the relationship between degree and PageRank.
9. **Network Visualization:** Visualize developer relationships.
10. **Random Sampling:** Analyze a subset of the collaboration network.
11. **Result Export:** Generate developer rankings and export results to CSV.

## 🧠 Key Concepts

### Graph Mining

Analyzes relationships and structural patterns in network-based data.

### Weighted Graph

Represents developers as nodes and collaborations as edges, with edge weights indicating collaboration frequency.

### PageRank Algorithm

Identifies influential developers by considering both their network connections and the importance of connected developers.

### Degree Analysis

Measures the number of direct connections associated with each developer.

### Network Density

Measures the proportion of existing connections relative to all possible connections.

## 📈 Results and Findings

The prototype analysis provides the following results:

- The collaboration network contains 11 developers and 17 edges.
- The network has a density of approximately 0.3091.
- The average degree is approximately 3.09.
- All developers belong to a single connected component.
- dev_D achieved the highest PageRank score of approximately 0.1189.
- Degree and PageRank showed a strong positive correlation of approximately 0.8918.

These findings demonstrate how graph mining and PageRank can be used to analyze developer collaboration relationships and network influence.

*Note: Results are based on the sample dataset and should not be generalized to the entire GitHub developer community.*

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Open the project notebook in Google Colab.
2. Run the notebook cells sequentially.
3. Execute the preprocessing and graph construction steps.
4. Perform graph analysis and PageRank calculations.
5. View the visualizations and generated results.

### Option 2: Local Environment

Clone the repository:

```bash
git clone https://github.com/<your-username>/<your-repository-name>.git
```

Navigate to the project directory:

```bash
cd <your-repository-name>
```

Install the required dependencies:

```bash
pip install pandas numpy networkx matplotlib
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and execute the cells.

## 🔮 Future Enhancements

- Integrate real-time GitHub collaboration data using the GitHub API.
- Analyze larger developer collaboration networks.
- Implement community detection algorithms such as Louvain.
- Explore additional centrality measures.
- Develop an interactive network visualization dashboard.
- Compare PageRank results across different datasets.

## 📚 References

- Page, L., Brin, S., Motwani, R., and Winograd, T. — *The PageRank Citation Ranking: Bringing Order to the Web.*
- Leskovec, J., Rajaraman, A., and Ullman, J. D. — *Mining of Massive Datasets.*
- GitSED — GitHub Socially Enhanced Dataset.
- NetworkX Documentation — [https://networkx.org/](https://networkx.org/)
- GitHub Documentation — [https://docs.github.com/](https://docs.github.com/)

## 👨‍💻 Project Information

**Project Title:** GitHub Developer Collaboration Network Analysis Using Graph Mining and PageRank

**Domain:** Data Mining | Graph Mining | Social Network Analysis

**Subject:** Mining Massive Datasets(MMD)

**Department:** Computer Science and Engineering

**Institution:** K G Reddy College of Engineering and Technology

