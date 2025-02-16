**Overview:**<br>
SPELLSHIELD is a Natural Language Processing (NLP)-based system designed to detect and correct typographical errors in Tamil text. It utilizes cosine similarity and minimum edit distance to improve accuracy in typo correction, enhancing Tamil text processing for digital applications.

**Approach & Technologies Used:**<br>
Text Processing Techniques:<br>
🔹Tokenization & Lemmatization using spaCy for text segmentation.<br>
🔹Word Embeddings generated from pre-trained BERT (bert-base-multilingual-cased) for semantic understanding.

**Error Detection & Correction:**<br>
**Cosine Similarity**<br>
  🔹Measures vector similarity between words using BERT embeddings.<br>
  🔹Helps find the most semantically similar correction.<br>
**Minimum Edit Distance (Levenshtein Distance)**<br>
  🔹Computes the number of insertions, deletions, and substitutions needed to correct a word.<br>
  🔹More effective for detecting simple typographical errors.

**Implementation:**<br>
  🔹More effective for detecting simple typographical errors.<br>
  🔹Libraries Used: PyTorch, Transformers (Hugging Face), Pandas, NumPy, spaCy.<br>
  🔹Datasets: Tamil word corpus from the Tamil Spellings Dataset.

**Future Enhancements:**<br>
  🔹Fine-tuning BERT for Tamil for improved contextual understanding.<br>
  🔹Hybrid approach combining cosine similarity and edit distance for better typo correction.<br>
  🔹Exploring transformer models like RoBERTa or T5 for better performance.<br>
  🔹Model pruning & quantization for real-time applications.
