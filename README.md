## Inspiration
The spread of fake news has become a significant problem in our digital age, leading to social and political upheaval and undermining trust in traditional media sources. A fake news detector has the potential to make a meaningful impact by identifying and flagging false information before it can spread widely, helping to prevent harm and reduce the influence of bad actors. By coding a fake news detector, we enable the opportunity to contribute to the fight against misinformation and support the vital role that accurate and trustworthy information plays in our society.

## What it does
The first part of the project was an EDA (Exploratory Data Analysis) to evaluate the sentiment and linguistics of a fake news article as compared to a true news article.
In the second part, a fake news detector algorithm uses machine learning techniques to analyze the content of articles and identify patterns of misinformation. Its purpose is to flag potentially false content and help reduce the spread of fake news.

## How we built it
To build the EDA component, we used machine learning libraries like Pandas, nltk, TextBlob and Top2Vec for sentiment and linguistic analysis.

For the fake news detector, we followed the following steps:
1. The datasets were cleaned and then labeled with encodings (1 for true and 0 for fake). The datasets were then combined and randomly shuffled.
2.  The DistilBERT model was then fine-tuned on the resulting combined dataset, achieving  an accuracy of 95%.
3. Finally, the trained model was deployed to a web application using Flask.

## Challenges we ran into
Some of the challenges we faces were:
1.  Lack of clear criteria for defining fake news
2. Difficulty in distinguishing between satire, real and fake news
3. Large amounts of diverse data made training take a long time

## Accomplishments that we're proud of
Thorough and successful analysis of the data: The team conducted a comprehensive and rigorous analysis of a large and diverse dataset, ensuring the accuracy and reliability of the fake news detector algorithm.

Accurate Detector - 95% accuracy: The fake news detector algorithm achieved an impressive accuracy rate of 95%, exceeding expectations and demonstrating the effectiveness of the machine learning techniques used.

Built an aesthetic UI: The team designed and built an aesthetically pleasing and user-friendly interface for the fake news detector, enhancing its usability and accessibility for a wide range of users.

## What we learned
Along with learning new techniques in NLP such as textblob and top2vec, we also improved our understanding on DistBERT. Other non-technical lessons were: understanding the relevance of high-quality training data, need for ongoing adaptation and refinement of algorithms and important of collaboration and interdisciplinary work.

## What's next for FakeWiz
Incorporating more advanced natural language processing (NLP) techniques: Most fake news detectors rely on simple keyword matching or other basic NLP techniques.

Addressing the issue of deepfakes: Deepfakes are a growing concern in the realm of fake news, as they can be used to create highly realistic videos or audio recordings that can be difficult to detect as fake. 

Leveraging user behavior data: The spread of fake news is often facilitated by social media platforms, and algorithms that can analyze user behavior data

Collaborating with fact-checking organizations: Fact-checking organizations such as Snopes and PolitiFact play an important role in identifying and debunking fake news.