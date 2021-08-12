# pytorchdocumentation
---
title: "Pytorch Documentation"
author: '* **TEAM MEMBERS:** **Naveen M**, **Deepak Hazarika** , **Arghya** , **Ritambhra Korpal** , **Parinita Bora**, **Anish V**, **Megha**, **Shyam T**, **Nikhil Shrimali**, **Vishak Bharadwaj** *'
date: "8/12/2021"
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

### Done - 755 QA generated on How to use a method?
      
  * code parsing and storing slightly differently
  
    * QA generated for all code examples from 355 web pages a sample is given below.
    
    * the entire code content is stored in a single line with the special characters
    
    * The question is more like *how to use the method*.
    
### Ongoing

  * parse 477 web pages 
  
    * python library - Beautifulsoup 

  * generate question and answer
  
    * open source code to generate the question and answer ,
      the quality of the questions requires manual verification.
    
### Schema of QandA - Json format


{
        "Answer": ">>> # Example of a function that takes in a torch.device\n>>> cuda1 = torch.device('cuda:1')\n>>> torch.randn((2,3), device=cuda1)\n",
        "Question": "How  the torch.device argument in functions can generally be substituted with a string.\nThis allows for fast prototyping of code., give an example?",
        "Id": 160,
        "source": "https://pytorch.org/docs/stable/tensor_attributes.html#type-promotion-doc",
        "context": " Thetorch.deviceargument in functions can generally be substituted with a string.\nThis allows for fast prototyping of code."
},




