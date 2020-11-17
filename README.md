# Natural Language Processing
![](rsm-tmt-nlp.jpg)
The use of natural language processing has exploded over the last decade. Appilcations that require machines to understand natural human speech patterns are abundant and substantial improvements in these systems has increased their utility. Within the educational space NLP is used to interpret human speech for the prupose of understanding human problems and recently an online tutor passed a limited version of the [Turing Test](https://en.wikipedia.org/wiki/Turing_test) when it was [indistinguishable from teaching assistants in a college class](http://www.news.gatech.edu/2017/01/09/jill-watson-round-three).

## Goals for this unit

* Understand and apply the basic process of natural language proceessing and the role of pre-processing text
* Understand and apply a sentiment analysis to a set of documents
* Understand and apply a latent dirichlet allocation (LDA) to a set of documents

# Pacakge used in Python
`pandas`: data cleaning and wrangling <br>
`matplotlib`: plotting <br>
`re` : Regular Expression <br>
`os` : Handle list of documents <br>
`nltk.corpus`: import corpus: stopwords <br>
`wordcloud.WordCloud` : wordcloud <br>
`textblob.TextBlob` : Sentiment analysis <br>
`sklearn.feature_extraction.text.CountVectorizer` :Tokenization<br>
`sklearn.decomposition.LatentDirichletAllocation` :LDA 


## Tasks for this unit

In this project we have completed three main tasks. Processing a set of documents, running a sentiment analysis of thise documents and then generating topic models of those documents. The documents we were using are student notes that the class HUDK4050 made 2019 fall semester. As background to this task please read over the follwing materials and watch the methodological videos. 

## Result
![](p1.png =200x)
![](p2.png)
![](p3.png)
![](p4.png)

## Readings

* [Nadkarni, P. M., Ohno-Machado, L., & Chapman, W. W. (2011). Natural language processing: An Introduction. Journal of the American Medical Informatics Association: JAMIA, 18(5), 544–551.](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3168328/)

* [Robinson, A. C. (2015). Exploring Class Discussions from a Massive Open Online Course (MOOC) on Cartography. In J. Brus, A. Vondrakova, & V. Vozenilek (Eds.), Modern Trends in Cartography (pp. 173–182). Springer International Publishing.](http://link.springer.com.ezproxy.cul.columbia.edu/chapter/10.1007/978-3-319-07926-4_14)

* [McNamara, D. S., Crossley, S. A., & Roscoe, R. (2013). Natural Language Processing in an Intelligent Writing Strategy Tutoring System. Behavior Research Methods, 45(2), 499–515.](http://link.springer.com.ezproxy.cul.columbia.edu/article/10.3758/s13428-012-0258-1)

## Videos

[Crash Course. (2017). Natural Language Processing.](https://www.youtube.com/watch?v=fOvTtapxa9c)

[Raval, S. (2016). Sentiment Analysis in 4 Minutes.](https://www.youtube.com/watch?v=AJVP96tAWxw)

[Knispelis, A. (2016). LDA Topic Models.](https://www.youtube.com/watch?v=3mHy4OSyRf0)

## Reference Github
[nlp-in-python-tutorial](https://github.com/zz2641/nlp-in-python-tutorial/settings)


## Additional Materials

[Quora. (2017). What is a good explanation of Latent Dirichlet Allocation?](https://www.quora.com/What-is-a-good-explanation-of-Latent-Dirichlet-Allocation)
