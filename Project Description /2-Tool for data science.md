# Data Science Tools 

* [Open Source Tools for Data Science](#opensource)
  * [Data Intergration and Transformation](#integration)
  * [Code Asset Management](#codeasset)
  * [Development Environments](#environment)
* [Commercial Tools for Data Science](#commercial)
* [Cloud Based Tools for Data Science](#cloud)
* [Packages, APIs, Data Set and Models](#api)
  * [Libraries for Data Science](#libraries)
* [Data Set](#datasets)
  * [Open data sources](#opensources)
* [Machine Learning Models](#models)
* [Git & GitHub](#git)

## Categories of Data Science Tools <a name="categories"></a>
![](https://github.com/wtbrissy/IBM-Data-Science-Coursera/blob/draft/Project%20Description%20/image%20/Categories%20of%20Data%20Science%20Tools%20.png)

## Open Source Tools for Data Science <a name= "opensource"></a>

### Data Management 
- Relational databases: MySQL , and PosstgreSQL
- NoSQL databases: MongoDB, Apache CouchDB, and Apache Cassandra 
- File-based: Hadoop File System, Ceph
- Text-data and creating a search index: Elasticsearch 

### Data Integration and Transformation <a name="integration"></a>
*ELT - Extra, Load and Transformed* or *data refinery and cleansing*
- Apache AirFlow: AibBNB
- Kubeflow: Execute data science pipelines on top of Kubernetes  
- Apache Kafka: Linkedin 
- Apache Nifi: Visual editor 
- Apache SparkSQL : ANSI SQL 
- NodeRED : Visual editor 
- HUE: create visualisation from SQL queries  
- Kibana: dta exploration and visualisation web application (*limited to Elasticsearch*)
- Apache Superset: data exploration and visualisation web application 

### Model Deployment 
- Apache PredictionIO: only support Apache Spark ML models for deployment  
- Seldon: support every framework, TensorFlow, Apache Spark ML, R, and scikit-learn 
- Melap: TensorFlow service, TensorFlow Lite, and TensorFLow.JS

### Model Monitoring and Assessment 
- ModelBD: a system to manage ML models 
- Prometheus
- IBM AI Faimess 360 Open Scource Toolkit 
- IBM Adversarial Robustness 360 Toolbox 
- IBM Ai Explainability 360

### Code Asset Management <a name="codeasset"></a>
- Git 
- Github 
- GitLab 
- Bitbucket 
- Apache Atals 
- Egeria  
- Kylo 

### Development Environments <a name="environment"></a>
- Jupyter notebooks
- Jupyter lab 
- Apache Zeppeline 
- RStudio 
- Spyder 
- Apache Spark: linear scalability - huge data 
- Apache Flink: stream processing - realtime stream 
- riselabRay: large scale deep-learning model training 

### Fully Integrated Visual Tools 
- KNIME
- Orange 

## Commercial Tools for Data Science <a name="commercial"></a>

### Data Management 
- Oracle Database 
- Microsoft SQL Server
- IBM DB2 

### Data Integration and Transformation 
- Infomatica 
- IBM InfoSphere DataStage 
- Talend 
- Watson Studio Desktop 

### Data Visualisation 
- PowerBI 
- Tableau 
- IBM Cognos Analytics 
- IBM Watson Studio Desktop 

### Model Building 
- SPSS Modeler 
- SAS Enterprise Miner 

### Data Asset Management 
- Informatica 
- IBM InfoSphere Information Governance Catalog 

### Fully Integrated Visual Tool 
- Watson Studio 
- H2O.ai 

## Cloud Based Tools for Data Science <a name="cloud"></a>

### Fully Integrated Visual Tool 
- Watson Studio 
- Azure Machine Learning
- H2O.ai 

### Data Management 
- Amazon DynamoDB
- Cloudant 
- Apache CouchDB
- IBM Db2 

### Data Integration and Transformation 
- Informatica 
- IBM Data Refinery 
- Datameer 
- IBM Cognos Analytics 
- … 

### Model Building 
- IBM Watson Machine Learning 
- Google Cloud AI Platform Training   

## Packages, APIs, Data Sets and Models <a name="apis"></a>

### Libraries for Data Science <a name="libraries"></a>
#### Python 
- Scientifics computing 
- Pandas - Data structures & tools 
- Numpy - Arrays & matrices 
- Visualisation 
- Matplotlib - plots & graphs, most popular
- Seaborn - plots: heat maps, time series, violin plots 
- Machine learning and deep learning 
- Scikit-learn: ml regression, classification…
- Kears: deep learning neural networks…
- TensorFlow: deep learning production and deployment 
- PyTorch: deep learning regression, classification 
#### Apache Spark 
- Scala-libraries 
- Vegas: data visualisation 
- Big DL: deep learning 
- R-Libraries 
- Ggplot2: visualisation 
- Keras 
- TensorFlow 

### Application Programming Interfaces (API) <a name="api"></a>
- What is an API 
- An API lets two pieces of software talk to each other 
- API Libraries : API can be multiple different languages, e.g. python, JS, C++. Java, GO, Julia, Matlab, and R, etc. 
  
![](https://github.com/wtbrissy/IBM-Data-Science-Coursera/blob/draft/Project%20Description%20/image%20/APIs.png)

*image: API* 
- REST APIs: they enable you to communicate using the internet, taking advantage of storage, greater data access, artificial intelligence algorithms, and many other resources. 
- RE: Representational 
- S: State
- T: Transfer 
- 
![](https://github.com/wtbrissy/IBM-Data-Science-Coursera/blob/draft/Project%20Description%20/image%20/REST%20APIs.png)

*image: REST APIs* 

## Data Sets <a name="datasets"></a>

- Collection data 
- Data structures 
- Tabular data 
- Hierarchical data
- Network data 
- Raw files 
  
### Data ownership 
#### Private data 
- Confidential 
- Private or personal information 
- Commercially sensitive 
  
#### Open data 
- Scientific institutions
- Governments
- Organizations
- Companies
- Publicly available 
  
#### Open data sources <a name="opensources"></a>
- [Open data portal lists](http://datacatalogs.org)
- Governmental, intergovernmental, and organisation websites:
- [United Nations](http://data.un.org)
- [USA](https://www.data.gov)
- [Europe](https://www.europeandataprotal.eu/en)
- [Kaggle](https://www.kaggle.com/datasets)
- [Google data set search](https://datasetsearch.research.google.com) 
  
#### Community Data License Agreement 
- [A Linux Foundation Project](http://cdla.io)
- CDLA-Sharing: Permission to use and modify data; publication only under same terms 
- CDLA-Permissive: Permission to use and modify data; no obligations 

## Machine Learning Models <a name="models"></a>

- Data can contain a wealth of information 
- Machine Learning models identify patterns in data 
- A model must be trained on data before it can be used to make predictions 

### Supervised Learning 
- data is labeled and model trained to make correct predictions 
- Regression 
	- Predict real numerical values 
- Classification 
	- Classify things into categories 

### Unsupervised Learning 
- data is not labeled 
- Model tries to identify patterns without external help 
- Common learning problems: clustering and anomaly detection 

### Reinforcement Learning 
- Conceptually similar to human learning process 

## Deep Learning 
- Tries to loosely emulate how the human brain works 
- Applications: 
	- Natural language Processing 
	- Image, audio, and video analysis 
	- Time sergers forecasting 
- requires typically very large datasets of labeled data and is compute intensive 

# Git/Github <a name="git"></a>

## Version Control 
 **Git** 
- Free and open source software 
- Distributed version control system 
- Accessible anywhere in the world 
- One of the most common version control systems
- Version control images, documents, etc 
**GitHub** 
**GitLab**
**Bitbucket** 
**Beanstalk** 

## SHORT Glossary of Terms 
- SSH protocol : A method for secure remote login form one computer to another 
- Repository: The folders of your project that are set up for version control 
- Fork : A copy of a repository 
- Pull request: The process you use the request that someone reviews and approves your changes before they become final 
- Working directory: A directory on your file system, including its files and subdirectories, that is associated with a git repository. 

## Basic Git Commands 
- init: push to GitHub, or cloning an exisiting repository 
- add: moves changes form the working directory to the staging area 
- status: see the state of working directories, and the staged of snapshot  of the changes 
- commit : commits the changes to the project 
- reset : undoes changes 
- log: browse previous changes 
- branch: created an isolated environment 
- checkout : see and changing existing branches 
- merge: put everything back together 

## Learning Git & GitHub
- [GitHub - IBM/skillsnetwork](https://github.com/IBM/skillsnetwork)
- Learning by reading - [Git Handbook · GitHub Guides](https://guides.github.com/introduction/git-handbook/)
- Cheat Sheets - [Git Cheat Sheets - GitHub Cheatsheets](https://training.github.com)
- Learning Git branching - [Learn Git Branching](https://learngitbranching.js.org)
- Visulizaing Git - [Visualizing Git](http://git-school.github.io/visualizing-git/)
