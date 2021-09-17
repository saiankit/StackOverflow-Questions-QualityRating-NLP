### StackOverflow-Questions-QualityRating-NLP

#### Motivation and Aim
The best place to find solutions to issues people face during the software development process is undoubtedly Stack Overflow. As of March 2021, there are over 14 million registered users, and Stack Overflow has received around 21 million questions and 31 million answers. There are multiple questions out there already listed for a given same issue, which causes high ambiguity in developers. Developers waste a lot of time running through various posts until they find the right one with a descriptive question, using which they can relate to the issue they are facing. We can assess the quality of questions and give an innate rating based on the parameters we evaluate the question on. On a combined feature of the number of answers and innate rating is given to the question, the question can be given more reach than other questions in the same topic. This will decrease the hassle user has to face during his quest for a perfect answer. This, in turn, increases the quality of the software community by increasing the developer's productivity because he found the solution in no time, and now he can concentrate on more essential aspects of the development.

Dataset : https://www.kaggle.com/imoore/60k-stack-overflow-questions-with-quality-rate

| Model Used                            |                          Loss |
|---------------------------------------|------------------------------:|
| TFIDF + Logistic Regression           | LogLoss = 0.683 Loss = 0.3045 |
| TFIDF + Naive Bayes           | LogLoss = 0.734 |