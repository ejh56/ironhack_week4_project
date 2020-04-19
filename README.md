# Sustainability with World Bank Data
*Emily Horton*

*DAFT March 2020, Berlin*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-and-hypotheses)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Limitations](#limitations)
- [Links](#links)

## Project Description
Looking at the UN's Sustainable Development Goals Dataset (SDG), I was curious to explore what factors were related to a country's status on the Climate Change Vulnerability Index. By combining two World Bank climate change datasets with the SDG dataset, I was able to show how temperature, rainfall, crop yield, and poverty differ between high risk countries and the rest of the world.

## Questions and Hypotheses
* Without previous knowledge of what factors are considered in climate change vulnerability, can I show how different climate factors are connected to the index? 
* What variables would differ between high risk countries and the rest of the world?

## Dataset
[SDG Dataset](https://www.kaggle.com/alahbs/global-sustainable-development-goals-data/data)
The SDG dataset contains two tables - an in depth global index and a time-series. The data in this set is from 2000 until 2018. For more about the dataset and SDG, click here: https://www.sdgindex.org/

[World Bank Climate Change Data](https://climateknowledgeportal.worldbank.org/download-data)
The climate change data focuses on percipitation and temperature. I downloaded information for all countries, from 1991 until 2016. This limited the SDG Dataset to 2016 as well. 

## Workflow
1. Explore the data and discover what I do not understand
2. Research topics to see what different columns mean and how they are calculated
3. Decide whether or not to use provided normalized data
4. Sketch what the final story should look like
5. Tableau
6. Adjust visualizations to show a range of graph types, animation skills, and add annotations

## Limitations
For many countries, there are years where there is no data. Additionally, there can be an issue with reporting data. Although it is not ideal, the graphs still show the general relationship between different traits; however, they should not be assumed to be a complete representation.  

Additionally the SDG dataset included normailzed columns, but no documentation on how these columns were normalized. I chose to use unnormalized data because the columns I chose to analyse were not influenced by population size, or were already adjusted. 

## Links
[Repository](https://github.com/ejh56/ironhack_week4_project) 

[Tableau Public](https://public.tableau.com/profile/emily.horton3683#!/vizhome/Climate_Change_Vulnerability/Story1)
