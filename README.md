
# Recommendation System Resources 

## I am collecting all the resources regarding RecSys,
- Leave a star if you find this useful
- Pull request if you want to contribute to this resource


### Common Datasets

| Name           | Scene         | Tasks        | Information                                                                                                           | URL                                                   |
|----------------|---------------|--------------|-----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| Amazon Review  | Commerce      | Seq Rec/CF Rec | This is a large crawl of product reviews from Amazon. Ratings: 82.83 million, Users: 20.98 million, Items: 9.35 million, Timespan: May 1996 - July 2014 | [link](http://jmcauley.ucsd.edu/data/amazon/)        |
| Amazon-M2      | Commerce      | Seq Rec/CF Rec | A large dataset of anonymized user sessions with their interacted products collected from multiple language sources at Amazon. It includes 3,606,249 train sessions, 361,659 test sessions, and 1,410,675 products. | [link](https://arxiv.org/abs/2307.09688)  [link-2](https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge) |
| Steam          | Game          | Seq Rec/CF Rec | Reviews represent a great opportunity to break down the satisfaction and dissatisfaction factors around games. Reviews: 7,793,069, Users: 2,567,538, Items: 15,474, Bundles: 615 | [link](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data) |
| MovieLens      | Movie         | General       | The dataset consists of 4 sub-datasets, which describe users' ratings to movies and free-text tagging activities from MovieLens, a movie recommendation service. | [link](https://grouplens.org/datasets/movielens/)    |
| Yelp           | Commerce      | General       | There are 6,990,280 reviews, 150,346 businesses, 200,100 pictures, 11 metropolitan areas, 908,915 tips by 1,987,897 users. Over 1.2 million business attributes like hours, parking, availability, etc. | [link](https://www.yelp.com/dataset)                 |
| Douban         | Movie, Music, Book | Seq Rec/CF Rec | This dataset includes three domains, i.e., movie, music, and book, and different kinds of raw information, i.e., ratings, reviews, item details, user profiles, tags (labels), and date. | [link](https://paperswithcode.com/dataset/douban)    |
| MIND           | News          | General       | MIND contains about 160k English news articles and more than 15 million impression logs generated by 1 million users. Every news contains textual content including title, abstract, body, category, and entities. | [link](https://msnews.github.io/assets/doc/ACL2020_MIND.pdf) |
| U-NEED         | Commerce      | Conversation Rec | U-NEED consists of 7,698 fine-grained annotated pre-sales dialogues, 333,879 user behaviors, and 332,148 product knowledge tuples. | [link](https://github.com/LeeeeoLiu/U-NEED)          |
| PixelRec | Short Video | Seq Rec/CF Rec | PixelRec is a large dataset of cover images collected from a short video recommender system, comprising approximately 200 million user image interactions, 30 million users, and 400,000 video cover images. The texts and other aggregated attributes of videos are also included. | [link](https://github.com/westlake-repl/PixelRec) |
| KuaiSAR | Video | Search and Rec | KuaiSAR contains genuine search and recommendation behaviors of 25,877 users, 6,890,707 items, 453,667 queries, and 19,664,885 actions within a span of 19 days on the Kuaishou app | [link](https://kuaisar.github.io) |
| Tenrec | Video, Article | General | Tenrec is a large-scale benchmark dataset for recommendation systems. It contains around 5 million users and 140 million interactions. | [link](https://tenrec0.github.io/) |
 
This link contains all the datsets regarding RecSys - [link](https://cseweb.ucsd.edu/~jmcauley/datasets.html)



## Libraries

| Name           | Tasks         | Information                                                                                                           | URL                                                   |
|----------------|---------------|-----------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| DeepCarsKit    |Context Aware  |  A deep learning based context-aware recommendation library                                                           |[link](https://www.sciencedirect.com/science/article/pii/S2665963822000380)
|MM-Rec          | MultiModal RecSys | MMRec is a MultiModal Recommendation toolbox based on PyTorch. It integrates more than ten outstanding multimodal recommendation system models| [link](https://github.com/enoche/MMRec)
|[Cornac](https://github.com/PreferredAI/cornac)| MultiModal RecSys| Cornac is a comparative framework for multimodal recommender systems. It focuses on making it convenient to work with models leveraging auxiliary data (e.g., item descriptive text and image, social network, etc),<br>Cornac enables fast experiments and straightforward implementations of new models. It is highly compatible with existing machine learning libraries (e.g., TensorFlow, PyTorch).|[Paper](https://dl.acm.org/doi/abs/10.5555/3455716.3455811)

## Miscellaneous Links

| Name           |               Information                                                                                                            |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|
| [Young Feng](https://www.yongfeng.me/)    | Researcher - Notes/ Slides/ Projects on RecSys|
| [PhD Thesis](https://recsyswiki.com/wiki/List_of_recommender_system_dissertations)| A Compilation of  RecSys thessis|
| [Tensorflow Summit](https://rsvp.withgoogle.com/events/recommendation-system-dev-summit) | Tensorflow Summit on RecSys 2023 - Their Tools explanation for RecSys|
|[RecSys WorkShop](https://recsys.acm.org/workshops/)| All the workshops of the RecSys|

## Github Pages

| Name           |               Information                                                                                                            | Paper Link|
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|-----------|
| [Graham Jesnon](https://github.com/grahamjenson/list_of_recommender_systems)| A list of the SOTA RecSys being used in the Industry and also links for the Open Source RecSys| N.A|
| [Foundation Models for Recommender Systems: A Survey and New Perspectives](https://github.com/westlake-repl/Recommendation-Systems-without-Explicit-ID-Features-A-Literature-Review)| All the literature they have used, compiled over here | [link](https://arxiv.org/pdf/2402.11143.pdf) |
| [A Survey on Large Language Models for Recommendation](https://github.com/WLiK/LLM4Rec-Awesome-Papers)| All the literature they have used, compiled over here| [link](https://arxiv.org/pdf/2305.19860.pdf)|
|[MultiModal RecSys](https://github.com/enoche/MultimodalRecSys)| All the literature encompising the MultiModal RecSys| N.A|



https://wenqifan03.github.io/openings.html



### Single card (RTX 3090) debuggable generative language models that support Chinese corpus

Some open-source and effective projects can be adapted to the recommendation systems based on Chinese textual data. Especially for the individual researchers !

| Project                                                      | Year |
| ------------------------------------------------------------ | ---- |
| [Qwen1.5-7B](https://github.com/QwenLM/Qwen1.5) | 2023 |
| [baichuan-7B](https://huggingface.co/baichuan-inc/baichuan-7B) | 2023 |
| [YuLan-chat](https://github.com/RUC-GSAI/YuLan-Chat)         | 2023 |
| [Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca) | 2023 |
| [THUDM](https://github.com/THUDM)/**[ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)** | 2023 |
| [FreedomIntelligence](https://github.com/FreedomIntelligence)/**[LLMZoo](https://github.com/FreedomIntelligence/LLMZoo)** **Phoenix** | 2023 |
| [bloomz-7b1](https://huggingface.co/bigscience/bloomz-7b1)   | 2023 |
| [LianjiaTech](https://github.com/LianjiaTech)/**[BELLE](https://github.com/LianjiaTech/BELLE)** | 2023 |

Hope our conclusion can help your work.
