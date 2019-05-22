# NLP in Chinese
<br>
This repo contains the Natural Language Processing (NLP) in Chinese project as part of my data science portfolio. The objective of this project is to work with text in Chinese language, which involve segmenting, cleaning, and visualizing the most frequent words of a famous Chinese novel in a wordcloud image. 

1. [Problem Statement](#ps)
2. [Dataset](#data)
3. [Natural Language Processing](#nlp)
4. [Discussion and Conclusion](#conclusion)


# <a name="ps">Problem Statement</a>

### What is NLP?
Natural language processing (NLP) is a subfield of computer science, information engineering, and artificial intelligence concerned with the interactions between computers and human languages, in particular how to program computers to process and analyze large amounts of natural language data. The ultimate objective of NLP is to read, decipher, understand, and make sense of the human languages in a manner that is valuable. 

In this project, we will look at how to perform NLP for text written in Chinese language. We will make use of a Chinese text segmentation library called "Jieba". Jieba is arguably the most elegant and the most popular Chinese word segmentation tool in python. "结巴" 中文分词: 做最好的Python中文分词组件.

To install, you can use PIP:
```python
pip install jieba
```


# <a name="data">Dataset</a>

The dataset (text) used in this project is the "Journey to the West" novel. "Journey to the West" or <<西游记>> is a Chinese novel published in the 16th century during the Ming dynasty and attributed to Wu Cheng'en. It is one of the Four Great Classical Novels of Chinese literature. Arthur Waley's popular abridged translation, Monkey, is well known in English-speaking countries. [(Source)](https://en.wikipedia.org/wiki/Journey_to_the_West)



# <a name="conclusion">Discussion and Conclusion</a>
In this project, we have performed NLP on the "Journey to the West" i.e. <<西游记>> novel. In particular, we have segmented the Chinese words, cleaned the word segments by removing stopwords (words which occur frequently but do not contain important significance and are therefore deemed irrelevant), counted the top 100 most frequently appeared word segments, and finally visualized the frequently appearing words in a wordcloud image. 

<br><br>
If you have any feedback for this project, feel free to contact me via my [LinkedIn](https://www.linkedin.com/in/limchiahooi) or [GitHub Pages](https://limchiahooi.github.io).


---

![wordcloud](wordcloud.png)
