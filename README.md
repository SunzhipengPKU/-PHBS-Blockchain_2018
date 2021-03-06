# PHBS_Blockchain_2018
# Financial Risk of Bitcoin From the Perspective of Price Fluctuation
## Intruduction
In recent years, the digital currency economy represented by Bitcoin has developed rapidly, attracting widespread attention from scholars, regulators and the public. In the ten years since 2008, it has initially formed a relatively complete industrial chain and trading market.

From the perspective of the whole world, on the one hand, digital currency itself has become a hot financial investment product, whose price fluctuates violently and frequently, experiencing many ups and downs. Meanwhile, financial accidents triggered by digital currency emerge in an endless stream. And different countries and institutions have different regulatory attitudes towards digital currency, which is also closely related to the its price fluctuations. On the other hand, the underlying blockchain technology of digital currency is changing many fields including finance. Bitcoin, as the first application of digital currency, is undoubtedly drawing concerns of many fields.

> As for China, the People's Bank of China and five other ministries and commissions jointly issued the ‘Notice on Preventing Risks of Bitcoin’ on December 5th, 2013, believing that Bitcoin does not have such monetary characters such as legal compensation and mandatory. So it is not a real currency, and financial institutions are not allowed to carry out relevant business. On September 4th, 2017, another ban named ‘Announcement on Preventing the Risks of Issuing and Financing Tokens’, announced that ICO (Initial Currency Offering) was illegal, and then stopped the registration and settlement business of trading platforms, as well as prohibiting major trading platforms from engaging in the exchange business of digital currencies and legal COINS. It can be seen that digital currencies represented by Bitcoin are prohibited from trading with legal COINS. Since 2016, China has also started to discuss the legality of digital currencies. Generally speaking, China holds a very cautious attitude towards digital currencies.

Digital currency is a new issue that has emerged in recent years. Not only the risk awareness of investors needs to be further strengthened, but also regulators have to solve financial and social problems brought by digital currency. In the context of global financial innovation, many countries are seeking for a reasonable balance between innovation and risk, and are optimizing and adjusting the whole system all the time. Therefore, this report will also try to give some suggestions for regulators based on digital currency risk.

## Literature Review
Most scholars regard Bitcoin as a financial asset to discuss the characteristics of the Bitcoin market. First, in terms of the market effectiveness of Bitcoin, many previous studies are still uncertain. Brown (2011) [1] believes that the Bitcoin market does not accord with the weak efficient market hypothesis. By testing the predictive ability of excess returns and market liquidity index, he finds the price of the Bitcoin is predictable in the short-term. However, Kurihara and Fukushima (2017) [2] believe that the Bitcoin market increasingly accords with the weak efficient market hypothesis. Through the study of Bitcoin price data over a long period of time, it is found that the Bitcoin market is becoming more and more effective and future earnings is also becoming more random. So it is inferred that the Bitcoin market is moving towards efficiency. From the perspective of price volatility, Buchholz (2012) [3] believes that the price volatility of Bitcoin has a positive impact on the price trend, which is the same as the characteristics of asset bubbles. Therefore, he holds that there is a bubble in Bitcoin now. Yermack (2013) [4] thinks that Bitcoin looks like a speculative asset in the Internet stock bubble in the late 1990s in terms of its performance. Ortisi (2016) [5] believes that the Bitcoin market is highly volatile and speculative. Zhu et al (2017) [6] find that the price of Bitcoin is directly related to the changes of some macroeconomic indicators and verify it with the VCEM model. Wu Jing (2015) [7], taking Bitcoin as an example, put forward a price formation model of digital currency under the current Internet finance condition. He believes that the Bitcoin price is correlated with overall GDP, the boom of Internet economy, the degree of network technology development and the degree of public enthusiasm for digital currency. These factors all contribute to the fluctuations of Bitcoin price. 

> As for financial regulation, since the development of digital currency, most countries have introduced suitable regulatory measures for their own markets according to international status and domestic conditions, and often adjust regulatory measures with market changes. Since 2016, some sovereign states have also proposed the concept of legal digital currency. 

