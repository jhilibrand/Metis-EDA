# EDA Project Proposal

Question: 
How "back to work" are we? This is an analysis of how certain areas of NYC have scaled up their office presence, using commute traffic on MTA as an indicator. This is a question that many commercial space developers or service industries may want to answer (Where should X brand open a popular salad lunch spot? Where are there more office space vacancies for Y company to get optimal pricing on a new office?) 

Data Description: 
I will use MTA turnstile data from 2019, 2020, and 2021 gathered from http://web.mta.info/developers/turnstile.html
There will be two parts to my analysis. For part 1, I aim to analyze net flows per time block to highlight station areas that are in typical "commute zones" (pre-Covid). This will be finding stations that have high exit traffic in the morning and/or high entry traffic in the evening. For the second part of my analsyis, I aim to look at these "commute zone" stations across three time periods: pre-Covid (Apr & May 2019), peak-Covid (Apr & May 2020), and late-Covid (Apr & May 2021). Ideally I will add a fourth analysis eventually (post-Covid) to see if our working landscape meaningfully changed. 
I aim to have a metric to compare how different "commute zone" areas compare to 1) their pre-Covid levels and 2) each other (are some recovering more quickly than others?) 

Tools/MVP: 
The majority of my analysis will be done in pandas (as well as utilize matplotlib and ideally plotly). An MVP for this project would be a template that can analyze and contextualize new MTA commuter data to get a better understanding of how the NYC commute and workspace flows are shifting as the city reopens.  


