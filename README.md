# Topsis-Text-Summarization on Pre-Trained models
Apply topsis to find the best pre-trained model for Text-Summarization

## Parmeters for evaluation
### ROUGE (Recall-Oriented Understudy for Gisting Evaluation):
ROUGE-N: Measures n-gram overlap between the generated summary and the reference summary.
ROUGE-L: Computes the longest common subsequence between the generated and reference summaries.
ROUGE-W: Evaluates word overlap.
ROUGE-S: Considers skip-bigram overlap.
ROUGE-SU: Takes into account skip-bigram and unigram overlap.

### BLEU (Bilingual Evaluation Understudy):
Measures precision of n-grams in the generated summary compared to the reference summary.

### METEOR (Metric for Evaluation of Translation with Explicit ORdering):
Considers precision, recall, and harmonic mean, taking into account stemming and synonymy.

### CIDEr (Consensus-based Image Description Evaluation):
Evaluates consensus among multiple reference summaries.

### Perplexity:
Measures how well the model predicts the reference summary in terms of likelihood.

### F1 Score:
Examines the precision and recall of the generated summary compared to the reference summary.

### Semantic Similarity Metrics:
Utilizes methods like Word Embedding Similarity, BERTScore, or Universal Sentence Encoder (USE) to measure semantic similarity between generated and reference summaries.

### Coverage:
Evaluates how well the generated summary covers the key information present in the source document.

### Diversity Metrics:
Assess the diversity of the generated summaries to avoid redundancy.

### Readability:
Considers the readability and coherence of the generated summary.

### Responsiveness:
Measures how well the generated summary responds to the input or query.

### Length Ratio:
Examines the ratio of the length of the generated summary to the length of the reference summary.

### Fluency:
Evaluates the naturalness and fluency of the generated summary.

### Abstractive Quality:
Assesses how well the model is able to generate abstractive summaries.

### Reproducibility:
Considers how consistent and reproducible the model's performance is across different runs or datasets.

## The pretrined are from hugging face:
### 1.google/pegasus-large
### 2.allenai/led-large-16384-arxiv
### 3.sshleifer/distilbart-cnn-12-6
### 4.facebook/bart-large-cnn
### 5.t5-large

Graph plotted for each model and its topsis score <img width="877" alt="Topsis_Graph" src="https://github.com/ArshiyaSethi13/Topsis-Text-Summarization/blob/main/graph.png">


