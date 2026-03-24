# colab_speech_project         
# Speech Cluster Analysis Project

[

**Political Speech Analysis** - Detects factual content, emotional manipulation, and religious hate in mixed Hindi-English speeches using NLP clustering.

## 🎯 Project Goals
- Cluster speeches semantically using Sentence-BERT embeddings + KMeans
- Quantify % of **facts**, **emotional manipulation**, **motivation**, & **religious hate** per cluster
- Analyze 10K+ text samples from political speeches
- Build interactive dashboard for trends & insights

## 📊 Key Features
- **Multilingual NLP**: Handles Hindi-English mixed speeches
- **Clustering**: Groups similar speeches (3-8 clusters)
- **Content Detection**:
  - Factual accuracy (zero-shot classification)
  - Emotional manipulation (emotion pipeline)
  - Religious hate speech detection
- **Visualization**: Cluster trends via Plotly/Tableau

## 🛠 Tech Stack
```
Python 3.10+ | Google Colab
├── sentence-transformers (embeddings)
├── scikit-learn (KMeans clustering)
├── transformers (HuggingFace pipelines)
├── NLTK/spaCy (preprocessing)
├── Plotly/Looker Studio (dashboards)
└── Pandas/NumPy (data handling)
```

## 📁 Project Structure
```
colab_speech_project/
├── Speech_Data.ipynb          # Main analysis notebook
├── cleaned_speech.csv         # Preprocessed speeches (10K+ samples)
├── requirements.txt           # Dependencies
├── README.md                 # This file
└── dashboard/                # Plotly visualizations
```

## 🚀 Quick Start (Google Colab)
1. Open [Speech_Data.ipynb](https://github.com/PragzScript/colab_speech_project/blob/main/Speech_Data.ipynb)
2. Upload `cleaned_speech.csv` (column: `cleaned_speech`)
3. Run all cells → **Clusters + % analysis generated**

**Sample Output**:
```
Cluster 0 (Fact-Heavy): 72% factual, 15% emotional, 2% hate
Cluster 1 (Manipulation): 28% factual, 65% emotional, 12% hate
```

## 📈 Results (4-Month Project)
- Processed **10,000+ speeches** via SQL/Pandas/NLTK
- **15+ features** engineered (SHAP explainability +40%)
- **3 risk profiles** via K-Means clustering
- **80% error reduction** in analysis pipeline
- Tableau dashboard for stakeholder insights





