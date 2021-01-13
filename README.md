# Detecting students who are at risk of failing a class
 

### Project's goal

Emergence of distance education has offered many promises such as access to education regardless of where students live or when they decide to devote themselves to subject. In theory, such flexibilities should offer great advantages over traditional classrooms. In practice however, online education programs often fall short of what they attempt to accomplish due to problems related to low student retention rate. Therefore, with an intent to address this issue this project aims to achieve two goals: 

* The first one is to visually examine through charts and plots the extent to which various socio-demographic and study-related factors are related to student's performance. 

* The second goal however is to build ML models that would predict who is likely to fail the course even before the exams take place. 


The analysis of learners’ data thus might provide informed guidance to policy-makers and curriculum administrators who are interested in improving students’ learning experience and optimizing learning material according to students’ needs.


The data for the project comes from Open University of the UK and is freely available on their website under the name *Open University Learning Analytics dataset*. Open University of the UK is one of the largest online universities in the world, with 170,000 students enrolled. The dataset was created specifically for research purposes and contains socio-demographic data along with data about student's interactions in the Virtual Learning Environment (VLE). The latter allows us to use student's actions to examine their learning behavior. 



### About the dataset

Dataset for the project is provided by Open University of the UK and is freely available on their website under the name *Open University Learning Analytics dataset*. For more comprehensive information, including full data access, detailed data description and methodology for data selection, please visit Ope University's dedicated webpage: https://analyse.kmi.open.ac.uk/open_dataset.


* The dataset consists of the information about 22 courses, 32,593 students, results of their assessments, as well as logs of their interactions with the Virtual Learning Environment(VLE) represented by daily summaries of student clicks (10,655,280 entries).

* VLE is the primary platform  which students at distance learning mode use to access the course content, forum discussions, to send course assignments etc.

* Data is provided for 7 courses (called modules) across 4 different semesters (called presentations).


### Content of the project

This project consists of two parts: 

* [Part 1 (Exploratory Analysis)](Part_1_(Exploratory_Analysis).ipynb) 

* [Part 2 (Machine Learning)](Part_2_(Machine_Learning).ipynb)


### Tools used for the project

* ###### Python version:
<code>Python==3.7</code>


* ###### Libraries and dependencies:

azure-core==1.9.0 <br/>
azure-storage-blob==12.6.0 <br/>
jupyter-core==4.6.3 <br/>
jupyterlab==2.2.6 <br/>
lightgbm==2.3.1 <br/>
matplotlib==3.3.1 <br/>
numpy==1.19.1 <br/>
nvidia-ml-py3==7.352.0 <br/>
pandas==1.1.3 <br/>
pycaret==2.2.2 <br/>
scikit-learn==0.23.2 <br/>
scikit-optimize==0.8.1 <br/>
scikit-plot==0.3.7 <br/>
seaborn==0.11.0 <br/>
sklearn==0.0 <br/>
tune-sklearn==0.2.1 <br/>
xgboost==1.2.0 <br/>

