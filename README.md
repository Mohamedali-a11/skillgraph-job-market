 🕸️ SkillGraph

Analyse du marché de l'emploi Data à partir de 668 704 offres : classification de postes, recommandation de compétences et Graph RAG.

Ce que fait le projet
- **Classification** du poste à partir du titre : TF-IDF + régression logistique (accuracy 0,87, F1 macro 0,871)
- **Embeddings** de 235 compétences avec Sentence-BERT (MiniLM, 384 dim.)
- **Graphe de connaissances** (postes, compétences, entreprises) avec NetworkX et détection de 4 communautés (Louvain)
- **Recommandation de compétences** avec un GNN GraphSAGE (AUC test 0,915)
- **Graph RAG** : faits extraits du graphe + LLM Qwen2.5-1.5B
- **Démo interactive** avec Gradio

🛠️ Skills
Python · NLP · TF-IDF · Sentence-BERT · KMeans · Graph Neural Networks (GraphSAGE) · NetworkX · Louvain · RAG / Graph RAG · PyTorch Geometric · scikit-learn · Hugging Face · Gradio · Google Colab

Utilisation
Ouvre `SkillGraph.ipynb` dans Google Colab et fournis le dataset `data_jobs.csv`.

Auteur
Mohamed Ali Oueslati, élève ingénieur à ESPRIT
[LinkedIn](https://linkedin.com/in/med-ali-oueslati-2212603ab)
