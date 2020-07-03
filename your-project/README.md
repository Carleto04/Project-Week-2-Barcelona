<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Where is love? Where is love from?
*By Erwan de Boisjolly and Carles Rosell Bernat*

*Data Analysis, Ironhack_Bcn & 30/06/2020*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Repository structure](#Repository-structure)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)


## Project Description
Because we are from different spots in the world, and Barcelona is an international city, we wonder how different nationalities and languages have spread through the city.
Also, mapping in a funny way nationality preferences to find your perfect love and what languages skills you need to fancy them.

## Questions & Hypotheses
1. What are the top3 spoken languages in Barcelona (supposing each nationality has only one exclusive official language)? <br>
2. Where is Russian district in Barcelona? <br>
3. If you want to meet the love of your life, where should you go according to your sex preferences? <br>

## Dataset
Our DataSet is called "Official population's nationality classified by genre of the city of Barcelona". 
URL: https://opendata-ajuntament.barcelona.cat/data/en/dataset/est-ine-nacionalitat/resource/04d2b7f1-63b6-422e-bf2b-079d5046e09a
The data refers to the readings of the living population of Barcelona on the first of January of 2019, approved by the INE (Instituto Nacinal de Estadística) and classified by nationality and genre.

## Repository structure
- Jupiter Notebook with python code of the game: Barcelona_Nationalities.ipynb
- The current README file: README.md
- The presentation of the project: Presentation_Barcelona-project.pdf
- A screenshot of my Trello board: trello_projectBCN_board.pdf
- The dataset file: 2019_ine_nacionalitat_per_sexe.csv


## Workflow
1. ".gitignore" file creation
2. Choosing the topic, in our case was "population"
3. Formulate questions-hypotheses
4. Research for a proper DataSet
5. Organize the following tasks

## Organization
Using Trello board to reference and organize each task. Trello screenshot is available in main repository.
1. Analysis: <br>
	1.1. Display the DataFrame structure <br>
	1.2. Display potential missing values (there was none) <br>
	1.3. Display main statistics in DataFrame <br>
	1.4. Display histograms <br>
	1.5. Verify possible mistakes inside references (District Code - District Numero and Neighborhood Code - Neighborhood Numero) <br>
	1.6. Display main statistics in column 'Number' (the only one with int) <br>
	1.7. Crossed display Gender and Nationality with Number <br>
	1.8. Crossed display Gender and District Name with Number <br>
2. Categorical Variables: <br>
	2.1. Display data per district <br>
	2.2. Display data per Neighborhood <br>
	2.3. Display data per Gender <br>
	2.4. Display data per Nationality <br>
3. Dataset cleaning: <br>
	3.1. Create a security copy for the DataFrame <br>
	3.2. Drop unwanted columns: 'Year', 'Neighborhood_Code', 'District_Code' <br>
	3.3. Translate columns Cat/Eng <br>
	3.4. Drop unwanted data <br>
	3.5. Translate data in columns Cat/Eng <br>
4. Dataset Analysis: <br>
	4.1. Question 1: What are the top3 spoken languages in Barcelona? <br>
	4.2. Question 2: Where is Chinatown in Barcelona? <br>
	4.3. Question 3: If you want to meet the love of your life, where should you go according to your sex preferences? <br>

## Links
[Repository](https://github.com/ErwanDB/Project-Week-2-Barcelona)  
[Slides](https://1drv.ms/b/s!AlSM8HZzXfwPxXcEnJ8EPP2uLBlk)  
[Trello](https://trello.com/b/NRbRo5ZD/project-week-2-barcelona)  
