# Smart-City-YVR
Smart City YVR is an innovative project leveraging data-driven methodologies to analyze and address critical aspects of urban living. Focusing on housing affordability, energy consumption, and transportation, this initiative utilizes advanced data analytics to derive actionable insights.
The aim of this project is to use a data driven approach to address them. The goal is to identify areas of concerns, provide with data backed trends and concerns that might arise in future and give insights helping us understand. We aim to use the Big Data Technologies to process the Raw data into useful insights.
We have taken up three major issues: Housing Affordability, Energy Consumption, Public Transport Connectivity
Task and Technologies used:
ETL, Analytics, Machine Learning: Python, Spark, Pandas
Data Visualization: Matplotlib, Folium, NumPy

## Overview: 
The Urban Areas (Vancouver and adj. cities) grapple with challenges that hinder the sustainability and Quality of life. We aim to address by data-centric approach to three critical challenges faced. These pivotal issues prevalent in urban areas are Housing affordability, Energy Consumptions, Public Transportation constraints. By utilizing our understanding with big data Technologies and data analytics to find various insights to understand the key factors causing that. This is scalable to other urban areas with similar challenges.

## Problem Definition:
•	For the urban areas (Vancouver & adj. cities), we identify three pressing issues that stand out: Housing affordability, Energy Consumption and Public Transportation. These issues not only strain resources but also impact environmental well-being and quality of life.

•	Challenges Encountered:
1.	Housing Affordability: Housing affordability concerns can lead to social disparities and limit access to suitable living spaces, affecting the well-being of individuals and communities.
2.	Energy Consumption: The high energy consumption leads to high carbon emissions and leads to environmental degradation by residential and commercial industries.
3.	Public Transportation: Inefficient Transportation leads to impact the day-to-day commute and quality of life. 

## Approach to the Problem: 

•	We’ve tried to approach these problems by using the big data tools that we learnt in Fall semester. We have gathered and curated three primary datasets – Housing, Energy and Transportation specific to Vancouver areas. We have done lot of research for the accomplishments of the datasets on the web for its comprehensive coverage. We have obtained these 10 total files downloaded from the credible online sources for Vancouver areas and used tools Python, Spark, Pandas, Folium, Matplotlib, Numpy

•	We leveraged the Big data tool Spark, acquired during the Fall semester for raw data processing and analysis. We conducted initial assessment of datasets to ascertain their scope, relevance, and potential. Then, we engaged in extensive ETL work to refine and structure the raw data we have. The data was cleaned based on the observations in the initial analysis. During the cleaning, we have filtered the dataset as per requirements, remove the data that is out of scope, remove nulls values, address the columns of integer containing strings etc.

•	To extend the analysis scope we performed the dataset joins to different datasets to the primary dataset to enhance and retrieve the meaningful data out of it. Now the data was ready for the analysis for all the three pipelines of Housing, Energy and Transportation.

•	The preprocessing is done in Spark as it uses the in-memory processing. We choose to use Spark as a tool because of its benefits in the context of big data and scalable options for large volumes of data. Moreover, because of it’s low-latency processing capability, Spark can handle a diverse analytic challenge. Additionally, it has well designed libraries for Machine Learning were instrumental in our analyses.

•	Our data analysis delved extensively into three main pipelines on the Housing, Energy and Transportation pipelines to fetch the metrics in spark by creating the different data frames. For Housing – we examined property value appreciation over years in areas, Impact of property age on its value, Price to Income ratio, Tax burdens w.r.t average incomes.

•	For Energy pipeline – metrics such as Co2 emission based on Vancouver areas over the years, Total energy consumption for the residential and Industrials, Distribution of Co2 emission in different areas and then in different sub sector. Also, emission on the source level, the source with max Co2 emission distribution area wise are investigated.

•	For the Transportation pipeline – metrics such as Services availability for each day, busy stops, trips in different directions, stop frequencies, availability of service at the hour of the day, trips on various routes etc.

•	Moreover, we have constructed the Machine Leaning models demonstrating – to predict Mean predicted values by Neighbourhood for Housing using three different models (GBTRegressor, RandomForest, Linear regression) and For Energy, a linear regression model to trend and forecast the Co2 emissions in Vancouver areas in next four years leveraging historical dataset.

•	Upon extracting valuable metrics from various datasets, we proceed to visualize the plots. For the scope of this project, we have used the matplotlib that helps to understand the trends better and more visual appealing for the findings.

## Results:
•	Uncovered the correlations between property values, land values,price-to-income ratio, tax burdens, shedding lights on housing market affordability dynamics.

•	For Housing Affordability: Three biggest takeaways are the exponential increase in price of houses in 2022 has impacted the housing affordability. The burden of Property Tax on residential property has equal impact and it should be capped according to average income of demographics. Finally, the major increase in the land value with respect to improvement value of a house should be restrained. 

•	Analysed the areas where the Co2 emission trends are high, energy consumption patterns, highlighting areas for the environmental sustainability and improved quality of life by moving more towards renewable energy than non-renewable sources.

•	For the Transportation – there should be enhancing services for the routes Surrey to Burnaby areas to connect various routes effectively, there's an observation in the number of busy stops (hubs) between Burnaby and Surrey sides. Burnaby has high concentration of busy hubs, while Surrey has fewer, indicating an opportunity to create more connections in Surrey for better accessibility across different locations. It’ll foster greater convenience for commuters and enhancing overall transportation efficiency.

•	The Machine Learning models serve as valuable tools to anticipate the housing trends and plan strategies for energy consumption for environmental conservation.

•	Utilized the Matplotlib and Folium for data visualization, creating intuitive and informative graphs and maps.

•	The data analysis helps us understand the property and income patterns for the housing affordability and for energy, which all areas have more Co2 emission by which energy resource and needs to find alternatives to non-renewable energy as it produces more Co2 emissions. We observe the trends based on Source, areas, type of Orgs. 

•	Adapted to new tools like Matplotlib and Folium to convey the data insights visually presentable.

•	Understanding to real-time problem via diverse datasets for effective integration and analysis.

•	Leveraged the Spark’s capacity for preprocessing and analysis, understanding the practical implementation on real dataset for problem solving perspective.

## Summary:
•	The project helps us explore the vastness of big data and solve real time problems while learning and implementing the big data.

•	The datasets that are large and messy, though using the data engineering and analytics, we can uncover the hidden insights in the datasets, patterns, correlations, market trends, understand surroundings etc, these analytical findings can help stakeholders to make informed decisions, government with policies and better future, new opportunities, and various services.

•	As a team, we have also able to learn and tackle the data challenges, its understanding, new tools, this was a valuable experience for us.

THANK YOU!











