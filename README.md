---
title: "Pytorch Documentation"
author: '* **TEAM MEMBERS:** **Deepak Hazarika** , **Arghya** , **Ritambhra Korpal** , **Parinita Bora**, **Anish V**, **Shyam T**, **Nikhil Shrimali**, **Vishak Bharadwaj** *'
date: "8/19/2021"
output: html_document
---

## Project task:

### Part 1:

* download the PyTorch Documentation and then figure out a mechanism on how to convert the documentation into simple QnA rapidly, smartly, and logically.

* code parsing and storing slightly differently such that we can later generate code as well (think the use of indentation tags to get Python indentation). 

* How to store the data.

### Part 2:

* start dividing the collection of issues URL for all the PyTorch-related projects mentioned on this link https://github.com/bharathgs/Awesome-pytorch-list. 

### Status

Part 2 is done - Arghya provided the list of URLs

Part 1 - 

### Methodology :

477 files were distributed across 8 members , Naveen M was not available

3 types of QA along with the context were generated

* QA based on python code

* QA based on contents in tabular format

* QA based on text content in the web page

#### Implementation 

* Beautifulsoup package was used extensively to scrape the web page and extract text information

* nlp model from hugging face was used to generated the QA from the context




### Final output

| Member    | QA generated |
|-----------|--------------|
| Deepak    | 3417         |
| Nikhil    | 2627         |
| Anish     | 5419         |
| Vishak    | 1582         |
| Parinita  | 2950         |
| Shyam     | 2215         |
| Ritambhra | 1931         |
| Arghya    | 5146         |


Total question generated : 25,287 

### Conclusion:

Clean up is required to improve the quality of QA 



