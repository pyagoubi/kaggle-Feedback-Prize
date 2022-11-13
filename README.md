# Feedback-Prize

Competition [Link](https://www.kaggle.com/competitions/feedback-prize-english-language-learning)

<b>Objective  </b>

The goal of this competition is to assess the language proficiency of 8th-12th grade English Language Learners (ELLs). Utilizing a dataset of essays written by ELLs will help to develop proficiency models that better supports all students.

<b>Links  </b>
* Comprehensive EDA: **[Link](https://github.com/pyagoubi/kaggle-Feedback-Prize/blob/main/Feedback_EDA.ipynb)**
* Experimentation with Language Tool **[Link](https://www.kaggle.com/code/pyagoubi/creating-new-features-with-language-tool)** 
* DeBERTa model: **[Link](https://github.com/pyagoubi/kaggle-Feedback-Prize/blob/main/dbb-4xmp3.ipynb)** 

Following points to note about the DeBERTa model
+ instead of CLS-pooling MeanPooling was applied as it has shown to work better on that dataset
+ the last three layers were meanpooled and then fed into a linear NN were weights were scaled by softmax
+ layerwise learning rate decay was applied

