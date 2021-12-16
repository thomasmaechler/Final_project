# Running and data vizualization

Final Project Ironhack by Thomas Maechler December 2021



I did differents vizualizations thanks to tableau to understand better the data i collected from the run of my friend in Paris. 

<img width="1252" alt="Screenshot 2021-12-16 at 18 19 20" src="https://user-images.githubusercontent.com/90766942/146418585-be851676-3980-4a71-8569-dff57eda5b9b.png">


## Agenda


- [Usefull links](https://github.com/thomasmaechler/Final_project#Usefull-links)
- [The Aim](https://github.com/thomasmaechler/Final_project#The-aim)
- [Process](https://github.com/thomasmaechler/Final_project#Process)
- [Tools](https://github.com/thomasmaechler/Final_project#Tools)
- [Key Take Aways](https://github.com/thomasmaechler/Final_project#Key-Take-Aways)



## Usefull links


- **Tableau**: [Link](https://public.tableau.com/app/profile/thomas.maechler/viz/FromStravatoTableauEdouard/Pollution2?publish=yes) 
- **Jupyter notebook**: Issue with the file (ask sian) 
- **Ajuntament** : [Lien](ttps://ajuntament.barcelona.cat/qualitataire/en/qualitat-de-laire/com-es-lluita-contra-la-contaminacio/barcelona-public-health-agency)
- **Data of airpollution in paris** [Lien](https://www.airparif.asso.fr/toutes-nos-cartes)
- **Data Weather** [Lien](https://www.meteoblue.com/fr/meteo/archive/export/paris_france_2988507)
- **Strava** [Lien](https://www.strava.com/)
- **Garmin** [Lien](https://www.garmin.com/fr-FR/account/)
- **Alteryx** [Lien](https://www.alteryx.com/fr/)


## The Aim

The aim of my project is to advice one of my friend runs based on his data. 

The idea was to import data from Garmin and Strava and compare this data to weather and pollution data.
That could help him to better understand the impact of his run on his health. 
He is located in Paris and his run goes from 2018 to 2021. I decided to focus on 2021.


## Process: 

**Strava**
- 1 - I ask my friend to give me access to his Strava to extract his data with an API. Unfortunately i understood later i will not need the API to extract the data.
<img width="1020" alt="Screenshot 2021-12-16 at 20 04 14" src="https://user-images.githubusercontent.com/90766942/146433702-abf9830c-fe52-47c1-93b1-08182693bf4e.png">

<img width="1061" alt="Screenshot 2021-12-16 at 20 03 59" src="https://user-images.githubusercontent.com/90766942/146433710-be4139c2-63d0-4b12-baae-66f622d96e8b.png">


**Alteryx**
- 2 - I extract the data from Strava and then i used Alteryx. ALteryx can be used to speed up your processes (accounting close, tax filings, regulatory reporting, forecast creation), automate processes (reconciliations, consolidations, marketing workflows, system integrations, continuous audits), and enable predictive and geospatial solutions. So, in my case was really usefull so i can use the data from stava, into files readable for Tableau.

**Tableau - Strava Data**
- 3 - I used Tableau to import the data and get some graph about Where, and when he is running. ALso i get a graph of HR/Mph to see how his Heartbeat is reacting to his speed.

**Excel - Managing the data**
- 4 - Normally we use python in class to clean and manage the data. But in my case the data was structured and i just nedeed to delete columns and change points into coma. So i thought it was faster in excel. 

**Tableau - Weather & Pollution Data**
- 5 - After understanding better how the data looks like, i tried to understand the impact of the pollution and the weather on his run and also the correlation between the pollution and the weather. 

**Tableau - Comparision**
- 6 - Then, i compared the data of Paris (where he is running) with the one of Barcelona. To see obvious correlation or not. That help us to better understand the amount of polution of paris compared to an other big europpeans city. Also the choice of Barcelona is done because i love this city and i would love my friends to come living here. 

**Tableau - Dashboard**
- 7 - This allowed me to better understand the impact of pollution in both cities, but i wanted my friends to better understand the impact of his previsous runs on his health, so i created a dashboard linked on the weather and the pollution amount. So he can adapt his life on the pollution (or not) and live longer (maybe). 

  
  
## Tools 

- **Excel**: [](url)

- **Vizualizations**: [Tableau](https://public.tableau.com/authoring/Case-Study-Classification_16369900928240/Dashboard1#1)

- **Alteryx**:[](https://www.alteryx.com/fr/)



## Key Take Aways

**Conclusion**
- My visualisation was really challenging with some difficulties for a picture where i spent 1-2 hours just to find a solution. It's a lot of little step that makes me discovering things in Tableau i did not knew. It was really interesting. 
The project himself is interesting for me to see the relation between two things i like: Sports and Climate. 

**Improvement**
- I could have imporve many thing in my visualisations. 
First the design, is simple but could have been more pretty. 
Secondly, the data used for the dashboard is only for 2021, coudl have been cool to have more data and also to compare with data of Barcelona. 
Thirdly, could have been cool to make it more sharable so anyone can put his data and it gives the informations. 




Thank you for checking my repo.
