# Big Data in Sports Game Predictions and How It is Used in Sports Gambling

[![Check Report](https://github.com/cybertraining-dsc/fa20-523-331/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-331/actions)

- [ ] see our sample template at <https://cybertraining-dsc.github.io/report/> for an elaborate example
- [ ] Please use references instead of adding urls to cite the work. (Vibhatha). Follow the template to fix these. 

Mansukh Kandhari,, [fa20-523-331](https://github.com/cybertraining-dsc/fa20-523-331/), [Edit](https://github.com/cybertraining-dsc/fa20-523-331/blob/master/project/project.md)

{{% pageinfo %}}

## Abstract

*completed further along in project

Contents

{{< table_of_contents >}}

{{% /pageinfo %}}

**Keywords:** sports, sportsbook, betting, gambling, data analysis, machine learning

## 1. Introduction 

Big Data in sports has been used for years by various stakeholders in this inidustry to do everything from predicting game outcomes to injury prevention. It is also becoming very prevelant in the area of sports gambling. Ever since the Supreme court decision in Murphy v. National Collegiate Athletic Association that overturned a ban on sports betting, the majorirty of states in the US have passed legislation to allow sports gambling[^1]. In 2019, the global sports betting market was valued at 85.047 US Dollars so this is an already very big industry that is expanding [^2]. There are various platforms that allow betting in this industry including tangible sports books, casinos, racetracks, and many online and mobile gambling apps. The interesting thing about big data in sports betting is that it is being used on both sides in this market. It is used by bookmakers to create game models and come up with different spreads and odds, but big data anlysis is also being used by gamblers to gain a competetive advantage and place more accurate bets. Various prediction models using Machine Learning have been created and one might wonder, if these models are even somewhat accurate, how people haven't taken millions from bookmakers? This report aims to analyize different prediction models made by people for various sports, and compare them to models used by Bookies to create the odds for each repsective sport. It aims to show what the most possible accuracy can be, and if there is a feasable way to get a consistent good return from betting. 


## 2. Plan

For this report, an examination of the different methods used by various bookmakers and data driven sports betters will occur. The plan is to compare the different stastistical models and examine which ones work the best and to see how good various sports betting models predict over/under and straight bet outcomes for a game, and also program game prediction models. Various data sets will be used from sites such as <https://www.sportsbookreview.com/betting-odds/> to get historical betting odds and <https://www.basketball-reference.com/> for NBA basketball data, <https://www.baseball-reference.com>/ for MLB baseball data, and <https://www.pro-football-reference.com/> for American Football data. These will be used to program an example predicion model for this report. Since a programming aspect is not required for undergraduates, it is not certian that this will be able to be done in the timeframe; however, it is likley that a simple model can be made by the author. Various game prediction models that have been created will also be analyized as part of this report, in order to see how they compare to models used by bookmakers for each sport. 







## 3. How bookmakes Determine odds

It is no secret that bookmakers use a lot of data and apply various statistical techniques to come up with betting odds. The statistical techniques used and the data that bookmakers look at vary from sport to sport, for example, the most popular method for modeling soccer uses the poisson distribution since it can be very accurate but also because it makes it easy to add time decay to the inputs [^3].Bookmakers employ various mathematicians to analyze historical sports data to come up with odds; however, sports data isn’t the only thing that bookmakers look at when determining how they will make odds for a game. At the end of the day, the gamlbing industry is a numbers game that thrives on ensuring the probability is in the houses favor. Bookmakers use various techniques involving big data in order to do so. 

Big data is being used more and more in various industries, and in the gambling industry, it isn't just used to come up with odds. One major way it is used is by gathering data about user demographics [^4]. When using an online sportsbook, the casino can gather data about a users age, location, gender, excetera which can provide valuable insights that can be used for product development and marketing purposes. By using user demographic data to provide targeted advertising, casinos and bookmakers can attract more betters which will increase revenue. As said by former odds compiler Matthew Trenhaile, "Their [bookmakers] product is entertainment and not the selling of an intellectual contest between punter and bookmaker. It is foolish to think this has ever been the product that bookmakers have sold.They sell an adrenaline rush and anyone who thinks great characters pitting themselves against the punters and taking anyone on in horse racing betting rings is what betting used to be about is kidding himself or herself." Due to the probability of making money in sports betting, and really every type of gambling, being in the houses favor, online casinos and sportsbooks use big data to increase the number of bets placed by customers. Nevertheless, using models to come up with odds is the heart of this industry which makes it the most important way big data analytics is used by bookmakers.
	
When odds are being made for a sports book, a lot of things are taken into consideration in the process. Bookmakers have teams of statisticians that analyze historical data of the teams in order to come up with game prediction models[^5]. When bookmakers are actually making the odds, these statistical models created from large amounts of data aren't the only thing they use. When bookmakers are creating odds, their goal is to have the lowest probability of paying out, so they will also use public opinion along with their statistical models to do this. For example, if a team has been on an unexpected winning streak the bookmakers will often overestimate their odds, even against a team that will statistically do better than them, since people will be more inclined to take that bet resulting in the bookmaker making more money if the team the models favored wins [^6]. Furthermore, bookmakers will often "hedge" bets to cover potential losses if an unexpected outcome occurs. For example, if a large amount of people are betting on a team regardless of the odds, the bookmakers will have a large payout if that outcome occurs, so they will start offering more favorable odds on the opposite outcome so they can bring in bets that would cover their losses[^5]. Although hedging reduces the risk for bookmakers, gamblers found a way to use hedging as a tool for AI models created in attempts to "beat the bookies". 








## 5. Possion Model

## 6. AI Driven Prediction Algorithms Created by Gamblers

## 7. Conclusion

## 8. References

[^1]: “INSIGHT: Sports Betting in States Races on a Year After SCOTUS Overturns Ban,” Bloomberg Law, 04-Jun-2019. [Online]. Available: <https://news.bloomberglaw.com/us-law-week/insight-sports-betting-in-states-races-on-a-year-after-scotus-overturns-ban>.

[^2]: Research and Markets, “Global Sports Betting Market Worth $85 Billion in 2019 - Industry Assessment and Forecasts Throughout 2020-2025,” GlobeNewswire News Room, 31-Aug-2020. [Online]. Available: <https://www.globenewswire.com/news-release/2020/08/31/2086041/0/en/Global-Sports-Betting-Market-Worth-85-Billion-in-2019-Industry-Assessment-and-Forecasts-Throughout-2020-2025.html>.

[^3]: M. Trenhaile, “How Bookmakers Create their Odds, from a Former Odds Compiler,” Medium, 29-Jun-2017. [Online]. Available: <https://medium.com/@TrademateSports/how-bookmakers-create-their-odds-from-a-former-odds-compiler-5b36b4937439>. [Accessed: Nov-2020]. 

[^4]: “How Big Data Analytics Are Transforming the Global Gambling Industry,” Analytics Insight, 17-Jan-2020. [Online]. Available: <https://www.analyticsinsight.net/how-big-data-analytics-are-transforming-the-global-gambling-industry/>. [Accessed: Oct-2020]. 

[^5]: arXiv, “The Secret Betting Strategy That Beats Online Bookmakers,” MIT Technology Review, 19-Oct-2017. [Online]. Available: <https://www.technologyreview.com/2017/10/19/67760/the-secret-betting-strategy-that-beats-online-bookmakers/>. [Accessed: 2020]. 

[^6]: A. Dörr, “How to apply predictive analytics to Premiership football to beat the bookies﻿,” Dataconomy, 19-Mar-2019. [Online]. Available: <https://dataconomy.com/2019/03/how-to-apply-predictive-analytics-to-premiership-football-to-beat-the-bookies%EF%BB%BF/>. [Accessed: 2020]. 
