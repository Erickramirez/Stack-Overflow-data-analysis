# Exploring Stackoverflow Anual Developer Survey 2020
This is a data analysis on [Stackoverflow Anual Developer Survey](https://insights.stackoverflow.com/survey) The whole project is implemented following "Cross-Industry Standard Process for Data Mining (CRISP-DM)" process, including the following steps:
1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Model Data
5. Results
6. Deploy
   
 
 ### Prerequisites
The environment needed for this project:
1. [Python 3.6](https://www.python.org/downloads/release/python-360/)
2. [numpy](https://numpy.org/)
3. [pandas](https://pandas.pydata.org/)

### Explanation of the files in the repository
1. data analysis.ipynb : jupyter notebook that contains the code and detailed data analysis
2. data
    - latin_america.csv: list of countries that are part of Latin America and the Caribbean
    - developer_survey_2020.zip: developer survey data, it can be also dowloaded [here](https://drive.google.com/file/d/1dfGerWeWkcyQ9GX9x20rdSGj7WtEpzBB/view). 

### Instructions to run the project
1. clone the github repository: `git clone https://github.com/Erickramirez/Stack-Overflow-data-analysis.git`
2. verify the Prerequisites
3. extract developer survey data into the path (if it doesn't exist, please create it) `/data/2020`
4. Run the jupyter notebook: `data analysis.ipynb`

### Project motivation
I'm from Guatemala and I'm interested in how the latin american developers works. I would like to answear the following questions:

1. How are developers' demographics in Latin America and the Caribbean (LAC): average age, country, level of education?
2. Does it change the status of satisfaction related to the professional experience in Latin America and the Caribbean (LAC)?
3. What is the salary behavior according to years of experience, country and Developer type?
4. What skills are more valuable for the developers (love the language), and what skills generate more earning?

The results of this questions are in this [Medium Post](https://erick-ramirez.medium.com/2020-status-of-people-who-code-around-latin-america-and-the-caribbean-a84004278bf1)

