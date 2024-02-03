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
![text input](https://github.com/MannatPruthi/TOPSIS-on-Text-Summarization/assets/91721574/c2c6a8d1-479c-4f4e-8da5-2b9f00ce0b64)



The below is the input which will be given to TOPSIS.
![input](https://github.com/MannatPruthi/TOPSIS-on-Text-Summarization/assets/91721574/e355e8d4-6de7-4227-b129-eabaf8bbadab)


## **4. Output**
![output](https://github.com/MannatPruthi/TOPSIS-on-Text-Summarization/assets/91721574/10a026d4-4103-4640-8d3a-5e1a4f76d01b)

## **5. Bar Graph**
The bar chart visually represents the performance metrics of each model, providing an easy-to-understand comparison.
![graph](https://github.com/MannatPruthi/TOPSIS-on-Text-Summarization/assets/91721574/a31f1329-3939-49c3-a571-65f1dd8fe07b)


## **6. Conclusion**
Hence we can conclude that Model-3 named "t5-base-fr-sum-cnndm" performed best in our case.
<br>
<a href="https://huggingface.co/plguillou/t5-base-fr-sum-cnndm">View Model on Hugging Face</a>
