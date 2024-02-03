# Applying TOPSIS to find the  best pre-trained model for Text Summarization

## 1. Overview
This project utilizes the TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) method for text summarization. It aims to provide a systematic approach for selecting the best text summarization model based on multiple criteria.

### **TOPSIS**




TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) is a decision-making method used to choose the best alternative from a set of options. It involves:

- **Normalization:** Scaling criteria to a common range for fair comparison.


- **Weighting:** Assigning weights to criteria based on their importance.


- **Positive and Negative Ideal Solutions:** Determining the best and worst possible values for each criterion.


- **Distance Calculation:** Measuring the distance of each alternative to both ideal solutions.


- **Ranking:** Assigning a preference ranking based on the calculated distances.

### **TEXT SUMMARIZATION**


Text summarization is the process of condensing a piece of text, preserving its key information, while reducing its length. There are two main types of text summarization:

- **Extractive Summarization:** Selects and extracts sentences or phrases directly from the original text to form a summary.
Uses algorithms to identify and rank sentences based on their importance.


- **Abstractive Summarization:** Generates a summary by paraphrasing and rephrasing the content in a new way.
Involves understanding the meaning of the text and generating novel sentences.


Text summarization is employed in various applications, such as:

- News Articles: Creating concise summaries of news articles for quick information retrieval.
- Legal Documents: Condensing lengthy legal documents to extract key points and arguments.
- Research Papers: Providing a brief overview of complex research findings.
- Search Engine Snippets: Generating concise summaries for search engine results.
- Content Aggregation: Summarizing and presenting content from multiple sources in a condensed form.


## **2. Methodology**
![Blank diagram](https://github.com/MannatPruthi/TOPSIS-on-Text-Summarization/assets/91721574/cccbd565-c618-403e-b32e-4caace1477b6)


## **3. Input**
The below is the text input on which we want to test five models.
<img src = "https://github.com/BhavyaBhalla-27/Assignment-3/assets/114859167/4d699da7-1a23-415b-a0f7-cb5437d167aa" width = "100%" height="100%" />
The below is the input which will be given to TOPSIS.
<img src="https://github.com/BhavyaBhalla-27/Assignment-3/assets/114859167/4cba7f9b-3d35-4904-a495-cdecee8e1df8" width="100%" height="100%">

## **4. Output**
<img src="https://github.com/BhavyaBhalla-27/Assignment-3/assets/114859167/3a04a1cb-a8a5-46a6-9f11-df1ffc38fb90" width="120%" height="120%">

## **5. Conclusion**
Hence we can conclude that Model-3 named "t5-base-fr-sum-cnndm" performed best in our case.
<br>
<a href="https://huggingface.co/plguillou/t5-base-fr-sum-cnndm">View Model on Hugging Face</a>
