# Web scraping pets in animal shelter

**Note: Readme file will only be updated with major updates on the project. If you need further info about the current status please check the wiki where you will find updated information**

## Context and description of the project
This project started as the first practice of the subject "Tipologia i cicle de vida de les dades" on the master degree in the Open University of Catalonia (UOC)
My goal with this practice is that by using web scraping tools from Python Get a Dataset in csv fomat where the pets in adoption on the CAACB (Centre d'Acollida d'Animals de Companyia de Barcelona), are registered. 
From now on this csv file will be refered as "ShelterAnimals.csv", and it will contain information regarding size of the animals, number of references, sex, aprox age, and race. 
To get all this data. I will be using the website from Ayuntamiento de Barcelona, where there's public information of all animals that are currently on adoption. 

## Index
* [General information and content of the repository](#General-information-and-content-of-the-repository)
* [Tecnology used to develop the project](#Tecnology-used-to-develop-the-project)
* [Setup](#setup)
* [Characteristics](#Characteristics)
* [Current Status](#Current-Status)
* [Inspiration and resources](#Inspiration-and-resources)
* [Contact and acknowledgments](#Contact-and-acknowledgment)

## General information and content of the repository 

Webscraping project to get a csv file with registrations of all pets on adoption in Centre d'Acollida d'Animals de Companyia de Barcelona.
On this repository you will find:

* Scraper code in python  jupyter notebook, Animals_In_Shelter_Web_Scraper.ipynb, this file has coments regarding the process and use.
* Hoja de Respuestas, information about the project, context, and description of the data (This file was tought as the final presentation for the fisrt iteration within a subject on a master degree )
* Data from first iteration run (currently only available by zenodo DOI)
* Zenodo DOI Badge, doi from zenodo for the first data collection under licence CC BY-NC-SA 4.0.

## Tecnology used to develop the project

* Python 3
* Selenium webdriver

## Setup

* Python 3 installed 
* libraries used for the project will be included on Animals_In_Shelter_Web_Scraper.ipynb 

## Characteristics

* The code is currently available as notebook markdown with explanations and in raw format without coments.
* Description of the scrapped websites setup and requirements will be detailed on the notebook.
* To get more information about the project please refer to the wiki

## Current Status

* First iteration done, data from first iteration on 16.10.2020 can be consulted on https://doi.org/10.5281/zenodo.4263443 (DOI: 10.5281/zenodo.4263443)
* Second iteration done, available raw code with minimum explanation
* Third iteration in progress. 

## Inspiration and resources

* https://github.com/rafoelhonrado/foodPriceScraper
* https://github.com/tteguayco/Web-scraping
* Richard Lawson. Web Scraping with Python. Packt Publishing Ltd, 2015. 174 p. ISBN 9781782164371
* https://www.youtube.com/watch?v=Xjv1sY630Uc
* Revisión de información oficial en selenium https://www.selenium.dev/documentation/en/  y https://selenium-python.readthedocs.io/

## Contact and acknowledgments

Aknowledgement to CAACB and all their volunteers and workers. 

This project has been created by Mila Ramírez Guevara, estudent ot the master degree on DataScience in University (UOC). 
You can also find me here [@MilaRG](https://www.linkedin.com/in/mila-ram%C3%ADrez-guevara-78636585/)
Thanks for taking the time to view my project 
