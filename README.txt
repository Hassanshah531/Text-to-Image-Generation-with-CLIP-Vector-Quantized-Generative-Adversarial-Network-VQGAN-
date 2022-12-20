Automatic synthesis of realistic images is extremely difficult task and even the state-of-the-art AI/ML algorithm 
suffer to fulfil this expectation. In this story I will talk about how to generate realistic images from textual 
description which describes the image. 

How text embeddings are learnt: There are several unsupervised way of learning text embeddings. A very successful
way of learning text embeddings is Skip-Thought Vectors. This kind of pre-trained vectors can be leveraged for 
multiple purposes to solve downstream applications. Another popular way to learn text embeddings is called 
Triplet Loss. For Triplet Loss formulation, 2 captions of same image is selected, one of them is considered as 
anchor whereas the other one is considered as positive. A random caption from different category is considered 
as negative.