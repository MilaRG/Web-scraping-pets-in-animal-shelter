# Web scraping pets in animal shelter

**Nota:El archivo Readme solo será actualizado cuando se hagan cambios o actualizaciones mayores. Si quieres información sobre el estado del proyecto y roadmap por favor dirigete a la wiki**

## Contexto y descripción del proyecto
Este proyecto empieza como la primera práctica de la asignatura Tipología y ciclo de vida de los datos dentro del máster universitario en Ciencia de Datos de la  UOC(Universitat Oberta de Catalunya). 
Mi objetivo con esta práctica es a través de herramientas de Web scraping con Python obtener un dataset en formato CSV de los animales de compañia en adopción que hay en el CAACB (Centre d'Acollida d'Animals de Companyia de Barcelona), a partir de ahora me referiré al dataset como "ShelterAnimals.csv", en este dataset hay información del nombre tipo de animal tamaño y la referencia. 
Para obtener esta información utilizaré la web del Ayuntamiento de Barcelona, en ella hay disponible una ficha para cada uno de los animales que se encuentran actualmente en el refugio pendientes de una Adopción.

## Índice
* [Información General y contenido del repositorio](#Información-General-y-contenido-del-repositorio)
* [Tecnologías](#Tecnologías)
* [Setup](#setup)
* [Características](#Características)
* [Estado del proyecto](#Estado-del-proyecto)
* [Inspiración y recursos](#Inspiración-y-recursos)
* [Contacto y agradecimientos](#Contacto-y-agradecimientos)

## Información General y contenido del repositorio 

Proyecto de Webscraping para obtener datos de los animales que se encuentran en adopción en el Centre d'Acollida d'Animals de Companyia de Barcelona. 
En este repositorio encontrarás: 

* Código del scraper en python jupyther notebook, Animals_In_Shelter_Web_Scraper.ipynb, contiene comentarios y apuntes sobre el uso. También disponible en formato Raw con comentarios mínimos.
* Hoja de Respuestas, archivo con información sobre el proyecto, contexto y descripción de los datos (el archivo está enmarcado dentro de la presentación de la práctica de una asignatura de master universitario).
* Datos obtenidos a través del scraper en formato csv pets_in_shelter.csv, publicado bajo licencia CC BY-NC-SA 4.0 License (Tras la segunda iteración ya no está disponible y solo es accesible mediante Zenodo DOI)
* Zenodo DOI Badge, doi en zenodo de los datos extraídos.

## Tecnologías 

* Python 3
* Selenium webdriver

## Setup

* Necesario tener Python 3 instalado 
* Consultar archivo Animals_In_Shelter_Web_Scraper.ipynb donde se incluyen las librerias necesarias 

## Características

* El código esta en formato notebook markdown con comentarios explicativos y en formato raw sin comentarios detallados 
* La descripción del sitio web objetivo, setup y requisitos se detallan en el archivo de código Markdown
* Para más información sobre las actualizaciones y el uso del repositorio consultar la Wiki

## Estado del proyecto

* Primera iteración finalizada, los datos regogidoa a fecha 16.10.2020 se pueden consultar en https://doi.org/10.5281/zenodo.4263443 (DOI: 10.5281/zenodo.4263443)
* Segunda iteración finalizada, Se añade código en formato crudo con comentarios mínimos.
* Tercera iteración en progreso. Para ver detalles sobre la misma consultar Wiki

## Inspiración y recursos

* https://github.com/rafoelhonrado/foodPriceScraper
* https://github.com/tteguayco/Web-scraping
* Richard Lawson. Web Scraping with Python. Packt Publishing Ltd, 2015. 174 p. ISBN 9781782164371
* https://www.youtube.com/watch?v=Xjv1sY630Uc
* Revisión de información oficial en selenium https://www.selenium.dev/documentation/en/  y https://selenium-python.readthedocs.io/

## Contacto y agradecimientos

Agradecimiento a los propietarios de los datos CAACB y a todos los que colaboran y forman parte de la organización. 

Este proyecto ha sido creado por Milagros Ramírez Guevara, estudiante del master de ciencia de datos en la UOC. También puedes encontrarme aquí [@MilaRG](https://www.linkedin.com/in/mila-ram%C3%ADrez-guevara-78636585/)

