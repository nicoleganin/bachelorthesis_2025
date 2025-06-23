## Table of Contents

### 1. Setup
- [1.1 Login to Hugging Face](BScThesis_NicoleGanin_Code.ipynb#11-login-to-hugging-face)
- [1.2 Import packages](BScThesis_NicoleGanin_Code.ipynb#12-import-packages)

### 2. Working with data
- [2.1 Descriptive statistics](BScThesis_NicoleGanin_Code.ipynb#21-descriptive-statistics)

### Preprocessing
- [2.1 Clean text from unwanted characters](BScThesis_NicoleGanin_Code.ipynb#21-clean-text-from-unwanted-characters)
- [2.1 Split text into chunks](BScThesis_NicoleGanin_Code.ipynb#21-split-text-into-chunks)
  - [2.1.1 Long chunk splitter](BScThesis_NicoleGanin_Code.ipynb#211-long-chunk-splitter-splits-by-sentence)
  - [2.1.2 Rule based chunking](BScThesis_NicoleGanin_Code.ipynb#212-rule-based-chunking-based-on-paragraphs)

### 3. Collecting data from LLMs
- [3.1 BART summarization](BScThesis_NicoleGanin_Code.ipynb#31-bart-summarization)
  - [3.1.1 BART summaries of reference text](BScThesis_NicoleGanin_Code.ipynb#311-bart-summaries-of-reference-text-merged-chunk-summaries)
  - [3.1.2 Print BART summary chunks in a data frame](BScThesis_NicoleGanin_Code.ipynb#312-print-bart-summary-chunks-in-a-data-frame)
  - [3.1.3 Save output to JSON](BScThesis_NicoleGanin_Code.ipynb#313-save-output-to-json)
- [3.2 Legal Pegasus](BScThesis_NicoleGanin_Code.ipynb#32-legal-pegasus---preprocessing-chunking--summariazing)
  - [3.2.1 LegalPegasus summaries of reference text](BScThesis_NicoleGanin_Code.ipynb#321-legalpegasus-summaries-of-reference-text-merged-chunk-summaries)
  - [3.2.3 Save output to JSON](BScThesis_NicoleGanin_Code.ipynb#323-safe-output-to-json)
- [3.3 T5 Summarizer](BScThesis_NicoleGanin_Code.ipynb#33-t5-summarizer)
  - [3.3.1 T5 summaries of reference text](BScThesis_NicoleGanin_Code.ipynb#331-t5-summaries-of-reference-text-merged-chunk-summaries)
  - [3.3.2 Save output to JSON](BScThesis_NicoleGanin_Code.ipynb#332-safe-outputs-to-json)
- [Load last saved JSON file to dataframe](BScThesis_NicoleGanin_Code.ipynb#load-last-saved-json-file-to-dataframe-again)

### 4. Evaluation & Selection
- [4.1 ROUGE](BScThesis_NicoleGanin_Code.ipynb#41-rouge)
  - [4.1.1 BART ROUGE](BScThesis_NicoleGanin_Code.ipynb#411-bart-rouge)
  - [4.1.2 LegalPegasus ROUGE](BScThesis_NicoleGanin_Code.ipynb#412-legalpegasus-rouge)
  - [4.1.3 T5 ROUGE](BScThesis_NicoleGanin_Code.ipynb#413-t5-rouge)
- [4.2 BERT Score](BScThesis_NicoleGanin_Code.ipynb#42-bert-score)
  - [4.2.2 LegalPegasus BERT](BScThesis_NicoleGanin_Code.ipynb#422-legalpegasus-bert)
  - [4.2.3 T5 BERT](BScThesis_NicoleGanin_Code.ipynb#423-t5-bert)
- [4.3 BLEU](BScThesis_NicoleGanin_Code.ipynb#43-bleu)
  - [4.3.1 BART BLEU](BScThesis_NicoleGanin_Code.ipynb#431-bart-bleu)
  - [4.3.2 LegalPegasus BLEU](BScThesis_NicoleGanin_Code.ipynb#432-legalpegasus-bleu)
  - [4.3.3 T5 BLEU](BScThesis_NicoleGanin_Code.ipynb#433-t5-bleu)
- [4.4 METEOR](BScThesis_NicoleGanin_Code.ipynb#44-meteor)
  - [4.4.1 BART METEOR](BScThesis_NicoleGanin_Code.ipynb#441-bart-meteor)
  - [4.4.2 LegalPegasus METEOR](BScThesis_NicoleGanin_Code.ipynb#442-legalpegasus-meteor)
  - [4.4.3 T5 METEOR](BScThesis_NicoleGanin_Code.ipynb#443-t5-meteor)

### 5. Text Mining & Similarity
- [5.1 Split by sentences](BScThesis_NicoleGanin_Code.ipynb#51-split-by-sentences)
- [5.2 Compare the chunks: TfIDF + Cosine Similarity](BScThesis_NicoleGanin_Code.ipynb#52-compare-the-chunks-tfidf-vectorizer--cosine-similarity)
- [5.3 Save JSON with extracted sentences and matched chunks](BScThesis_NicoleGanin_Code.ipynb#53-save-json-files-with-extracted-summary-sentences-and-most-similar-reference-chunks-based-on-cosine-similarity)
  - [5.3.1 Similarity ≥ 0.7](BScThesis_NicoleGanin_Code.ipynb#531-similarity--07)
  - [5.3.2 Delete noisy sentences](BScThesis_NicoleGanin_Code.ipynb#532-delete-sentences-with-too-much-noise-if-more-than-30-repetitive-words)

### 6. Export to LabelBox
- [6.1 LabelBox](BScThesis_NicoleGanin_Code.ipynb#61-labelbox)
- [6.2 Check versions of used libraries](BScThesis_NicoleGanin_Code.ipynb#62-check-versions-used-libraries)

### 7. Data Analysis
- [7.1 Import data](BScThesis_NicoleGanin_Code.ipynb#71-import-data)
  - [7.1.1 Import Pegasus annotations](BScThesis_NicoleGanin_Code.ipynb#711-import-pegasus-annotations)
  - [7.1.2 Import Human summaries annotations](BScThesis_NicoleGanin_Code.ipynb#712-import-human-summaries-annotations)
- [7.2 Visualize results](BScThesis_NicoleGanin_Code.ipynb#72-visualize-results)
- [7.3 Statistical analysis](BScThesis_NicoleGanin_Code.ipynb#73-statistical-analysis)

### Push to GitHub
- [Push to GitHub](BScThesis_NicoleGanin_Code.ipynb#push-to-github)
