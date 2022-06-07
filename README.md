# CryptoLin

This is the official repository of Cryptocurrency Linguo (CryptoLin), a novel corpus containing cryptocurrency related 2683 news covering more than 3-years period. 
We web crawled English online cryptocurrency news articles on all cryptocurrencies from various sources over a period of 42 months (July 2018–January 2022) using the cryptocurrency news aggregator CoinMarketCal website (https://coinmarketcal.com/en/news) resulting in a data set with 2683 news.
CryptoLin was human annotated with discrete values representing negative, neutral and positive news respectively. Each news item was randomly assigned and blindly annotated by 3 humans followed by a consensus mechanism using simple voting. In case one of the annotators was in total disagreement with other two (1 negative vs 2 positive or 1 positive vs 2 negative), we considered this minority report and defaulted the labeling to neutral. 
The annotations also include a text span, providing the 3 manual labels providing additional insight into the decision’ reasoning. To further verify the quality of the labelling and the usefulness of CryptoLin, it also includes other data including the Fama French Three Factor Model \cite{fama_efficient_1970} and the outcomes of using several pre-trained Sentiment Analysis models, including FinBERT \cite{Zhuang2020}.  
Overall, CryptoLin aims to complement the current knowledge by providing a novel and publicly available cryptocurrency sentiment corpus and to foster research on the topic of cryptocurrency sentiment analysis and potential applications in behavioural science.
