# 🌟 Vibe Matcher – AI-Powered Fashion Recommendation System

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![OpenAI](https://img.shields.io/badge/OpenAI-Embeddings-412991?logo=openai)
![Status](https://img.shields.io/badge/Status-Prototype-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
![Made with Love](https://img.shields.io/badge/Made%20With-Love-red)

---

## 🧠 Project Overview

**Vibe Matcher** is an AI-powered mini recommendation system that uses **text embeddings and cosine similarity** to match user vibe descriptions with the most relevant fashion products. It demonstrates how AI can understand natural-language style preferences and return top-3 recommendations.

---

## 🎯 Objective

- Accept vibe input from the user  
- Convert vibe text into an embedding  
- Generate embeddings for product descriptions  
- Compute cosine similarity  
- Rank all products based on similarity  
- Display the top-3 recommendations  
- Test multiple vibes and measure latency  

---

## 🗂️ Notebook Highlights

### ✅ 1. Data Preparation
A small mock dataset of fashion products is created with:
- Product Name  
- Description  
- Vibe Tags  

The data is stored in a Pandas DataFrame for later embedding and matching.

---

### ✅ 2. Embedding Generation
Using the **OpenAI Embedding Model**, the notebook converts:
- Product descriptions  
- The user's vibe input  

into high-dimensional vectors.  
These embeddings capture semantic meaning and stylistic context.

---

### ✅ 3. Cosine Similarity Matching
Using scikit-learn’s `cosine_similarity`, the system:
- Compares the user vibe vector with each product vector  
- Computes similarity scores (0 to 1)  
- Sorts scores in descending order  
- Selects and displays the top-3 closest matches  

---

### ✅ 4. Testing & Evaluation
Several vibe prompts are tested, such as:
- “energetic urban chic”  
- “soft pastel aesthetic”  
- “boho holiday vibe”  
- “minimal cozy winter look”  

Results include:
- Product names  
- Similarity scores  
- Latency measurements  
- Quality evaluation (good if similarity ≥ 0.7)

---

### ✅ 5. Edge Case Handling
The notebook includes:
- Missing API key detection  
- Handling empty or invalid user input  
- Fallback output when similarity scores are too low  

---

### ✅ 6. Reflection
The notebook concludes with:
- Observations on accuracy  
- Strengths and weaknesses  
- Challenges with vibe matching  
- Suggestions for future enhancements  

---

## 🔮 Future Improvements

- Add product images  
- Integrate a vector database (Pinecone, ChromaDB)  
- Build an API using Flask or Django  
- Create a React frontend for vibe searching  
- Use a larger real-world fashion dataset  
- Add filters like style, color, category, price  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Python** | Core logic & data processing |
| **Pandas** | Dataset creation & manipulation |
| **NumPy** | Vector operations |
| **Scikit-Learn** | Cosine similarity |
| **OpenAI API** | Embedding generation |
| **Jupyter Notebook** | Development environment |

---

## 📂 Repository Structure

