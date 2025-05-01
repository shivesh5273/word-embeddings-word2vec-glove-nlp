# Word Embedding & NLP Practice – Word2Vec, GloVe, spaCy

This project explores modern word vector representations using Word2Vec, GloVe, and spaCy. The focus is on training embeddings, performing analogy reasoning, running PCA visualizations, and comparing sentence similarities across embedding types.

---

## 🔍 Project Breakdown

### 📚 1. NLP Lab Notebooks (Gensim, NLTK, spaCy)
- Studied word vectors, tokenization, syntactic relations, and embeddings.
- Lab outputs are included in HTML format for reference.

### ⚙️ 2. Train Word2Vec & Closest Words Query
- Trained a Word2Vec model using the original `demo-word.sh` script on `text8`.
- Queried the top 10 similar words to a chosen word using the binary/text embedding vectors.

### 🧠 3. Country–Capital Analogy + PCA
- Visualized 4 country–capital pairs on a 2D PCA plot.
- Examined the parallelism between vector relationships.
- Used GoogleNews pretrained embeddings.

### 📊 4. Analogy Reasoning with GloVe
- Repeated PCA analysis using 300d GloVe vectors.
- Compared angle preservation and directional behavior across models.

### ✍️ 5. Sentence Similarity (spaCy + Word2Vec + GloVe)
- Imported pre-trained Word2Vec and GloVe vectors into spaCy.
- Compared semantic similarity between custom sentence pairs using:
  - spaCy’s large English model
  - Word2Vec
  - GloVe
  - GoogleNews vectors

---

## 📁 Files Included

- `word2vec-train-and-query-results.html`
- `word2vec-country-capital-analogy-pca.html`
- `glove-analogy-parallelism-pca.html`
- `embedding-similarity-spacy-word2vec-glove.html`
- `lab-gensim-word2vec.html`, `lab-nltk-text-processing.html`, `lab-spacy-nlp-workflow.html`
- `word2vec-glove-nlp-overview.docx`

---

## 🛠 Tools & Libraries

- Python 3.x  
- Gensim  
- spaCy  
- NLTK  
- Scikit-learn PCA  
- Word2Vec / GloVe / GoogleNews vectors

---

> A strong practical foundation in embeddings, NLP pipelines, and reasoning with vector spaces.
