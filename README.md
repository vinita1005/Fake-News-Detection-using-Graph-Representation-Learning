## Fake-News-Detection-using-Graph-Representation-Learning

Author 1:
Vinita Chappar
vchappar@buffalo.edu

Author 2:
Charanteja Kalva
charante@buffalu.edu

# Abstract
With the rapid expansion of Social media platforms, people
also depend on these platforms for news and daily activities
happening around the world. As there are no regulations
or restrictions on these platforms people have enough
freedom to post irrespective of the authenticity of the post.
This may result in the wrong influence on the people regarding
the news in the post. This gives us the need to find such
fake news and eradicate them before it reaches a vast number
of audience. So we decided to counter these fake news
by some deep learning methods. As we can observe that
social media platforms represent graphical networks, we
explored some Graph Neural Networks to detect the Fake-
News based on the content and the users responsible for its
spread. We have used Graph Convolutional Networks and
Graph Attention Networks to classify Fake NEWS and got
good results, which show that while detecting fake news the
Graph network structure play an important role.

# Introduction

The World is accelerating with progressive developments
in technology of all forms. Because of the easy
availability of internet and high-speed bandwidth, usage of
mobile phones and other related equipment has seen a sudden
spike. Subsequently the social media platforms saw
the opportunity to keep people engaged to their platform by
providing various appealing features. People are now reliable
on social platforms for their daily dose of NEWS. Social
media platforms provide enough freedom to the users
without restricting the type of content the users post. Here
comes the problem of FAKE NEWS. The problem with the
NEWS articles on social platforms is that the users post the
article without any authenticity, which draw in many fake
and misleading news. These NEWS traverse through the
network because of re-sharing and re-posting by other users
who are not even aware of the context of the situation.
In this project we propose a model to identify the
fake news using the graph representation of how the news
articles are connected and its diffusion process through the
social media.
Fake NEWS detection is an emerging topic that has received
a lot of attention since last five years. Researchers
are continuously trying to make progress in this field of
study. Some well-structured datasets are available and different
approaches were developed to handle the problem.
We adopted the Graph Convolutional Network(GCN) to
classify news articles into fake and real classes. News articles
are posted by a user and are re-posted and re-shared by
other users and the chain continues forming a graph structure
between users and news articles. The Fake article takes
birth at a node and diffuses through the network. We assume
that GCN has the capability to capture this diffusion
process helping to improve the performance.

# Architectures implemented:
1. Graph Convolution networks
2. Graph Attention networks

# Dataset:
BuzzFeedNews

# Data preprocessing Methods used:
Bert Tokenization

# References

[1] Representation learning on networks.
snap.stanford.edu/proj/embeddings-WWW, 2018. 2

[2] William L. Hamilton, Rex Ying, and Jure Leskovec. Inductive
representation learning on large graphs. CoRR,
abs/1706.02216, 2017. 2

[3] Vineet Kumar. Loading bert with tensorflow hub, 2019. 4

[4] Yi-Ju Lu and Cheng-Te Li. Gcan: Graph-aware co-attention
networks for explainable fake news detection on social media,
2020. 1, 2

[5] Inneke Mayachita. Training graph convolutional networks
on node classification task, 2020. 4

[6] MOHD SANAD ZAKI RIZVI. Demystifying bert: A
comprehensive guide to the groundbreaking nlp framework,
2019. 4

[7] Kai Shu, Deepak Mahudeswaran, Suhang Wang, Dongwon
Lee, and Huan Liu. Fakenewsnet: A data repository
with news content, social context and dynamic information
for studying fake news on social media. arXiv preprint
arXiv:1809.01286, 2018. 3

[8] Kai Shu, Amy Sliva, Suhang Wang, Jiliang Tang, and Huan
Liu. Fake news detection on social media: A data mining
perspective. CoRR, abs/1708.01967, 2017. 1

[9] Kai Shu, Amy Sliva, Suhang Wang, Jiliang Tang, and Huan
Liu. Fake news detection on social media: A data mining
perspective. ACM SIGKDD Explorations Newsletter,
19(1):22–36, 2017. 3

[10] Kai Shu, Suhang Wang, and Huan Liu. Exploiting
tri-relationship for fake news detection. arXiv preprint
arXiv:1712.07709, 2017. 3

[11] Petar Veliˇckovi´c, Guillem Cucurull, Arantxa Casanova,
Adriana Romero, Pietro Li`o, and Yoshua Bengio. Graph attention
networks, 2018. 2