>> 1.The UK is the first country to implement the concept of legal digital currency and introduce the prototype system. In March 2016, the UK proposed the RScoin central bank cryptocurrency, which is the world's first legal digital currency prototype system regulated by central bank. Since then many countries have embarked on digital currency research led by central Banks. 
 
>> 2.In 2016, Canada started to develop the digital version of Canadian dollar CADcoin, called the experiment of block chain technology project which is code-named Jasper and will be run in two experimental stages. 

>> 3.In June 2017, the monetary authority of Singapore (MAS) announced a project implemented by domestic banks, Deloitte and distributed ledger consortium (R3), which sought to launch Singapore's digital currency SGD on distributed ledger.

## Theoretical Analysis of Bitcoin Price Risk 

* Most risks of digital currencies are under supervision. One of them is the price fluctuation, which in reverse is also an intuitive indicator to measure risks. In fact, the price fluctuations are largely caused by major events, which not only include policy promulgation, but also unexpected bad contingencies that need to be solved in emergency.

* Generally speaking, when a positive event occurs the price of bitcoin will rise in the short-term, and vice versa when a negative event occurs. The Bitcoin price will rise due to increased demand. When positive events happen, investors will tend to be optimistic about the price trend and long Bitcoin to wait for the going-up, thus reducing the demand for Bitcoin transaction and increasing the total investment demand. However, due to fixed supply and limited supply, the price will rise directly. Besides, some investors who are not in this market before, encouraged by the good news, also eagerly enter the transaction, which in turn increase the market demand and push up the price of Bitcoin.

* When a negative event occurs, some investors will short Bitcoin, resulting in less investment demand and lower price. However, the falling price will push other investors to increase the purchase of Bitcoin, and the players who are keen on Bitcoin believe that bitcoin will have a good prospect for appreciation. So the price jump-down will attract investors to take the opportunity to enter the market, which will result in increased investment demand in the later stage. As a result, bad news tends to cause prices to fall in the early stages and rebound later as demand increases.

## Empirical Analysis
In this part, I will choose two major events—WannaCry ransomware attack, to make an event study.

> Starting on May 12, 2017, the WannaCry ransomware began sweeping the globe. The virus first broke out in Britain and eventually spread to most countries around the world. It attacked computers, locked files and encrypted them to demand Bitcoin for ransom. The ransomware virus caused the price of bitcoin to fall from $1,773 to $1,627, then fluctuated slightly before continuing its upward trend, rising 39.9 percent in 10 days.

This event had a huge influence on Bitcoin prices. First, although the ransomware virus caused social losses, it made more people know about Bitcoin and raised its popularity. Second, in this event, Bitcoin could be seen as a real application of digital currency. The ransomware virus itself caused negative effects, but it was a broader attempt for Bitcoin to be applied as a monetary tool. In general, this event was a positive event for bitcoin, fully reflecting the characteristics of digital currency.

![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/figure1.png)

> Due to the difference between Bitcoin and the stock market, there is no reliable price index formed yet. As it is only a single asset, without horizontal comparison with other assets, I decide to apply Cumulative Abnormal Return method to complete the event study. 

Suppose ARit is the abnormal return of asset i in period t. ARit should equal to the real return Rit in the event window minus expected return ERit

![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/%E5%85%AC%E5%BC%8F1-1.PNG)


First, I use estimation window data as sample and calculate the average return. This value can be seen as the expected return in the event window. Then I normalize the abnormal return in the last two windows

![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/%E5%85%AC%E5%BC%8F2-3.PNG)

