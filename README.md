# codeathome_Group14
Abgabe der TechLabs #codeathome Bootcamp Challenge - Group14

Please open the website first (go to the website folder and download the html document). 
The images in the folder are needed too to open the website.
Further you can find two different data sets & their analysis (Covid19 and TripAdvisor) the notebook/data set folder as well as a prediction on TripAdvisor data. 
Additionally, we provide all code created (e.g. the TripAdvisor crawler).


Problem9, Group 14: How might we help local businesses?
Title of the project: “betterCALLkilian”

Q1: Which is the problem the solution solves? 
The impact of Covid19 restrictions causes problems all over the world. Almost every industry is suffering from the worldwide lockdown of borders and business. Covid19 will probably be followed by a recession all over the globe. Especially local businesses in traditional industries will struggle to survive the financial loss from the pandemic. Local businesses like restaurants, retail stores, bakeries, hotels, fitness studios or cinemas are close to bankruptcy. How can data help local businesses and what insights can be generated from Covid19 data?
The project “betterCALLkilian” is a solution design to help local tourism.
Our groups solution approach is to find out about interdependencies of Covid19 infections within specific regions (e.g. Hamburg in Germany) and its impact on reviews for local attractions. The ultimate solution idea is to design a model for predicting the destination tourists could alternatively select in case of local shut down. 
To exemplify a potential scenario the following situation is analyzed: How can a data model foresee an alternative for tourists who actually planned to visit the Miniatur Wunderland in Hamburg but cannot travel there due to travel restrictions? “betterCALLkilian” analyzes open data from the review platform tripadvisor to formulate future preferences for tourists to steer the tourist to another preferred local business.

Q2: Solution Pitch 
•	The Problem: Local businesses in the tourism sector are heavily suffering from regional and local lockdowns.
•	The solution: Step 1- Data sets from of regional Covid19 cases (e.g. time series, regions, age categories) are analyzed and ploted.
•	Step 2- Generating and analyzing data from tripadvisor with the “betterCALLkilian” machine learning crawling algorithm for tourist preferences by categories (e.g. activities, locations, age, evaluations). Step3- Gaining insights from the data to foresee travel alternatives for users in case Covid19 is causing local lockdowns.
•	The vision: “betterCALLkilian” helps local tourism to generate alternatives for tourism in case of lockdowns.

Q3: The solution 
The “betterCALLkilian” data model works as described in the solution pitch. The data base for the project is a Covid19 data set for Germany. This data set is ploted (all codes are saved in Google Colab) and shows the time series of Covid19 infections in Hamburg (see graph below).
 
Parallel the “betterCALLkilian” algorithm is generating time series data for tripadvisor reviews in Hamburg and the respective attractions. The next step of the project (that is not coded yet) is to generate data insights from machine learning to guide tourists to alternative travel locations. The timespan of German lockdown initiatives beginning 15th of March 2020 therefore will be analyzed and the events around 12th of May 2020 when first restaurants were allowed to open businesses again. These ranges might give insights on how travel and tourism did change. The idea is that the more product online review features are available to consumers, the higher the likelihood for sales of related items within the product category can be achieved (Chevalier & Mayzlin, 2006).

Q4: Impact on the crisis 
Desirability & Impact: Small business, especially in travel and tourism, need tools to be able to foresee and cope with the ongoing risks that can occur with a second wave of the Covid19 pandemic. The “betterCALLkilian” algorithm will support to avoid financial loss and generate potential sales. The positive impact on society is that consumers and business profit from alternative travel destinations in case of further lockdowns.
Innovation & Creativity:
The innovation in this project is based on finding linkages between ex post Covid19 infection data and open source data on customer reviews from tripadvisor. The model for Hamburg can be a blueprint for areas or countries where Covid19 had or will have a similar development. At this point of the project specific data insights cannot clearly be stated.
The outcome from the team is a basic dataplot from python code, code for a crawler that generates data sets from tripadvisor, a website draft and the formal submission. The code for the crawler was redesigned from an existing blueprint. The group result combines different dimensions of output such as python code for a web crawler, data plots, a website draft and text.
Feasibility & Prototype Completion
The mvp is plots and python code to generate data sets. The new developed crawler code can generate .csv data.
Viability & Sustainability:
The code can be adjusted to open the scope for analysis for other cities or countries which is not Hamburg.

WOW – Effect:
Our WOW effect?! You “betterCALLkilian”!
