# anime_ML project planning

## Meeting notes

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
