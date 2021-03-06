# Soil-Mates
Our group project for BIOL 432

Our team name is Soil Mates

Team members:

[Lauryn Joslin](https://github.com/laurynjoslin)

[Nadejda Boev](https://github.com/16nbb1)

[Logan Wisteard](https://github.com/LoganWisteard)

[Joel Sagman](https://github.com/JoelSagman)

Our dataset:
[Bowd, Elle (2021), Data from: Disturbance alters the forest soil microbiome, Dryad, Dataset] (https://doi.org/10.5061/dryad.p8cz8w9qv)

We are looking to investigate the research question of what is the impact of destructive forces (both fire and logging) on the impact of potential measures of soil health? We will be doing this using three subquestions: 

A) of Are destructive forces associated with decreasing microbial diversity? 

B) Are different soil chemical compositions associating with destructive forces? 

C) Are different soil chemical compositions associated with decreasing microbial diversity? 

 

Joel will be investigating subquestion A. He will create boxplots using R’s ggplot package to compare alpha at each site. They will group by destructive force to see if there is a relationship between the destructive force and diversity.
 

Lauryn and Logan will be investigating subquestion B. They will create a series of boxplots to compare the number of disruptive events with levels of each nutrient.

Nadejda will answer subquestion C. By calculating beta diversity using Bray-Curtis's dissimilarity, she will visualize and analyze if sites with fires, salvage logging and clearcut logging cluster and separate well using Non-metric multidimensional scaling (NMDS) ordinations. Additionally, she will attempt to find if a soil health indicator is associated with these clusters. 

 

____

Diagram Outlining our Workflow:

<img width="605" alt="flowchart" src="https://user-images.githubusercontent.com/94632840/161470808-242a9b8d-27df-4858-9494-206a49694a49.png">

_____

Predicted results:

![277245470_665418907845707_8006956865598330293_n](https://user-images.githubusercontent.com/68873262/161539902-38278e83-8d4c-48b1-b3eb-852e809dc36e.jpg)

![275391977_3177582792557608_8949299353905118334_n](https://user-images.githubusercontent.com/68873262/161540216-26f7cdfd-f772-4cbe-a2c5-229d55359e51.jpg)

![277116110_512435110460647_1787797503133910810_n](https://user-images.githubusercontent.com/68873262/161540227-d1ea2888-5395-4ac2-899d-2ef689d041b3.jpg)

______

In order to run this code and observe our report, use ./Soil-Mates/Soil-Mates.Rmd

In order to view final figures, please see .png stored in ./Soil-Mates/Question 1 and ./Soil-Mates/Question 2

The data we used is stored in the Data folder. 

About the dataset we are using: 

Our dataset is from soil samples taken in the Victorian Central Highlands of southeastern Australia. These soil samples were taken at 0-10cm and 20-30cm depths at 80 sites with differing disturbance histories. These histories are comprised of five forest fire-only sites, forest fire sites that were clear cut years later, and a forest fire sites that were salvaged logged directly following a fire. The data includes bacterial, archaeal, and fungal microbial compositions derived from 16S rRNA sequencing. Additionally, scientists quantified ammonium, nitrate, phosphorus, potassium, organic carbon, copper, iron, manganese, and magnesium to determine the chemical makeup of the soil samples. The dataset contains tables of operational taxonomic units (OTUs); therefore we will consider the data as pre-processed. 
