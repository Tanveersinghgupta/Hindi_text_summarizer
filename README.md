# Hindi_text_summarizer
The project aims to develop a Hindi text summarization system using both extractive and abstractive techniques. 

This project aims to meet the growing need for text summarization systems tailored for Hindi text. It leverages a blend of extractive and abstractive techniques, including TF-IDF, Text Rank, T5, and BART, to produce succinct summaries. To evaluate the efficacy and coherency of the generated summaries, the project employs metrics like ROUGE-1, ROUGE-2, and ROUGE-L.

Text summarization is an essential natural language processing (NLP) task that condenses lengthy documents into shorter versions while preserving key information. This project focuses on catering to the specific requirements of Hindi text summarization. By employing a combination of extractive and abstractive approaches, including TF-IDF, Text Rank, T5, and BART, the system generates concise summaries.

# TF-IDF
TF-IDF (Term Frequency-Inverse Document Frequency): It is a numerical representation of a word's importance in a document within a collection or corpus. TF-IDF assigns a weight to each word based on its frequency in the document (term frequency) and rarity in the corpus (inverse document frequency). Words with higher TF-IDF scores are considered more important.

# Text Rank
Text Rank: Text Rank is a graph-based ranking algorithm used for extractive summarization. It constructs a graph representation of the text, where sentences are nodes and edges indicate the similarity between sentences. By applying iterative algorithms (similar to PageRank), Text Rank identifies the most important sentences in the graph, which form the summary.

# T5
T5 (Text-to-Text Transfer Transformer): T5 is a versatile transformer-based language model developed by Google. It can be fine-tuned for various natural language processing tasks, including text summarization. T5 uses a "text-to-text" transfer learning approach, where both the input and output are represented as text strings, enabling it to handle summarization by conditioning the model to generate summaries given an input text.

# BART
BART (Bidirectional and Auto-Regressive Transformer): BART is another transformer-based model that can be used for both abstractive and extractive summarization. It leverages a combination of bidirectional and auto-regressive training techniques. BART is pre-trained using denoising auto-encoding and can be fine-tuned for specific summarization tasks. It has achieved state-of-the-art performance on various summarization benchmarks.

# Features
Extractive and abstractive summarization techniques for Hindi text
Evaluation using ROUGE-1, ROUGE-2, and ROUGE-L metrics

# Evaluation
The quality and coherence of the generated summaries are evaluated using the following metrics:

ROUGE-1: Measures the overlap of unigram (single word) sequences between the generated summary and the reference summary.
ROUGE-2: Measures the overlap of bigram (two-word) sequences between the generated summary and the reference summary.
ROUGE-L: Computes the longest common subsequence of words between the generated summary and the reference summary.
