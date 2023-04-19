 #Capstone Project - SI 699
 
Are Celebrity Endorsements Worth The Money?
- Nitanshi Mahajan and Emily Schemanske

## Abstract
Are celebrity endorsements worth the money? 

Many companies use celebrities to promote their products; a wise move since, according to Forbes, a company could see as much as a 4% increase in sales almost immediately after an endorsement deal is signed (Olenski). At the same time, these lucrative deals are not without risk. Recent public scandals and the rise of “cancel culture” have  raised questions about the potential financial impact on companies when things go wrong.

This paper aims to understand the degree to which a company’s financial performance may be impacted by a celebrity endorser’s scandal, using empirical data and case study to provide a preliminary analysis of the issue. The overarching question will be, how can we measure such a thing? By shedding light on this topic, this study offers valuable insights for companies looking to weigh the risks and benefits of celebrity endorsements in today’s highly competitive market.

## Methodology
Our first task is to quantify a “scandal”. We will do this by applying Natural Language Processing techniques to extract sentiment from published articles - in particular, Us Weekly magazine. We will combine our insights from that analysis with stock data for the company to understand the degree to which it impacts a stock’s performance. For this part of the analysis we will use linear regression to build a model and interpret the results.

Finally, we will visualize the data to get a holistic view of the relationship between celebrity and company. For this case study, we will look at the nine year long partnership of Kanye West and Adidas.

## Instructions
To rreproduce the results, run the code files in the following order - 

1. 1_Data_Collection_US_Weekly.ipynb
2. 2_Sentiment Analysis Modeling.ipynb
3. 3_monthly_fin_data.ipynb
4. 4_linear_model_prep.ipynb

All the intermediate data files are uploaded to see the regression model, directly run the 4_linear_model_prep.ipynb file.
