# COVID-19-complete-EDA-analysis
**The virus has spread rapidly across the globe and has caused significant damage to human health and the global economy. In this report, we will analyze the 6 months (2020) global covid data helps to identify the multiple factors of spreading the COVID-19 virus worldwide and discuss measures to overcome the pandemic.**

##Goal
To identify the reason behind the spreading of the coronavirus

##Data
Global covid data contains multiple information about different locations like case data, hospital data, prevention data, and location data.

##Method
Determinig the objective,
Gathering the data,
Cleaning the data
Explore the data (EDA)

##Tools & Technology
Jupiter notebook, Python, pandas library, Plotly library.

##Process of analyzing the data
First analyze the country report confirmed cases, recovered cases, deaths cases, and activ cases according to population and case number we can identify the most affected and needed area for taking action. (fig1) <br>
As of the date of this report, the total number of confirmed COVID-19 cases worldwide is over 259 million. The top ten countries with the highest number of confirmed cases are the United States, India, Brazil, Russia, France, the United Kingdom, Spain, Italy, Brazil, Russia, the United Kingdom, Germany, France, Turkey, and Iran. The United States has the highest number of confirmed cases, with over 80 million cases and over 453,013 deaths. So we can analyze every country individually here and next, we will take Italy's data to analyze the reason behind the spreading (fig2). Where Confirmed case 14931210, the Recovery percentage is 43.01%, the death percentage is 13.42%, and the active percentage is 43.56% according to the calculation death and the active percentage are high so need to analyze hospital measures and prevention measures. <br>

Second analyze the hospital data of hospitalized patients, ICU, and Ventilations numberwhich helps to look into the hospital facilities where the government takes action to increase beds, ventilation, ICU, and Medicine facilities to overcome the death rate. <br>
For that, we have created a graph in the comparison of confirmed cases and hospitalized patients to identify the actual numbers of hospital beds, ICU, and Ventilation facilities. According to day wise graph, we can easily identify the number of cases increasing hospitalize patients number decreasing which indicates looking into hospital in-depth data(fig3). <br>

Third analyze the stringency_index total numbers of all prevention like school closure, an international movement, contract tracing, etc (1-100 strictness higher number). According to Italy's stringency_index number and we can analyze the month may the confirmed case increasing and the stringency_index number decreased (fig4) which indicates the lack of prevention so we have to look at all prevention measure data where have to take action (fig5). <br>

Overall covid data analysis can provide valuable insights that can inform public health policies and interventions aimed at controlling the spread of the virus and mitigating its impact on public health. <br>

Also, we can analyze through bar graph:
* The most affected area (fig6)
* Percentage of recovered cases (fig7)
* Percentage of death cases (fig8)
* Percentage of active cases (fig9)

##Conclusion
Understanding the spread of the virus: Covid data analysis can help in identifying the geographic areas that are most affected by the virus, and the rate at which the virus is spreading in those areas. This information can be used to target resources and efforts toward areas that need it the most. <br>
Predicting future trends: By analyzing patterns and trends in covid data, we can make predictions about future infection rates, hospitalizations, and deaths. This information can be used to plan and prepare for future surges in cases and to allocate resources accordingly. <br>
Assessing the effectiveness of interventions: Covid data analysis can help in evaluating the effectiveness of interventions such as social distancing, Contract tracing, international movements, etc. By analyzing trends in infection rates before and after the implementation of these interventions, we can determine their impact on controlling the spread of the virus. <br>

###Appendix
Figure 1:
![Screenshot (523)](https://user-images.githubusercontent.com/61973220/234777590-be1e156f-0fcb-4a00-acf4-870c72bc7fe2.png)

Figure 2:
![Screenshot (524)](https://user-images.githubusercontent.com/61973220/234777636-0da9e577-4392-4d6d-8f18-03bd3115cfe5.png)

Figure 3:
![Screenshot (525)](https://user-images.githubusercontent.com/61973220/234777679-8802d14c-e90d-4302-b22e-262917662a44.png)

Figure 4:
![Screenshot (527)](https://user-images.githubusercontent.com/61973220/234777730-ec550ac6-1ba0-44af-aac2-949677ee245b.png)

Figure 5:
![Screenshot (528)](https://user-images.githubusercontent.com/61973220/234777805-2df4cf11-d923-428a-aa69-3fd089a5709c.png)

Figure 6:
![Screenshot (529)](https://user-images.githubusercontent.com/61973220/234777865-91d6a274-0634-48f8-a617-88e9610292d3.png)

Figure 7:
![Screenshot (530)](https://user-images.githubusercontent.com/61973220/234777935-fc4c5afd-0392-42c7-9b4c-92d4497bc354.png)

Figure 8:
![Screenshot (531)](https://user-images.githubusercontent.com/61973220/234778005-e6fa6275-9c6c-411b-8140-52c15e9a1546.png)

Figure 9:
![Screenshot (532)](https://user-images.githubusercontent.com/61973220/234778059-07cfc8e6-13b6-4a54-8022-67f40f6308d3.png)