> The data are all selected from [OKCoin](https://www.okcoin.cn/), one of the top three Bitcoin trading platforms in China. I choose the value of Bitcoin/USD and adopt closing price at 8:00 am Beijing time.

The estimation window covers from 100 days to 11 days before the event, a total of 90 days, which is taken as the event sample. The event window includes 21 days, ranging from 10 days before the event to 10 days after the event. The post-event window includes 20 days, which is 10 days after the event window.

Table 1  Observation window of WannaCry ransomware event
![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/table1-1.PNG)

Table 2 Abnormal return during the observation window
![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/table2-2.PNG)

* On the event day, the abnormal rate of return of Bitcoin showed a large depreciation, indicating that the event had a significant impact on the price.

* Four days before the event, Bitcoin price began to fluctuate slightly. It may come from early market operation of virus makers. 

* In the 10 days after the event, there were many large fluctuations, which could be regard as the result of the constant influence of the virus and it was the process of expansion and spread. Even if there were several spanking, the cumulative abnormal return of Bitcoin had mainly increased. It can be concluded that the event had a positive corresponding effect on the price of Bitcoin. 

* During the post-event window, the cumulative abnormal yield continued to increase and reached the peak on the 12th day, which then slightly shook but still showed an overall upward trend. It could be seen as the result of the continuous impact.

![Cattributes](https://github.com/SunzhipengPKU/figure-and-table/blob/master/figure2.png)

In the WannaCry ransomware event, the empirical test result is basically consistent with the objective situation. ]It is a bad event, but from the perspective of bitcoin trading market, it highlights the characteristics of bitcoin. WannaCry ransomware attack has caused bad social impact, but it has made more people know about bitcoin. Therefore, this event has a positive effect on the Bitcoin trading market in the early stage. 

## Suggestions
Mainstream academic researchers believe that digital currency regulation should balance risk prevention and financial innovation. For financial institutions operating digital currencies business, the regulatory authorities should set restrictive regulatory measures and follow up management. This includes registration, filing, reporting and examination of digital currency management. The content includes regulations on digital currency management, regulations on digital currency exchange, consumer protection measures, etc. 

* Japan, the United States and the European Union have already done this. Japanese government has a positive attitude towards digital currency, and its management methods have been constantly optimized and improved. Digital currencies are officially recognized in Japan, and the Financial Services Agency (FSA) has established regulations for Bitcoin exchanges. 

* In 2017, FSA announced on its website that 11 digital currency trading platforms have been registered, becoming officially legal. The regulatory authorities in the United States have expanded the original supervision scope of anti-money laundering and anti-terrorist financing to digital currency. In March 2013, the US Financial Crimes Enforcement Network (FinCEN) put convertible digital currencies under the supervision. They are asked to report the violation to the New York State Financial Services Authority.

China should utilize and encourage financial innovation as well as achieving the effectiveness of its supervision. 

* Financial innovation should be encouraged and inclusive management measures should be implemented in due course by gradually relaxing the control within a certain range. The government should have little involvement in the development of innovative businesses until this board grows up to a certain scale. And then the authority intervenes and gradually increases the management force. 

* Fintech should be used to lay out the digital currency infrastructure and promote its application. It is time to speed up the understanding of digital currency among regulators, utilize industry organization to strengthen the forward-looking research. 

* Financial institutions should actively embrace Fintech and consider cooperation, merger or acquisition of Fintech companies. From the perspective of digital currency, banking institutions may highlight their own characteristics and achieve a win-win situation with digital currency industry. 

China's strict regulatory control are still under discussion. Now it is necessary to define the connotation of digital currency, improve the legal system and establish a multi-dimensional supervision system. Regulators should make financial services more "inclusive" and "regulated at different levels", so as to achieve the effectiveness of financial regulation. We cannot totally reject advanced Fintech, nor can digital currencies lead to new systemic financial risk or even crisis. 

## References
1. Brown, & William, L. . (2014). An analysis of bitcoin market efficiency through measures of short-horizon return predictability and market liquidity.
2. Kurihara. Y. & A. Fukushima（2017）. The market efficiency of bitcoin: A weekly anomaly perspective. Journal of Applied Finance & Banking.
3. Buchholz, M., Delaney, J., Warren, J., Parker, J. (2012). Bits and Bets, Information, Price Volatility, and Demand for BitCoin. Economics.
4. Yermack, D. (2013). Is bitcoin a real currency? an economic appraisal. Handbook of Digital Currency, 31–43.
5. Ortisi, M. . (2016). Bitcoin market volatility analysis using grand canonical minority game. Social Science Electronic Publishing,1, 111-118.
6. Zhu, Y. , Dickinson, D. , & Li, J. . (2017). Erratum to: analysis on the influence factors of bitcoin’s price based on vec model. Financial Innovation, 3(1).
7. (2015). 互联网经济背景下虚拟货币价格形成机制研究——以比特币为例. (Doctoral dissertation, 中国海洋大学).
