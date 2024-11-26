I was working on a housing regression task with multi-modal data predicting house prices This includes tabular data on the house's attributes(size, bedrooms...etc), textual data (txt files describing house's condition), and images of the house. I encoded images as a feature using a vision language model(CLIP) on a set of textual categories (ex. "Small house, Modern house, Newly constructed house"), classified the textual data with tranformer, and combined all data and fed into CatBoost.
Resources: 
https://medium.com/@kerry.halupka/getting-started-with-openais-clip-a3b8f5277867
https://towardsdatascience.com/catboost-regression-in-6-minutes-3487f3e5b329
