# Colleges Shiny App

Deciding where to go to college can be one of the most consequential decisions a person will make in their lifetime. Many people chose where to go to college based on rankings from news organizations, but rankings reduce the quality of a school down to one number. By itself, rankings are not helpful in deciding which school is best for YOU. Instead, prospective students should prioritize fit when deciding where to go to college.

Evaluating fit requires customization which is something conventional school rankings don't provide. This app aims to aid prospective students in identifying and comparing colleges they may want to attend based on their unique preferences.

## Data

The data used for this app comes from the following sources:

* U.S. Department of Education [College Scorecard](https://collegescorecard.ed.gov/data/)
* U.S. News & World Report National University Rankings via [Andrew G. Reiter](https://andyreiter.com/datasets/)
* U.S. Department of Education [Campus Safety and Security Data](https://ope.ed.gov/campussafety/#/)

Rankings and safety data can be found in the `data` folder. College Scorecard data must be downloaded from https://collegescorecard.ed.gov/data/. After downloading the data, open `.zip` file and rename folder to `scorecard`. Move this folder to `data` before running `clean_data.R`. A merged dataset used in the application is available in the `colleges.csv` which can be found in the `data` folder.)


