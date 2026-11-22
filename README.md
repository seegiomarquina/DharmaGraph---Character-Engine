#  DharmaGraph — Ramayana Knowledge Graph & NLP Intelligence Engine

### Exploring the Ramayana Through Data Science, NLP, Semantic Search and Knowledge Graphs

DharmaGraph is an advanced Data Science and Natural Language Processing project that transforms Ramayana-related textual data into an interactive knowledge exploration system.

It combines **Knowledge Graphs, Semantic Search, Graph Analytics, NLP and Character Relationship Intelligence** to explore characters, locations, events and their connections.

The project demonstrates how traditional literary and cultural knowledge can be explored using modern data science techniques.

---

## 🚀 Project Highlights

- **Ramayana Knowledge Graph:** Builds a structured graph of characters, locations, events and relationships.
- **Semantic Verse Search:** Retrieves relevant verses based on meaning rather than exact keyword matching.
- **Ramayana Question Retrieval:** Finds relevant textual evidence for natural-language questions.
- **Character Intelligence:** Examines character connections and graph-based influence metrics.
- **Relationship Path Finder:** Discovers connection paths between characters.
- **Common Connection Analysis:** Identifies entities shared by two characters.
- **Community Detection:** Finds clusters of interconnected entities.
- **Graph Analytics:** Calculates PageRank, Betweenness Centrality, Closeness Centrality and Degree Centrality.
- **Interactive Visualization:** Explores the knowledge graph through an interactive network visualization.

---

## 🧠 Technologies Used

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Natural Language Processing | Sentence Transformers, Scikit-learn |
| Semantic Search | all-MiniLM-L6-v2 |
| Knowledge Graph | NetworkX |
| Visualization | Plotly, Matplotlib, Seaborn |
| Database | SQLite |
| Data Storage | JSON, CSV, NumPy |
| Environment | Google Colab |

---

## 🏗️ Project Architecture

```text
              RAMAYANA TEXTUAL DATA
                       |
                       v
                DATA COLLECTION
                       |
                       v
                 DATA CLEANING
                       |
                       v
              STRUCTURED VERSE DATA
                       |
             +---------+----------+
             |                    |
             v                    v
       NLP PROCESSING       KNOWLEDGE GRAPH
             |                    |
             v                    v
      SEMANTIC EMBEDDINGS   ENTITY RELATIONSHIPS
             |                    |
             v                    v
      SEMANTIC SEARCH       GRAPH ANALYTICS
             |                    |
             +---------+----------+
                       |
                       v
             DHARMAGRAPH INTELLIGENCE
                       |
                       v
              SEARCH & EXPLORATION
```

---

## 📊 Advanced Intelligence Modules

### 1. Semantic Verse Search

Uses Sentence Transformers to generate vector embeddings for textual records.

A user can search using natural-language queries and retrieve semantically similar verses.

Example:

```python
semantic_search(
    "Why did Rama go into exile?",
    top_k=5
)
```

### 2. Ramayana Question Retrieval

Retrieves relevant verse references, translations and explanations for a question.

```python
ask_ramayana(
    "How did Hanuman help Rama find Sita?"
)
```

*This is evidence retrieval, not a generative AI system. Similarity scores indicate relevance, not factual verification.*

### 3. Character Intelligence

Analyzes graph connections and centrality metrics for individual characters.

```python
character_intelligence("Hanuman")
```

### 4. Relationship Path Analysis

Finds the shortest available relationship path between two graph entities.

```python
relationship_path("Rama", "Ravana")
```

### 5. Common Connection Analysis

Identifies shared neighboring entities.

```python
common_connections("Rama", "Hanuman")
```

### 6. Graph Community Detection

Uses NetworkX community detection to identify clusters of connected entities.

### 7. Graph Influence Analytics

Calculates:

- PageRank
- Betweenness Centrality
- Closeness Centrality
- Degree Centrality
- Clustering Coefficient

