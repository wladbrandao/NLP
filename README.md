[Vers&atilde;o em Portugu&ecirc;s](br/README.md)

# Natural Language Processing
This is a set of lectures and material on natural language processing providing an introduction to the main methods and algorithms used to address practical problems involving natural language. See also the current courses related to this topic:

* [Introduction to Natural Language Processing](NLP202001.md): course offered in the 1st semester of 2020 to the students of the [Graduate Program in Informatics](http://portal.pucminas.br/pos/informatica) at [PUC Minas](http://www.pucminas.br).

## Introduction
Natural language processing (NLP) is one of the most important technologies since people communicate most everything in language, from emails, instant messages, web search, posts in social networks to customer service and medical reports.
Particularly, NLP refers to the set of methods for making human language accessible to machines \[[2](#Eisenstein-2018-BOOK)\]. It designates the design and analysis of representations, methods and algorithms to solve practical language problems by taking as input or produce as output unstructured natural human language data \[[3](#Goldberg-2017-SLHLT)\]. Usually, problems in NLP involve automatic speech recognition and text summarization, information extraction, machine translation, natural language understanding and generation, sentiment and discouse analysis.

The history of NLP dates back to the 1950s with experiments on automatic machine translation \[[6](#MIT-1952-CMT)\]. In the following years experiments on chatbots, conceptual ontologies and question answering were developed and the proposed approaches were mostly based on complex sets of hand-written rules.
In the late 80's, the introduction of machine learning algorithms for language processing produced a new paradigm distinct from rule-based NLP, with research mostly focusing on the development of statistical models to make probabilistic decisions based on features extracted from text corpus \[[5](#Johnson-2009-EACL)\].

Recent advances in artificial intelligence and high performance computing have led to an intensive use of new machine learning models powering NLP applications.
In particular, deep neural network based approaches have obtained very high performance across many different
NLP tasks \[[4](#Goldberg-2016-JAIR)\]. These models can often be trained with a single end-to-end model and do not require traditional, task specific feature engineering.
Such neural NLP have been they have been more effective for understanding complex language utterances and have been viewed as a new paradigm distinct from statistical NLP.

## Lectures

1. Introduction to NLP [ [sl01](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/notes/slides/ch01-intro.pdf) | [sl02](http://www3.cs.stonybrook.edu/~cse634/L16NLP.pdf) | [sl03](http://courses.cs.washington.edu/courses/cse490u/17wi/slides/intro-slides.pdf)]
1. Basic text processing [ [sl04](http://spark-public.s3.amazonaws.com/nlp/slides/textprocessingboth.pdf) ]
1. Text representation [ [sl05](http://web.stanford.edu/~jurafsky/slp3/slides/vector1.pdf) | [sl06](http://web.stanford.edu/~jurafsky/slp3/slides/vector2.pdf) ]
1. Text classification [ [sl07](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/notes/slides/ch02-linear-classification.pdf) | [sl08](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/notes/slides/ch03-nonlinear-classification.pdf) | [sl09](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/notes/slides/ch04-applications-of-classification.pdf) | [sl10](http://spark-public.s3.amazonaws.com/nlp/slides/naivebayes.pdf) ]
1. Language modeling [ [sl11](http://cs.columbia.edu/~mcollins/cs4705-spring2019/slides/lmslides.pdf) | [sl12](http://spark-public.s3.amazonaws.com/nlp/slides/languagemodeling.pdf) ]
1. POS Tagging [ [sl13](http://spark-public.s3.amazonaws.com/nlp/slides/Maxent_PosTagging.pdf) ]
1. Parsing and context-free grammars [ [sl14](http://spark-public.s3.amazonaws.com/nlp/slides/Parsing-Intro.pdf) | [sl15](http://spark-public.s3.amazonaws.com/nlp/slides/Parsing-Probabilistic.pdf) | [sl16](http://spark-public.s3.amazonaws.com/nlp/slides/Parsing-Lexicalization.pdf)]
1. Information extraction [ [sl17](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/2017-materials/slides/ie-slides.pdf) | [sl18](http://spark-public.s3.amazonaws.com/nlp/slides/Information_Extraction_and_Named_Entity_Recognition_v2.pdf) ]
1. Text summarization [ [sl19](http://spark-public.s3.amazonaws.com/nlp/slides/summarization.pdf) ]
1. Machine translation [ [sl20](https://github.com/jacobeisenstein/gt-nlp-class/raw/master/2017-materials/slides/mt-slides.pdf) ]
1. Question answering [ [sl21](http://spark-public.s3.amazonaws.com/nlp/slides/qa.pdf) ]
1. Language generation [ [sl22](https://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture15-nlg.pdf) ]
1. Text Semantics [ [sl23](http://spark-public.s3.amazonaws.com/nlp/slides/sem.pdf) ]
1. Introduction to neural networks [ [sl24](https://people.csail.mit.edu/dsontag/courses/ml16/slides/lecture24.pdf) | [sl25](http://web.stanford.edu/class/cs224n/slides/cs224n-2020-lecture04-neuralnets.pdf) | [sl26](http://www.cs.virginia.edu/~jjl5sw/documents/DeepLearningIntro.pdf) ]
1. Text embeddings [ slides ]
1. Neural language models [ slides ]


* And more... [NLP with Deep Learning](http://web.stanford.edu/class/cs224n/)

## Material

### Videos

1. [Channel: Natural Language Processing](https://www.youtube.com/playlist?list=PLoROMvodv4rOFZnDyrlW3-nI7tMLtmiJZ&disable_polymer=true) by Dan Jurafsky and Christopher Manning.
1. [Channel: From Languages to Information](https://www.youtube.com/channel/UC_48v322owNVtORXuMeRmpA) by Dan Jurafsky.
1. [Channel: Natural Language Processing with Deep Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) by Stanford University.

### Other Resources

1. [Natural Language Processing](http://web.stanford.edu/~jurafsky/NLPCourseraSlides.html) by Dan Jurafsky and Christopher Manning
1. [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) by Michael A. Nielsen.
1. [Deep Learning](http://www.deeplearningbook.org) by Ian Goodfellow, Yoshua Bengio and Aaron Courville.

## Further Information

Most of the topics of the lectures are taken from \[[1](#Jurafsky-2019-BOOK)\], \[[2](#Eisenstein-2018-BOOK)\] and \[[3](#Goldberg-2017-SLHLT)\]. Material and assignments are mostly inspired by the Stanford course [Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/).


## References

<a name="Jurafsky-2019-BOOK"></a>\[[1][1]\] Dan Jurafsky, and James H. Martin. Speech and Language Processing. 3rd ed. 2019.

<a name="Eisenstein-2018-BOOK"></a>\[[2][2]\] Jacob Eisenstein. Natural Language Processing. MIT Press. 2018.

<a name="Goldberg-2017-SLHLT"></a>\[[3][3]\] Yoav Goldberg. Neural network methods for natural language processing. Synthesis Lectures on Human Language Technologies, 10(1):1–309. 2017.

<a name="Goldberg-2016-JAIR"></a>\[[4][4]\] Yoav Goldberg. A Primer on Neural Network Models for Natural Language Processing. Journal of Artificial Intelligence Research, 57(1):345-420. 2016.

<a name="Johnson-2009-EACL"></a>\[[5][5]\] Mark Johnson. How the Statistical Revolution Changes (Computational) Linguistics. In Proceedings of the EACL Workshop on the Interaction between Linguistics and Computational Linguistics, p. 3-11, 2009.

<a name="MIT-1952-CMT"></a>\[[6][6]\] Conference on Mechanical Translation. MIT. 1952.

[1]: https://web.stanford.edu/~jurafsky/slp3/
[2]: https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf
[3]: https://doi.org/10.2200/S00762ED1V01Y201703HLT037
[4]: https://doi.org/10.1613/jair.4992
[5]: https://www.aclweb.org/anthology/W09-0103
[6]: http://mt-archive.info/MIT-1952-TOC.htm
