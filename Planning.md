# anime_ML project planning

## Meeting notes

08/12/2022:
- Karthik presented the userbase_model for anime recommendation
  - On first glance, it seems to be biased towards recommending popular animes, rather than similar-type animes. This might partially be due to small dataset used and partially due to the nature of the model. 
- Michael confirmed that the closeness metric we have is the one most commonly used in these kinds of problems. 
- We still don't have a good performance evaluation metric for this type of problem. However, the original idea of predicting the score for a given anime is something that we can evaluate the performance of our model based on. 

To Dos:
- Write a model based on what we have learnt so far, to predict the score of a given anime.
  - Take the anime_with_synopsis, split it into 80-20 train test split, and using whatever parameters you want to choose predict the score.

07/28/2022:

- Questions to think about for the group:
  - How do we evaluate the closeness of two animes?
  - How do we evaluate the performance of the model?
    - Use the user base database to make a separate model and see how they compare?

To Dos:
- Intro 2 GNNs (Yash)
- How to evaluate closeness? (Michael)
- How to evaluate performance of our model? (Pritom)
- Write a model based on user reviews (Karthik)
- Use NLP to extract information from synopsis 

07/22/2022:

- We should at least have a baseline model before we dive into more complex ML rabbit holes. We decided to train a K-Nearest neighbors model on the kaggle dataset and use it as a baseline to compare against. We plan to have it ready by the next meeting, as we already have several implementations of this on Kaggle that we can refer to. Here's my favorite [one](https://www.kaggle.com/code/benroshan/content-collaborative-anime-recommendation)

- Yash gave a brief introduction to Graph Neural Networks along with a collection of resources that we can refer to, once we are ready to implement a GNN for our recommender system. These resources will be made available on github.

- Karthik gave a brief introduction to Natural Language Processing (NLP) with an example of a Spam vs non-Spam sms classifier. See 04_natural_language_processing.ipynb for more details.

<hl>

We will use this as a central document that will broadly define our project and the directions we take. Our goal can be pretty flexible depending on what people find interesting. Nominally we can start off with something simple and broad and refine it as we go. Accordingly, we will have to modify the model selection, metrics etc as required. Please feel free to edit this document as you see fit.

## Potential subprojects/takeaways (Add more subprojects here and self-assign tasks)

- Data exploration and identiying potential issues with the data
  - Writing notebooks with helper functions to enable data manipulation and visuaization (Michael, Karthik)
- Recommendation model selection
  - Reading up about various models and assessing their suitability
  - Coding them in notebooks and eventually we might want to build modules
- Natural language processing
  - How to use information from show description, reviews etc
- UI design
  - Some experiments with tkinter, QtDesigner etc
- Practice with GitHub, VS Code etc