These metrics measure structural importance within the constructed graph. They do not represent moral importance or canonical ranking.

---

## 📁 Project Structure

```text
DharmaGraph/
│
├── data/
│   ├── ramayana_verses.json
│   └── cleaned_verses.csv
│
├── outputs/
│   ├── plots/
│   ├── graph_nodes.csv
│   ├── graph_edges.csv
│   ├── centrality_metrics.csv
│   ├── graph_communities.csv
│   ├── event_timeline.csv
│   ├── ramayana_knowledge_graph.json
│   ├── ramayana_knowledge_graph.graphml
│   ├── dharmagraph_network.html
│   └── dharmagraph.db
│
├── advanced_outputs/
│   ├── graph_intelligence_metrics.csv
│   ├── graph_communities.csv
│   ├── character_profiles.json
│   ├── verse_embeddings.npy
│   └── validation_report.json
│
├── sql/
│   └── analysis_queries.sql
│
└── README.md
```

*The lightweight GitHub package may omit large regenerable datasets, databases and embedding files. The original notebook contains the processing workflow.*

---

## ⚙️ How to Run the Project

### Step 1 — Open Google Colab

Open [Google Colab](https://colab.research.google.com/).

### Step 2 — Upload the Notebook

Upload the DharmaGraph `.ipynb` notebook.

### Step 3 — Configure Runtime

For semantic embedding generation, select a GPU runtime if available.

### Step 4 — Execute the Notebook

Run the notebook cells in sequence to:

1. Install dependencies.
2. Retrieve and prepare the dataset.
3. Perform exploratory data analysis.
4. Construct the knowledge graph.
5. Generate graph visualizations.
6. Build semantic embeddings.
7. Run character intelligence and graph analytics.
8. Export project outputs.

### Step 5 — Explore the Intelligence Engine

Try the example queries provided in the notebook.

---

## 📚 Dataset and Attribution

The project uses the publicly available **Valmiki Ramayan Dataset**:

[GitHub — Ashutosh-Vijay/Valmiki_Ramayan_Dataset](https://github.com/Ashutosh-Vijay/Valmiki_Ramayan_Dataset)

The repository provides structured Ramayana verse data, including Sanskrit shlokas, transliterations, English translations and explanations.

**Data considerations:**
- The source repository notes that some shlokas may be merged.
- Some translations and explanations may be missing.
- Translation verification is not complete.
- The knowledge graph contains manually curated starter relationships and annotations.

Please consult the original repository's license and attribution requirements before redistributing its contents.

---

## ⚠️ Limitations

- Semantic search retrieves similar textual records; it does not independently verify their accuracy.
- Question answering currently uses retrieval rather than a generative language model.
- Character relationships and event annotations are manually curated starter data, not automatically extracted canonical facts.
- Graph metrics depend on the entities and relationships included in the graph.
- The dataset may contain incomplete or unverified translations.

---

## 🔮 Future Enhancements

- AI-powered relationship extraction from Ramayana texts.
- Retrieval-Augmented Generation (RAG) with verse-level citations.
- Multilingual semantic search across Sanskrit, Hindi and English.
- Advanced interactive character relationship dashboard.
- Automated entity recognition and event extraction.
- Cross-version comparison of Ramayana adaptations.
- Source-aware fact verification and annotation tools.

---

## 🎯 Project Objective

The objective of DharmaGraph is to demonstrate how Data Science and AI techniques can transform large textual collections into structured, searchable and analyzable knowledge systems.

It brings together NLP, semantic retrieval, graph theory and data visualization in one cultural knowledge exploration project.

---

## 👨‍💻 Author

**Aditya Dhage**

Data Science & AI Enthusiast

Skills demonstrated:
- Python
- Data Science
- Natural Language Processing
- Semantic Search
- Knowledge Graphs
- Network Analysis
- Machine Learning
- Data Visualization

---

### ⭐ If you find this project interesting, consider giving the repository a star!

**DharmaGraph — Connecting Stories Through Data.**
