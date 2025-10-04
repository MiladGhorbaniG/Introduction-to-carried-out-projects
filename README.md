# Introduction to carried out projects

Here you will find information about a number of completed projects and the software or hardware used.

## Detection and tracking of targets with Deep Learning

2017-18

This project was about detecting and tracking people in a room using computer vision. The camera was rotated using a servo motor and targets were detected using deep learning methods such as YOLO and Faster RCNN. The deep learning models were developed using the Python language via the Tensorflow and Keras libraries. The hardware for processing was a Raspberry Pie. We collected and labelled the data using LabelMe.

## Increasing the speed of reinforcement learning through ensemble learning

2018-19

In this project, some agents learn a task simultaneously using ensemble learning ideas and share their knowledge to increase the learning speed. Matlab, Python and Javascript are used for the simulations. A preprint on this work can be found in [paper](https://arxiv.org/abs/2012.07091).

## Semantic Real-Time Segmentation and Autonomous Driving

2018-19

In this project, the goal was to visually control a robot to avoid obstacles and reach the goal. For testing, we used the AirSim simulator and trained deep learning models that are proven in real-time testing, such as ENet, BiSeNet, and SegNet. The library used was Tensorflow. Using the output of the model, we estimated the position on the road and made the robot stay on the road using a fuzzy controller. We created a map of the area in AirSim and used the Bellman-Ford algorithm for path planning and used the Deep Learning results to stay on the road. We also used a depth map computed by combining the results of the block-based stereo matching methods and the MonoDepth method, which estimates depth using a single approach.

We tested 2 scenarios. In the first, the starting point and destination was from D to K in the graph below:

![image-20230115162451129](images/image-20230115162451129.png)

We have tested this scenario in AirSim and you can see an snapshot from this scenario. In the pictures you can see the image observed by the robot and the path followed by the robot and its control commands.

 ![image-20230115162743642](images/image-20230115162757686.png)

These scenarios were also tested on the Jetson TX2.

## Advanced Trading Strategy for Stock, Crypto and Forex Markets

2020-25

This innovative trading system delivers exceptional results across multiple financial markets, achieving over **70% accuracy** in market predictions. The system significantly outperforms traditional investment strategies, providing users with a superior trading experience that consistently beats both HODL (Hold On for Dear Life) and DCA (Dollar Cost Averaging) approaches.

### Key Performance Advantages:
- **Superior Returns**: Consistently generates higher profits compared to passive investment strategies
- **Market Versatility**: Successfully operates across stocks, cryptocurrencies, and forex markets
- **Risk Management**: Intelligent position sizing and timing reduce exposure to market volatility
- **User-Friendly Experience**: Streamlined interface that makes sophisticated trading accessible to all skill levels

The system analyzes critical market factors and processes vast amounts of real-time data to make informed trading decisions. Through advanced machine learning techniques, including various LSTM architectures (Bidirectional LSTM, Stacked LSTM, and LSTM with Attention mechanisms) and modern transformer-based models, it identifies profitable opportunities while minimizing risks, giving traders a significant edge in today's competitive markets.

### Advanced Model Architectures:
- **Bidirectional LSTM**: Captures both forward and backward temporal dependencies in market data
- **Stacked LSTM**: Multi-layer architecture for complex pattern recognition across different time horizons
- **LSTM with Attention**: Focuses on the most relevant market indicators and time periods
- **Transformer Models**: Leverage self-attention mechanisms for superior sequence modeling
- **Hybrid Architectures**: Combine LSTM and transformer approaches for optimal performance

**Performance Highlights:**
- Over 70% prediction accuracy across all tested markets
- Consistently outperforms traditional buy-and-hold strategies
- Superior risk-adjusted returns compared to dollar-cost averaging
- Real-time market analysis with actionable insights

### Quantitative Approaches and Methodologies

The trading system employs sophisticated quantitative approaches that combine multiple analytical frameworks to maximize trading performance:

#### Statistical Analysis and Signal Processing
- **Time Series Analysis**: Advanced ARIMA, GARCH, and VAR models for volatility forecasting
- **Technical Indicators**: Custom implementations of RSI, MACD, Bollinger Bands, and Ichimoku Cloud
- **Signal Processing**: Wavelet transforms and Fourier analysis for noise reduction and pattern extraction
- **Statistical Arbitrage**: Pairs trading and mean reversion strategies across correlated assets

#### Machine Learning and AI Techniques
- **Feature Engineering**: Automated creation of 200+ technical and fundamental indicators
- **Ensemble Methods**: Random Forest, XGBoost, and LightGBM for robust prediction models
- **Deep Learning**: Convolutional Neural Networks (CNNs) for pattern recognition in price charts
- **Reinforcement Learning**: Q-learning and Policy Gradient methods for adaptive strategy optimization
- **Natural Language Processing**: Sentiment analysis of news, social media, and financial reports

#### Risk Management and Portfolio Optimization
- **Modern Portfolio Theory**: Mean-variance optimization with constraints
- **Value at Risk (VaR)**: Monte Carlo simulations for risk assessment
- **Kelly Criterion**: Optimal position sizing based on win probability and payoff ratios
- **Dynamic Hedging**: Real-time portfolio rebalancing to maintain target risk levels
- **Stress Testing**: Scenario analysis under extreme market conditions

### Advanced Trading Strategies

The system implements multiple sophisticated trading strategies that adapt to different market conditions:

#### Momentum and Trend Following
- **Breakout Strategies**: Identification and trading of price breakouts with volume confirmation
- **Moving Average Crossovers**: Multi-timeframe MA systems with adaptive parameters
- **Momentum Oscillators**: Custom momentum indicators with market regime detection
- **Trend Strength Analysis**: ADX and directional movement indicators for trend validation

#### Mean Reversion and Contrarian
- **Statistical Mean Reversion**: Z-score based entry/exit signals for overbought/oversold conditions
- **Pairs Trading**: Long-short strategies on correlated assets with cointegration analysis
- **Volatility Mean Reversion**: Trading volatility spikes using VIX and implied volatility metrics
- **Support/Resistance Trading**: Automated identification and trading of key price levels

#### Market Microstructure and High-Frequency
- **Order Flow Analysis**: Real-time analysis of bid-ask spreads and order book dynamics
- **Liquidity Provision**: Market making strategies with dynamic spread adjustment
- **Arbitrage Opportunities**: Cross-exchange and cross-asset arbitrage detection
- **Latency Optimization**: Sub-millisecond execution for high-frequency strategies

#### Multi-Asset and Cross-Market
- **Cross-Asset Correlation**: Trading based on relationships between stocks, bonds, commodities, and currencies
- **Sector Rotation**: Dynamic allocation across market sectors based on economic cycles
- **Geographic Diversification**: International market analysis and currency hedging
- **Alternative Data Integration**: Satellite imagery, social sentiment, and economic indicators

#### Adaptive and Machine Learning Driven
- **Regime Detection**: Automatic identification of market regimes (bull, bear, sideways, volatile)
- **Strategy Selection**: Dynamic allocation across different strategies based on market conditions
- **Parameter Optimization**: Continuous optimization of strategy parameters using genetic algorithms
- **Performance Attribution**: Real-time analysis of strategy performance and risk-adjusted returns

## Video object detection for bird detection

2021-22

This project tests different approaches to object detection on a dataset created to detect birds. Some of the approaches tested were image-based, such as Faster RCNN, YOLO, Retinanet, and Swin Transformer, and some others were video-based, such as TransVOD, LSFA, DEFT, Centertrack, SELSA. A post-processing method, REPP, is also tested. Its performance is improved using camera movement compensation. The detection accuracy was 95.07 and with these video methods, the accuracy was improved by 3 percent. The models were tested on the Jetson Xavier board. To obtain a fast model, we also used knowledge distillation and obtained a model with a smaller number of parameters and still good accuracy by training with a large model.


## Road Detection

2022-23

This project tests different approaches to object detection on a dataset created to detect birds. Some of the approaches tested were image-based, such as Faster RCNN, YOLO, Retinanet, and Swin Transformer, and some others were video-based, such as TransVOD, LSFA, DEFT, Centertrack, SELSA. A post-processing method, REPP, is also tested. Its performance is improved using camera movement compensation. The detection accuracy was 95.07 and with these video methods, the accuracy was improved by 3 percent. The models were tested on the Jetson Xavier board. To obtain a fast model, we also used knowledge distillation and obtained a model with a smaller number of parameters and still good accuracy by training with a large model.
