# Text Generation using Markov Chains
This project implements a probabilistic text generation model using Markov Chains.  
The system learns word transition patterns from a training corpus and generates new text sequences by predicting the next word based on previously observed transitions.

The implementation demonstrates the use of statistical language models such as **Bigram** and **Trigram models** to simulate natural language generation.

---

## Objective

To develop a text generation system that models word-level dependencies using Markov Chains and generates new sentences based on learned transition probabilities.

---

## Methodology

1. **Data Preprocessing**
   - Convert text to lowercase
   - Tokenize the corpus into word sequences

2. **Bigram Model**
   - Constructs a transition dictionary where  
     `current_word → possible next words`

3. **Trigram Model**
   - Uses two previous words as context  
     `(word₁, word₂) → next word`

4. **Text Generation**
   - Start with an initial word or word pair
   - Iteratively sample the next word using probabilistic transitions

5. **Graph Visualization**
   - Word transitions are represented using a directed graph to illustrate the Markov Chain structure.

---

## Technologies Used

- Python
- Google Colab
- Natural Language Processing
- Markov Chains
- NetworkX
- Matplotlib

---

## Repository Structure

PRODIGY_GA_03  
│  
├── PRODIGY_GA_03.ipynb  
└── README.md  

---

## Example Output

Generated text sample:

Artificial intelligence is transforming the world machine learning is widely used in computer vision and natural language processing.

The output varies for each execution due to the stochastic nature of the Markov process.

---

## Learning Outcomes

- Understanding probabilistic language models
- Implementation of Bigram and Trigram Markov Chains
- Practical exposure to statistical approaches in NLP
- Visualization of word transition graphs

---

## Internship Information

Organization: Prodigy InfoTech  
Internship: Generative AI Internship  
Task: Task-03 – Text Generation using Markov Chains  
