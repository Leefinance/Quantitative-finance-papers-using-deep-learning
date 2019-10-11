# Quantitative-finance-papers-using-deep-learning

## Background
<!Deep learning have become increasingly used in the field of finance. One of the difficulties in developing financial models arises from the fact that there is not a standard data like MINST or CIFAR. Experiments have been usually carried out under different conditions such as periods, country, and private data, and consequently, the models are exposed to experimental bias. Due to the difficulty of directly comparing the performance of the developed models, we cannot simply adopt the model with higher performance.> 
I would like to introduce some papers on deep learning model-based forecasting and its applications, hoping that the tecniques employed in the studies will be used as components in developing new and improved perdictors, especially for investment and risk management.
## Contents
![alt text](/Contents.png)
***

## 1. Financial data
### Tecnical indicators
- **Forecasting price movements using technical indicators: Investigating the impact of varying input window length** (2017), Y. Shynkevich et al. [[pdf]](https://www.sciencedirect.com/science/article/pii/S0925231217311074)
### Macroecnomic indicators
- **An Algorithmic Crystal Ball: Forecasts-based on Machine Learning** (2018),  J.-K. Jung et al. [[pdf]](https://www.imf.org/en/Publications/WP/Issues/2018/11/01/An-Algorithmic-Crystal-Ball-Forecasts-based-on-Machine-Learning-46288)
### Fundamental indicators
- **Deep Learning for Predicting Asset Returns** (2018),  G. Feng et al. [[pdf]](https://arxiv.org/pdf/1804.09314.pdf)
  + Foucs: It finds the existence of nonlinear factors which explain predictability of returns, in particular at the extremes of the characteristic
space.
## 2. Deep neural networks
### 2-1. Multi-layer perceptron 

### 2-2. Recurrent neural networks (simple-RNN, LSTM, GRU)
- **Deep learning with long short-term memory networks for financial market predictions** (2018), T. Fischer and C. Krauss. 
(https://www.sciencedirect.com/science/article/abs/pii/S0377221717310652)
### 2-3. Convolutional neural networks
- **Algorithmic financial trading with deep convolutional neuralnetworks: Time series to image conversion approach** (2018), O. B. Sezer and A. M. Ozbayoglu.
(https://www.sciencedirect.com/science/article/pii/S1568494618302151)
  - Focus: It proposes a novel algorithmic trading model CNN-TA using a 2-D convolutional neural network based on image processing properties. In order to convert financial time series into 2-D images, 15 different technical indicators each with different parameter selections are utilized.
### 2-4. Autoencoder

## 3. Optimization
- **A note on the validity of cross-validation for evaluating autoregressive time series prediction** (2018), Bergmeir et al. <https://www.sciencedirect.com/science/article/pii/S0167947317302384> 

## 4. Financial use cases
### 4-1. Prediction: up/down, trend
### 4-2. Deep trading
### 4-3. Deep portfolio/deep factor
- **Applying Deep Learning to Enhance Momentum Trading Strategies in Stocks** (2013), L. Takeuchi and Y.-Y. Lee. [[pdf]](http://cs229.stanford.edu/proj2013/TakeuchiLee-ApplyingDeepLearningToEnhanceMomentumTradingStrategiesInStocks.pdf)
  + Focus: It uses an autoencoder composed of stacked
restricted Boltzmann machines to extract features from the history of individual stock prices. Its model is able to discover an enhanced version of the momentum effect in stocks without extensive hand-engineering of input features.
- **Deep learning with long short-term memory networks for financial market predictions** (2018), T. Fischer and C. Krauss. 
(https://www.sciencedirect.com/science/article/abs/pii/S0377221717310652)
- **Deep Learning in Asset Pricing** (2019), L. Chen et al. [[pdf]](https://economics.yale.edu/sites/default/files/deep_learning_in_asset_pricing.pdf)
- **Deep Factor Model** (2018), K. Nakagawa et al. [[pdf]](https://arxiv.org/pdf/1810.01278.pdf)
  + Focus: It proposes to represent a return model and risk model in a unified manner with deep learning, which is a representative model that can express a nonlinear relationship.
- **Deep Learning in Asset Pricing** (2019), G. Feng et al. [[pdf]](https://arxiv.org/pdf/1805.01104.pdf)
- **Deep Recurrent Factor Model: Interpretable Non-Linear and Time-Varying Multi-Factor Model** (2019), K. Nakagawa et al. [[pdf]](https://arxiv.org/ftp/arxiv/papers/1901/1901.11493.pdf)
- **Deep Learning Approximation for Stochastic Control Problems** (2016), J. Han and Weinan E. [[pdf]](https://arxiv.org/pdf/1611.07422.pdf)
  + Focus: It develops a deep learning approach that directly
solves high-dimensional stochastic control problems based on Monte-Carlo sampling and test this approach using examples from the areas of optimal trading. 
## 5. Explaining machine learning
- **A Unified Approach to Interpreting Model Predictions** (2017), S. M. Lundberg and S.-I. Lee [[pdf]](https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf)
  + Focus: It presents a unified framework for interpreting predictions, SHAP (SHapley Additive exPlanations). SHAP assigns each feature
an importance value for a particular prediction.
## 6. Industrial application
- J.P. Morgan (https://www.jpmorgan.com/global/technology/artificial-intelligence)

## 7. Survey
- **Natural language based financial forecasting: a survey** (2018), F. Z. Xing et al. [[pdf]](https://link.springer.com/article/10.1007/s10462-017-9588-9)
  + Focus: It clarifies the scope of natural language based financial forecasting (NLFF) research by ordering and structuring techniques and applications from related work.
- **Surveying stock market forecasting techniques – Part II: Soft computing methods** (2009), G. S. Atsalakis et al. [[pdf]](https://www.sciencedirect.com/science/article/pii/S0957417408004417)
  + Focus: It surveys more than 100 related published articles that focus on neural and neuro-fuzzy techniques derived and applied to forecast stock markets.
- **Computational Intelligence and Financial Markets: A Survey and Future Directions** (2016), R. C. Cavalcante et al. [[pdf]](https://www.sciencedirect.com/science/article/pii/S095741741630029X)
  + Focus: It gives an overview of the most important primary studies published from 2009 to 2015, which cover techniques for preprocessing and clustering of financial data, for forecasting future market movements, for mining financial text information, among others.
