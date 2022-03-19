# Machine Learning in Social Sciences at the OII

Welcome to the seminar talks on application of Machine Learning in Social Sciences taking place at the Oxford Internet Institute, University of Oxford. If you would like to present or have a suggestion please contact Dr Adam Mahdi (adam.mahdi@oii.ox.ac.uk). Currently the seminars are taking place in the hybrid format on Thursdays at 14.00. 


## Current talks

__Date__: 17 March 2022\
__Speaker__:  	[Ana-Maria Cretu](https://scholar.google.com/citations?hl=en&user=1iDGOKUAAAAJ&view_op=list_works&sortby=pubdate) (Imperial College London)\
__Title__:   [Interaction data are identifiable even across long periods of time](https://www.nature.com/articles/s41467-021-27714-6)

__Abstract__: Fine-grained records of people’s interactions, both offline and online, are collected at large scale. These data contain sensitive information about whom we meet, talk to, and when. We demonstrate here how people’s interaction behavior is stable over long periods of time and can be used to identify individuals in anonymous datasets. Our attack learns the profile of an individual using geometric deep learning and triplet loss optimization. In a mobile phone metadata dataset of more than 40k people, it correctly identifies 52% of individuals based on their 2-hop interaction graph. We further show that the profiles learned by our method are stable over time and that 24% of people are still identifiable after 20 weeks. Our results suggest that people with well-balanced interaction graphs are more identifiable. Applying our attack to Bluetooth close-proximity networks, we show that even 1-hop interaction graphs are enough to identify people more than 26% of the time. Our results provide strong evidence that disconnected and even re-pseudonymized interaction data can be linked together making them personal data under the European Union’s General Data Protection Regulation.

--- 
## Past talks (2022-)

__Date__: 3 March 2022\
__Speaker__:  	[Mohamed Ibrahim](https://scholar.google.com.eg/citations?user=6-6sTUUAAAAJ&hl=en) (Alan Turing Institute)\
__Title__:   Image signatures for image recognition models

__Abstract__: This paper introduces a new lightweight method for image
recognition. ImageSig is based on computing signatures
and does not require a convolutional structure or an
attention-based encoder. It is striking to the authors that it
achieves: a) an accuracy for 64 X 64 RGB images that exceeds
many of the state-of-the-art methods and simultaneously
b) requires orders of magnitude less FLOPS, power
and memory footprint. The pretrained model can be as
small as 44.2 KB in size. ImageSig shows unprecedented
performance on hardware such as Raspberry Pi and Jetson nano.
ImageSig treats images as streams with multiple
channels. These streams are parameterized by spatial directions.
We contribute to the functionality of signature and
rough path theory to stream-like data and vision tasks on
static images beyond temporal streams. With very few parameters
and small size models, the key advantage is that
one could have many of these ”detectors” assembled on the
same chip; moreover, the feature acquisition can be performed
once and shared between different models of different
tasks - further accelerating the process. This contributes
to energy efficiency and the advancements of embedded AI
at the edge.

-

__Date__: 19 January 2022\
__Speaker__:  	[Pawel Dlotko](https://dioscuri-tda.org/members/pawel.html) (Dioscuri Centre in Topological Data Analysis)\
__Title__:   Invitation to TDA

__Abstract__: What is the shape of a collection of points or a sublevel set of a high dimensional function? Is there a way to explore it, understand it and apply it in a learning context? Topological Data Analysis, in particular mapper-type algorithms and persistent homology propose an answer to this question. In this talk we will briefly introduce those concepts and computational tools that can be used to compute them. We will also briefly mention some of their applications.

-

__Date__: 26 January 2022\
__Speaker__:  	[Davide Gurnari](https://dioscuri-tda.org/members/davide.html) (Dioscuri Centre in Topological Data Analysis)\
__Title__:   Distributed algorithms for Euler Characteristic Curves (and Profiles)

__Abstract__: Persistent homology is a technique from topological data analysis that has been shown to be powerful in a variety of applications. However new ideas and algorithms are needed in order to efficiently tackle big data problems.
In this talk I will present how topological features can be extracted using one of the most famous invariants, the Euler characteristic. The Euler characteristic of a simplicial complex is the alternate sum of its Betti number, or equivalently the alternating sum of the number of its simplices of following dimensions. For a filtered complex the Euler Characteristic Curve is a function that assigns an Euler number to each filtration level.
By following a distributed approach, the contributions to the ECC can be computed locally without having to explicitly build up the whole complex. This allows us to significatively reduce both time and memory requirements, giving us the opportunity to tackle much larger datasets compared to persistent homology. Such algorithms can be naturally extended to work in the multiparameter persistence setting, giving rise to the notion of Euler Characteristic Profiles.

-

__Date__: 26 January 2022\
__Speaker__:  	[Ambrose Yim](https://www.maths.ox.ac.uk/people/ambrose.yim) (Mathematical Institute, University of Oxford)\
__Title__:    How to Bin and Slice Data - a Topological Perspective

__Abstract__: In many real life applications, the analysis of large, high dimensional distributions of data is often simplified by dividing them into bins along a continuous parameter. For example, covid patient data is often divided by age bands to study how age impacts covid outcomes. However, a poor choice of bins can give a misleading illustration of the data. We discuss how topological ideas, in particular those from Morse theory and topological data analysis, can guide how data on a manifold can be discretised into bins.


-

__Date__: 12 January 2022\
__Speaker__:  	[Dani Kiyasseh](https://danikiyasseh.github.io/) (Caltech)\
__Title__:    Active Learning - Motivation, Core-elements and SoQal

__Abstract__: Supervised learning has been the driving force behind many of today’s machine learning algorithms. The success of this approach, however, typically necessitates the presence of abundant labelled data, a resource which can be non-trivial to collect. In contrast, an increasing number of settings is characterized by both scarce labelled data and abundant unlabelled data. One way to leverage such data is via active learning, a paradigm that attempts to minimize the burden of providing annotations while designing generalizable algorithms. In this talk, I will first outline the motivation for active learning and discuss its four core elements (train, acquire, label, and augment). I will then introduce a recently-proposed framework known as SoQal which, in contrast to previous work, addresses two of active learning’s elements simultaneously (acquire and label). I will conclude the talk by reflecting on the utility of active learning and providing some guiding principles.

-

__Date__: 12 January 2022\
__Speaker__:  	[Hannah Kirk](https://www.hannahrosekirk.com/) (Oxford Internet Institute, University of Oxford)\
__Title__:    Using Transformers-Based Active Learning for Efficient and Effective Detection of Harmful Language

__Abstract__: Automated abusive language detection has predominately been approached using passive, fully supervised learning over a large, annotated dataset to maximize accuracy or F1-score. This approach focuses on user welfare, but ignores annotator welfare where viewing harmful content can be psychologically damaging. In this talk, I will present some of my recent research on active learning with abusive language detection, where we ask the question: is more data always better?  To answer this question, we use a series of simulated experiments over two datasets at varying percentages of abuse. We demonstrate that transformers-based active learning is a promising alternative approach, which maintains high efficacy but substantially raises efficiency by requiring a fraction of examples to reach equivalent performance. More data is not always better and sometimes it is worse. These findings demonstrates that a re-think is needed as to whether we require so many annotated examples of abusive language and thus whether the current paradigm puts annotators at undue harm.


-

__Date__: 5 January 2022\
__Speaker__:  	[Lingyi Yang](https://www.maths.ox.ac.uk/people/lingyi.yang) (Mathematical Institute, University of Oxford)\
__Title__:    Online Neural Controlled Differential Equations

__Abstract__: In recent years, differential equation-inspired neural networks have become increasingly popular. Neural controlled differential equations (Neural CDEs) can be thought of as a continuous-time extension of recurrent neural networks (RNNs). This requires the construction of a continuous control path from discrete observations. For online prediction tasks, the underlying control path should be causal, something that was not considered when Neural CDEs were first conceived. In this talk, we discuss how to ensure this condition, along with other properties that the ideal control path should satisfy. Finally we show that this modification achieves state-of-the-art performance on prediction problems from the MIMIC-IV dataset.
