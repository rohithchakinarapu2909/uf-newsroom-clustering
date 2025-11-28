# UF Newsroom Article Clustering Project

This project applies NLP and machine learning techniques to analyze and cluster **1,000+ University of Findlay Newsroom articles**.  
Using **Word2Vec, GloVe, and BERT embeddings**, along with **KMeans** and **Hierarchical Clustering**, the project reveals thematic patterns in institutional communication.

---

## 🚀 Project Goals
- Identify dominant themes in UF Newsroom articles.
- Compare multiple embedding techniques.
- Evaluate cluster quality using Silhouette Score and Davies–Bouldin Index.
- Generate PCA, t-SNE, and UMAP visualizations for interpretability.
- Build reproducible notebooks showcasing end-to-end NLP processing.

---

## 🧠 Techniques & Tools Used
### **Embeddings**
- Word2Vec  
- GloVe  
- BERT (Sentence Transformers)

### **Clustering**
- KMeans  
- Hierarchical Clustering  

### **Evaluation**
- Silhouette Score  
- Davies–Bouldin Index  

### **Visualization**
- PCA  
- t-SNE  
- UMAP  

---

## 📁 Repository Structure
📂 UF Newsroom Clustering
│
├── UFNewspapersScrapping.ipynb # Scraping 1,000+ UF Newsroom articles
├── UFNewspapersfinal.ipynb # Preprocessing, embeddings, clustering & evaluation
│
├── visuals/ # PCA, t-SNE, UMAP images (to be added)
│
└── README.md


---

## 🔍 Key Insights
- Each embedding method generated unique yet meaningful clusters.
- PCA, t-SNE, and UMAP plots show strong separations between major themes.
- Silhouette and DBI metrics were compared to choose the best clustering configuration.
- The project provides insight into UF’s communication strategies, academic themes, campus events, research focus areas, and student achievements.

---

## 📊 Future Enhancements
- Build an interactive dashboard for exploring clusters  
- Automate scraping + preprocessing as a pipeline  
- Expand dataset with additional UF communication sources  

---

## 🧑‍💻 Author
**Rohith Chakinarapu**  
Master’s in Applied Security & Analytics  
University of Findlay  

