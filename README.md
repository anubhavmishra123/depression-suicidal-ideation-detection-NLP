# depression-suicidal-ideation-detection-NLP

Depression is a common mental disorder whose importance is often being overlooked. If not treated properly, it can lead to more serious problems, disability, psychotic episodes and unfortunately in some cases even to suicide. According to World Health Organization, more than 264 million people worldwide suffer from depression. As it is the case with the majority of mental illnesses, early detection of the problem can prove to be very useful in its prevention. With the development of technology, people are spending more and more time on the Internet, and their activity on various websites (e.g. social networks, blogs. . .) can tell a lot about them. Language is a powerful indicator of personality, social or emotional status, but also mental health. It will surprise no one to learn that those with symptoms of depression use an excessive amount of words conveying negative emotions, specifically negative adjectives and adverbs such as “lonely “or “sad”. More interesting is the use of pronouns like “me”, “myself” and “I” which are used much more by those with symptoms of depression which means they are generally more focused on themselves. Someone’s social media account content can often provide us with valuable information about that person’s emotional status. However, the current technology used to deal with depression issues is only reactive. For instance, some specific types of risks can be detected by tracking Internet users, but alerts are triggered when the victim makes his disorders explicit, or when the criminal or offending activities are actually happening. We believe there is a better way in detecting early detection by using natural language processing tools
which can be used to diagnose depression. The main idea of this project is to present one method of predicting whether a person is having depressive thoughts and intentions using natural language processing.


Following Steps are followed for data pre-processing.

•Tokenization

•Removing numeric and special symbols

•Removing Stop words,

                example: Are, The, To, For etc.
                
•Lemmatization 

                example: playing-> play
                
Text Vectorization using TF-IDF (Term frequency-inverse document frequency)


Dataset is collected from Kaggle which is having more than 10 thousand sentences and corresponding emotion depicted in sentence.

Columns in dataset are

1.Label

2.Sentence

Block Diagram

<img src="https://github.com/anubhavmishra123/depression-suicidal-ideation-detection-NLP/blob/main/blockdiagram.png" width="500" height="500">



