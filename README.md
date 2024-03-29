# Quantitative-finance-papers-using-deep-learning
## This page is now updated in "<a href="https://deepallocation.com/Sub_html_frontier/index_Frontier.html">AI frontier in investment portfolio</a>".
## Background
<!Deep learning have become increasingly used in the field of finance.> 
I would like to introduce some papers bridging deep learning and traditional financial theories (especially in the field of investments), hoping that the tecniques employed in them will be used as components in developing new investment and risk management systems.
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
  + _Focus_: It finds the existence of nonlinear factors which explain predictability of returns, in particular at the extremes of the characteristic
space.

### Multi-indicators
- **Discovering Bayesian Market Views for Intelligent Asset Allocation** (2018),  F. Z. Xing et al. [[pdf]](https://arxiv.org/pdf/1802.09911.pdf)
  + _Focus_:  It proposes to formalize public mood into market views, because market views can be integrated into the modern portfolio theory. In the framework, the optimal market views will maximize returns in each period with a Bayesian asset allocation model. They use the data of capitalization, prices, volume, and sentiment and train two neural models to generate the market views, and benchmark the model performance on other popular asset allocation strategies.

- **Visual Attention Model for Cross-sectional Stock Return Prediction and End-to-End Multimodal Market Representation Learning** (2018),  R. Zhao et al. [[pdf]](https://arxiv.org/abs/1809.03684)
  + _Focus_: Using the data of price-volume, historical return, technical indicators, and fundamental indicators, it applies a convolutional neural network over this market image to build market features in a hierarchical way. We use a recurrent neural network, with an attention mechanism over the market feature maps, to model temporal dynamics in the market.



## 2. Deep neural networks
### 2-1. Multi-layer perceptron 

### 2-2. Recurrent neural networks (simple-RNN, LSTM, GRU)
- **Deep learning with long short-term memory networks for financial market predictions** (2018), T. Fischer and C. Krauss. 
(https://www.sciencedirect.com/science/article/abs/pii/S0377221717310652)
### 2-3. Convolutional neural networks
- **Algorithmic financial trading with deep convolutional neuralnetworks: Time series to image conversion approach** (2018), O. B. Sezer and A. M. Ozbayoglu.
(https://www.sciencedirect.com/science/article/pii/S1568494618302151)
  - _Focus_: It proposes a novel algorithmic trading model CNN-TA using a 2-D convolutional neural network based on image processing properties. In order to convert financial time series into 2-D images, 15 different technical indicators each with different parameter selections are utilized.
### 2-4. Autoencoder

## 3. Optimization
- **A note on the validity of cross-validation for evaluating autoregressive time series prediction** (2018), Bergmeir et al. <https://www.sciencedirect.com/science/article/pii/S0167947317302384> 

## 4. Financial use cases
### 4-1. Prediction: up/down, trend
### 4-2. Deep trading
### 4-3. Deep portfolio/deep factor
- **Applying Deep Learning to Enhance Momentum Trading Strategies in Stocks** (2013), L. Takeuchi and Y.-Y. Lee. [[pdf]](http://cs229.stanford.edu/proj2013/TakeuchiLee-ApplyingDeepLearningToEnhanceMomentumTradingStrategiesInStocks.pdf)
  + _Focus_: It uses an autoencoder composed of stacked
restricted Boltzmann machines to extract features from the history of individual stock prices. Its model is able to discover an enhanced version of the momentum effect in stocks without extensive hand-engineering of input features.
- **Deep learning with long short-term memory networks for financial market predictions** (2018), T. Fischer and C. Krauss. 
(https://www.sciencedirect.com/science/article/abs/pii/S0377221717310652)
- **Deep Learning in Asset Pricing** (2019), L. Chen et al. [[pdf]](https://economics.yale.edu/sites/default/files/deep_learning_in_asset_pricing.pdf)
- **Deep Factor Model** (2018), K. Nakagawa et al. [[pdf]](https://arxiv.org/pdf/1810.01278.pdf)
  + _Focus_: It proposes to represent a return model and risk model in a unified manner with deep learning, which is a representative model that can express a nonlinear relationship.
- **Deep Learning in Characteristics-Sorted Factor Models** (2019), G. Feng et al. [[pdf]](https://arxiv.org/pdf/1805.01104.pdf)
- **Deep Recurrent Factor Model: Interpretable Non-Linear and Time-Varying Multi-Factor Model** (2019), K. Nakagawa et al. [[pdf]](https://arxiv.org/ftp/arxiv/papers/1901/1901.11493.pdf)
- **Deep Learning Approximation for Stochastic Control Problems** (2016), J. Han and Weinan E. [[pdf]](https://arxiv.org/pdf/1611.07422.pdf)
  + _Focus_: It develops a deep learning approach that directly
solves high-dimensional stochastic control problems based on Monte-Carlo sampling and test this approach using examples from the areas of optimal trading. 
- **Machine learning and the cross-section of expected stock returns** (2018), M. Messmer [[pdf]](http://www1.unisg.ch/www/edis.nsf/SysLkpByIdentifier/4816/$FILE/dis4816.pdf)
  + _Focus_: Modeling expected cross-sectional stock returns has a long tradition in asset pricing. It is motivated by shortcomings of classical portfolio sorting approaches and tackles the task with alternative methodologies including classical linear models and more advanced machine learning algorithms.
- **Empirical Asset Pricing via Machine Learning** (2019), S. Gu et al. [[pdf]](http://dachxiu.chicagobooth.edu/download/ML.pdf)
  + _Focus_: It performs a comparative analysis of machine learning methods for the canonical problem
of empirical asset pricing: measuring asset risk premia. Improved risk premium
measurement through machine learning simplifies the investigation into economic mechanisms of
asset pricing and highlights the value of machine learning in financial innovation.
- **Machine Learning and Asset Pricing Models (PhD Thesis)** (2018), R. A. Porsani. [[pdf]](https://escholarship.org/uc/item/124940r0)
  + _Focus_: It incorporates statistical-learning techniques into the field of cross-sectional asset pricing.

- **Deep Fundamental Factor Models** (2019), M. F. Dixon and N. G. Polson [[pdf]](https://arxiv.org/pdf/1903.07677.pdf)
  + _Focus_: It develops deep fundamental factor models to interpret and capture non-linearity, interaction effects and non-parametric shocks in financial econometrics, by constructing a six-factor model of assets in the S&P 500 index and generating information ratios that are three times greater than generalized linear regression.
  
- **Deep Learning for Forecasting Stock Returns in the Cross-Section** (2018), Masaya Abe and Hideki Nakayama
 [[pdf]](https://arxiv.org/ftp/arxiv/papers/1801/1801.01777.pdf)
  + _Focus_: It implements deep learning to predict one-month-ahead stock returns in the cross-section in the Japanese stock market and investigates the performance of the method. 
  
- **Improving Factor-Based Quantitative Investing by Forecasting Company Fundamentals** (2018), J. Alberg and Z. C. Lipton [[pdf]](https://arxiv.org/pdf/1711.04837.pdf)
  + _Focus_: They first show through simulation that if they could (clairvoyantly)
select stocks using factors calculated on future fundamentals (via oracle), then
their portfolios would far outperform a standard factor approach.

### 4-4. Deep Reinforcement
- **Deep Reinforcement Learning in Financial Markets** (2019), S. Chakraborty [[pdf]](https://arxiv.org/abs/1907.04373)
  + _Focus_: It explores the usage of deep reinforcement learning algorithms to automatically generate consistently profitable, robust, uncorrelated trading signals in any general financial market and develops a novel Markov decision process (MDP) model to capture the financial trading markets. 

## 5. Explaining machine learning
- **A Unified Approach to Interpreting Model Predictions** (2017), S. M. Lundberg and S.-I. Lee [[pdf]](https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions.pdf)
  + _Focus_: It presents a unified framework for interpreting predictions, SHAP (SHapley Additive exPlanations). SHAP assigns each feature an importance value for a particular prediction.


## 6. Industrial application
- **J.P. Morgan** Artificial Intelligence <https://www.jpmorgan.com/global/technology/artificial-intelligence>
- **J.P. Morgan** J.P.Morgan's massive guide to machine learning and big data jobs in finance. <https://news.efinancialcareers.com/dk-en/285249/machine-learning-and-big-data-j-p-morgan>
- **J.B. Heaton** Quantitative investing and the limits of (deep) learning from financial data. [[pdf]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3133110)  



## 7. Survey
- **Natural language based financial forecasting: a survey** (2018), F. Z. Xing et al. [[pdf]](https://link.springer.com/article/10.1007/s10462-017-9588-9)
  + _Focus_: It clarifies the scope of natural language based financial forecasting (NLFF) research by ordering and structuring techniques and applications from related work.
- **Surveying stock market forecasting techniques – Part II: Soft computing methods** (2009), G. S. Atsalakis et al. [[pdf]](https://www.sciencedirect.com/science/article/pii/S0957417408004417)
  + _Focus_: It surveys more than 100 related published articles that focus on neural and neuro-fuzzy techniques derived and applied to forecast stock markets.
- **Computational Intelligence and Financial Markets: A Survey and Future Directions** (2016), R. C. Cavalcante et al. [[pdf]](https://www.sciencedirect.com/science/article/pii/S095741741630029X)
  + _Focus_: It gives an overview of the most important primary studies published from 2009 to 2015, which cover techniques for preprocessing and clustering of financial data, for forecasting future market movements, for mining financial text information, among others.
