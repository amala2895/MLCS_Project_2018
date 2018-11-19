
# Stock Prediction and Firm Embeddings based on Legal Cases


Predicted change in stock price of firms based on their stock movements with respect to legal cases. 

The legal cases which were in form of text files of sentences passed were converted to dense vectors using gensim's doc2vec - The code is contained in CaseData folder

The stock data preparation code is in StockData folder

These dense vectors were used to generate prediction model using Random Forest algorithm and Neural Networks.

Further, formed embeddings of firms based on their reaction (stock movement) to legal cases using Neural Network
