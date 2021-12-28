# Product Recommendation [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1B6seELwQjQj3hjO02oX-1X5FMwk4SVWo)
[![Product Recommendation](https://img.shields.io/badge/-Python-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/03%20-%20Product%20Recommendation)
[![Product Recommendation](https://img.shields.io/badge/-Google%20Colab-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/03%20-%20Product%20Recommendation)
[![Product Recommendation](https://img.shields.io/badge/-Apriori-blue)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/tree/main/03%20-%20Product%20Recommendation)

## 1. Import Dataset
The dataset is a survey asking the students in the class whether they have ever purchased each item. It contains total 41 items and 47 responses.

## 2. Association Rules
Run market basket analysis. Selected only one-item pair and Filtered by lift > 1.7, confidence > 0.5, support > 0.1.  

The recommend interesting item pairs are as follows:
1. ทรายแมว คู่กับ น้ำพุแมว
2. Logitech Mx Master 3 Mouse คู่กับ เครื่องชงกาแฟแคปซูล
3. gaming chair คู่กับ Mechanical keyboard
4. ลู่วิ่งออกกำลังกาย คู่กับ airpods
5. ที่นอน memory form คู่กับ พลาสเตอร์บรรเทาปวด ตราเสือ

[![Association rules](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/03%20-%20Product%20Recommendation/Association%20rules.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/03%20-%20Product%20Recommendation/Association%20rules.png)

## 3. Collaborative Filtering Item-based
Calculate cosine similarity values for each item pair to find item Similarity. Filter the similarity value by threshold 0.8.

[![Cosine](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/03%20-%20Product%20Recommendation/Cosine.png)](https://github.com/pongsakorn-sur/BADS7105-CRM-Analytics/blob/main/03%20-%20Product%20Recommendation/Cosine.png)
