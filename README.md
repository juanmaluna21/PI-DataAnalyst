<h1 align='center'>
 <b>Individual Project - Data Analyst</b>
</h1>

Welcome to this project! On this occasion I am taking the roll of a Data Analyst.

-----------------------

### `Context`

We took the role of Data Analyst where one of our clients belongs to the telecommunications industry.

This Argentinian company asked us to carry out a complete study of the sector's behavior, in order to guide them to provide good quality services, identify growth opportunities, and be able to propose customized solutions to their potential clients.

The objective is to increase internet service access by 2% for the next quarter, per 100 households, per state. Additionally, 3 additional KPIs were required to complement the analysis.

In order to meet the customer's demand, we conducted a deep analysis of the datasets available on this [link](https://datosabiertos.enacom.gob.ar/home).


### `Data Exploratory Analysis (DEA)`

[dea_main.ipynb](https://github.com/juanmaluna21/PI-DataAnalyst/blob/main/dea_main.ipynb)

Several analyses were carried out on each dataset, focusing on 8 of them.

***Incomes***

We found out the internet access per 100 households is increasing over the years. This is very positive for the goal of 2%, set by the client.

***Different Services***

Over the years we can see that the sector of internet has been offering access via different services:
- ADSL 
- Cable modem
- Fiber Optic
- Wireless
- Others

The analysis begins in 2014, and in that year, it can be observed that fiber optics did not have a significant weight in the industry, so it can be deduced that it is a new technology that was just entering to the market.
The case was different for ADSL and Cable Modem, which occupied a large part.

During the course of the years, this situation changed. Fiber optics began to grow and gain ground, specially over ADSL, which was losing weight against both technologies because they provide faster connectivity, so it is expected that this will continue in the same way in future.

Now the next question would be how the market distribution will be for Fiber Optics and Cable Modem. Although both have a positive development during the analyzed period (2014-2022), currently Cable Modem has a larger market share.

However, this analysis cannot end here, although both technologies are growing, in the last part of the analyzed period, a small decline in the slope of Cable Modem is seen. The opposite happens with fiber optics, which continues to grow due to its ability to connect different points at great distances without losing signal.

In addition, by transporting photons of light instead of electric current, they are immune to electromagnetic interference, which affects cable modem.

That said, it can be deduced that in the near future, fiber optics will replace cable modem.


***Download speed average per state***

For this analysis, download speed could be taken, also, as a customer satisfaction ratio, since the higher it is, the shorter the user waits. It has been increasing over the past few years due to the strong investment made by the companies in this market to improve their service and attract more customers.

Analyzing by states, it can be seen that in Buenos Aires, specially in Capital Federal, download speed is much higher than in other states (on average, download speed in Capital Federal is a little over 35Mbps), having a difference of about 6 times with the slowest state, which is approximately 5Mbps.


### `Additional KPIs`

+ Complaints distribution per service: If well, in Argentina, complaints come mostly for telephone service with 50%, "internet" complaints are high as well with 30% of the total. This is an indicator of how satisfied clients are with the service.

+ Average incomes per state: Average incomes per state rise up to 30 millions. If well it is not an accurate measure, it gives us a first idea of how much states apport to the incomes.

+ Average download speed in Argentina: This is a good measure to compare with other countries in order to compare service quality.


### `Presentation`

[Presentation](https://github.com/juanmaluna21/PI-DataAnalyst/blob/main/Presentation.pbix)

In order to communicate the results to our client, we chose to do it through the Power BI program, to show trends and behaviors of the variables.


### `Recommendations`

Based on the above, we can see that the objective of increasing connectivity access by 2% per state is possible. This market sector growing, so the company could take advantage of it.

The possible investments in infrastructure expansion can lead to increased revenue for companies providing such services.

In case the company decide to pursue this objective, it is recommended to do it through the fiber optic service, as it provides better service benefits at a lower cost. This can generate sustained growth in customers, leading to increased revenue.

The state with the highest internet access is Buenos Aires, specifically in Capital Federal, and also has the highest download speed. Hence, it can be said that the market with the easiest access is Capital Federal since it already has an infrastructure for providing internet service to many clients. However, at the same time, customer satisfaction is high, so entering this market may not generate many changes, making it more difficult to achieve the objective of increasing connectivity access by 2%.

On the other hand, if the strategy is to first enter the provinces with lower quality services, it may be easier to achieve this objective.

Appart of this analysis, I would like to indicate that there are other factors to be consider if an investment needs to be done in this sector, such as the economic situation of the country, costs of infrastructure, etc.