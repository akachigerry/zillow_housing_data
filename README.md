                        PREDICTIVE ANALYSIS OF THE ZILLOW HOUSE PRICE DATA

# Purpose:
#    To develop a model for effective prediction of house prices in diverse housing markets. 
#    House price prediction models are often trained with housing market-specific data and rely (in addition to other factors) on time-course or cyclical patterns for prediction. This approach often result in models with of predictive performance that deteriorate outside of the market data utilised for training. A reasonably simple / inflexible model was therefore chosen for this analysis. An iterative model training approach which trains the model using a market-specific subset of the training data, validates/tests on a different subset re-trains on a new training set updated using the previous validation set.

# Method
#    An ensembl model of regression methods consisting of lasso, simple linear and regression trees methods was used in an end-to-end process that spans from data retrieval and cleaning to model testing and deloyment.
