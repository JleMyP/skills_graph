# skills-graph 
https://avk0.github.io/skills_graph/

A graphical representation of relations between programming languages, technologies and skills in demand, based on thousands of job postings.

### Sample
~500 vacancies parced by keyword "Machine Learning" (headhunter.ru)

![Peek 2020-04-24 00-13](https://user-images.githubusercontent.com/47819971/80150148-846a5e80-85c0-11ea-82cc-cff6aef4900c.gif)

We can see, that essential skills for machine learning jobs are Python, SQL, Linux and others

### Structure
  Backend: tags scraper and parser\
  Frontend: dynamic graph visualization 
  
### How to use
* Use scraper in `./scraper` folder to get more data.
* Use `preprocess.py` to format and filter tags data.

Visualization is based on JavaScript and few [Observable notebooks.](https://observablehq.com/@avk0?tab=notebooks)\
Some additional Python visualization can be done using Ipython Notebook: `./scrapers/hh-ru_scraper.ipynb` 

Any ideas are highly appreciated!
### TODO

##### Frontend:
* fasten visualization
* add filtering by size

##### Data sources
* Used:
  * hh.ru
* To try:
  * Linkedin
  * Stackoverflow jobs
  * Who is hiring hackernews
  * Indeed
  * Glassdoor

### Contributors
[Andrei Koval](https://github.com/avk0)\
[Serghei Mihailov](https://github.com/SergheiMihailov)