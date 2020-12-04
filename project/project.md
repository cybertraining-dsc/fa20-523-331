# Big Data in Sports Game Predictions and How It is Used in Sports Gambling

[![Check Report](https://github.com/cybertraining-dsc/fa20-523-331/workflows/Check%20Report/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-331/actions)
[![Status](https://github.com/cybertraining-dsc/fa20-523-331/workflows/Status/badge.svg)](https://github.com/cybertraining-dsc/fa20-523-331/actions)
Status: in progress

- [ ] see our sample template at <https://cybertraining-dsc.github.io/report/> for an elaborate example
- [ ] please continue to make progress

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

Nov 21: Research on Tax and Joustra and Davoodi and Khanteymoori sports prediction models

November 31: Possion distribution model used in sports prediction, make own possion distrubution with premier league data using R






## 3. How bookmakes Determine odds

It is no secret that bookmakers use a lot of data and apply various statistical techniques to come up with betting odds. The statistical techniques used and the data that bookmakers look at vary from sport to sport, for example, the most popular method for modeling soccer uses the poisson distribution since it can be very accurate but also because it makes it easy to add time decay to the inputs [^3].Bookmakers employ various mathematicians to analyze historical sports data to come up with odds; however, sports data isn’t the only thing that bookmakers look at when determining how they will make odds for a game. At the end of the day, the gamlbing industry is a numbers game that thrives on ensuring the probability is in the houses favor. Bookmakers use various techniques involving big data in order to do so. 

Big data is being used more and more in various industries, and in the gambling industry, it isn't just used to come up with odds. One major way it is used is by gathering data about user demographics [^4]. When using an online sportsbook, the casino can gather data about a users age, location, gender, excetera which can provide valuable insights that can be used for product development and marketing purposes. By using user demographic data to provide targeted advertising, casinos and bookmakers can attract more betters which will increase revenue. As said by former odds compiler Matthew Trenhaile, "Their [bookmakers] product is entertainment and not the selling of an intellectual contest between punter and bookmaker. It is foolish to think this has ever been the product that bookmakers have sold.They sell an adrenaline rush and anyone who thinks great characters pitting themselves against the punters and taking anyone on in horse racing betting rings is what betting used to be about is kidding himself or herself." Due to the probability of making money in sports betting, and really every type of gambling, being in the houses favor, online casinos and sportsbooks use big data to increase the number of bets placed by customers. Nevertheless, using models to come up with odds is the heart of this industry which makes it the most important way big data analytics is used by bookmakers.
	
When odds are being made for a sports book, a lot of things are taken into consideration in the process. Bookmakers have teams of statisticians that analyze historical data of the teams in order to come up with game prediction models[^5]. When bookmakers are actually making the odds, these statistical models created from large amounts of data aren't the only thing they use. When bookmakers are creating odds, their goal is to have the lowest probability of paying out, so they will also use public opinion along with their statistical models to do this. For example, if a team has been on an unexpected winning streak the bookmakers will often overestimate their odds, even against a team that will statistically do better than them, since people will be more inclined to take that bet resulting in the bookmaker making more money if the team the models favored wins [^6]. Furthermore, bookmakers will often "hedge" bets to cover potential losses if an unexpected outcome occurs. For example, if a large amount of people are betting on a team regardless of the odds, the bookmakers will have a large payout if that outcome occurs, so they will start offering more favorable odds on the opposite outcome so they can bring in bets that would cover their losses[^5]. 





## 5. Possion Model

## 6. Prediction Alogrithms used By Gamblers

Gamblers often use various models, driven by big data, in order to help them place more accurate bets. Many different models have been created in the sports field that use factors such as historical sports data in order to come up with game prediction models. In research done by Manuel Silvero, he studied 5 famous algorithms that used Nueral Network and Machine learning and concluded that their accuracy varies from 50-70 percent, depending on the sport [^7]. 

One of the most accurate models created, in terms of recieving a good return on a bet, was created by Lisandro Kaunitz of the University of Tokyo, and relied on data from odds that boomkmakers put out rather than historical game data [^6]. When it comes to stastical models for sports, big data from historcal sports games are often analyized in order to come up with game predictions and to gain insight on things like team, player, and position performance. In the market of sports betting, these models are used to come up with odds and also by bettors to place bets. Gamblers have often tried different game prediction models in order to beat the books, but sucess if very rare since bookmakers employe various statasticions and data analysis experts in order to come up with the best game prediction models [^6]. Kaunitz created a model that focused on analysing data of the odds created by bookmakers, rather than sports team data, to predict good bets to place. The basis of his model relied on a tehcnique bookmakers use to reduce their payout risk, known as hedging. This concept and the way bookmakers use it to reduce their risk of payout is covered in section 3. Kaunitz betting model worked by gathering the odds for a game created by various bookmakers and determining the average odds availible. Using statistical analysis of odds offered, Kaunitz was able to determine any outliers from the average odds for a game [^6] . Using these outliers, Kaunitz could determine if a bet would favor them or not. After varous simulations and models, Kaunitz's and his team took their strategy into the real world, and their bets payed out 47.2 percent of the time. They received an 8.5 percent return and profited $957.50 in 265 bets [^6]. Due to their impressive returns, bookmakers caught on and started to limit the amount that they could bet


## 7. Conclusion

## 8. References

[^1]: "INSIGHT: Sports Betting in States Races on a Year After SCOTUS Overturns Ban," Bloomberg Law, 04-Jun-2019. [Online]. Available: <https://news.bloomberglaw.com/us-law-week/insight-sports-betting-in-states-races-on-a-year-after-scotus-overturns-ban>.

[^2]: Research and Markets, "Global Sports Betting Market Worth $85 Billion in 2019 - Industry Assessment and Forecasts Throughout 2020-2025," GlobeNewswire News Room, 31-Aug-2020. [Online]. Available: <https://www.globenewswire.com/news-release/2020/08/31/2086041/0/en/Global-Sports-Betting-Market-Worth-85-Billion-in-2019-Industry-Assessment-and-Forecasts-Throughout-2020-2025.html>.

[^3]: M. Trenhaile, "How Bookmakers Create their Odds, from a Former Odds Compiler," Medium, 29-Jun-2017. [Online]. Available: <https://medium.com/@TrademateSports/how-bookmakers-create-their-odds-from-a-former-odds-compiler-5b36b4937439>. [Accessed: Nov-2020]. 

[^4]: "How Big Data Analytics Are Transforming the Global Gambling Industry," Analytics Insight, 17-Jan-2020. [Online]. Available: <https://www.analyticsinsight.net/how-big-data-analytics-are-transforming-the-global-gambling-industry/>. [Accessed: Oct-2020]. 

[^5]: arXiv, "The Secret Betting Strategy That Beats Online Bookmakers," MIT Technology Review, 19-Oct-2017. [Online]. Available: <https://www.technologyreview.com/2017/10/19/67760/the-secret-betting-strategy-that-beats-online-bookmakers/>. [Accessed: 2020]. 

[^6]: A. Dörr, "How to apply predictive analytics to Premiership football to beat the bookies," Dataconomy, 19-Mar-2019. [Online]. Available: <https://dataconomy.com/2019/03/how-to-apply-predictive-analytics-to-premiership-football-to-beat-the-bookies%EF%BB%BF/>. [Accessed: 2020]. 

[^7]: M. Silverio, "My findings on using machine learning for sports betting: Do bookmakers always win?," Medium, 26-Aug-2020. [Online]. Available: <https://towardsdatascience.com/my-findings-on-using-machine-learning-for-sports-betting-do-bookmakers-always-win-6bc8684baa8c>. [Accessed: 2020]. 
