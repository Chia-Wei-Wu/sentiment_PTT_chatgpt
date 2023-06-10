# Exploring People Sentiment towards ChatGPT on PTT
## Contributors
|組員|工作分配|
|-|-|
|吳家瑋|PTT Scrapy, Code(Data processing, cnsenti(fail)),GitHub,PPT|
|王玓澄|Code(Facebook-Scraper(Uudo)),PPT|
|郭達穎|Code(TF-IDF, WordCloud),PPT|
|李皓鈞|PTT Scrapy、Code(textblob(fail),snownlp),PPT|
## Motivation
* “ChatGPT” is a large-scale language model based on the GPT-3.5 architecture with potential for a wide range of applications, especially in social media.
* “PTT” attracts many users with its free and open discussion environment and diverse topics. It is a platform for people to exchange opinions, share knowledge and build communities.
* Hence, we analyze the direction of ChatGPT's public opinion on PTT to understand the usage of ChatGPT on social media.
## Related work
* Jieba: Jieba is a popular Chinese text segmentation library to split Chinese text into individual words or tokens used for NLP tasks like Information Retrieval, Machine Translation, Keyword Extraction, and so on.(https://pypi.org/project/jieba/)
* Term Frequency-Inverse Document Frequency(TF-IDF): It is a technique for assessing the importance of terms in a document collection, and it is commonly used in various tasks, including Information Retrieval, Document Similarity,  and Keyword Extraction.
* SnowNLP: SnowNLP is a Python library designed for natural language processing tasks about the Chinese language to do Sentiment analysis.(https://github.com/isnowfy/snownlp)
## DataSet
* Using PTT Scrapy to collect "tech_job" and "stock" board.
* Using jieba to token and delete Stopword by our defined dictionary.
* Classification by “date” with title having keyword “Chatgpt”.
* Classification by “date” with content having keyword “Chatgpt”. 
## Experiment
## TF-IDF result
## Sentiment Analysis
## Future prospects
* Optimize word segmentation method.
* Discuss other PTT boards.
* Discuss other social media platforms like FB, Twitter.
* Improve sentiment analysis techniques like using transform model.
* More models to do ensemble to get better result.
