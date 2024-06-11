We are developing a system that can communicate with a MySQL database. Questions submitted by users in natural language are translated into SQL queries by the system, which are then run on a MySQL database to provide answers.


Questions will be asked such as,
- Show the list the products that have not been ordered yet
- Find the total number of orders placed by each customer



## Project Highlights
Data Storage: Classicmodels MySQL database
url: https://www.mysqltutorial.org/getting-started-with-mysql/mysql-sample-database/

Components:
- Google PaLM LLM
- Hugging Face embeddings
- LangChain framework
- ChromaDB as a vector store
- Few-shot learning


## Installation

1.Clone the repository to your local machine.

2.Install the required dependencies.

3.Acquire an api key through makersuite.google.com and use it in the api key settings.

4.For database setup, load database --> mysqlsampledatabase.sql in your MySQL workbench.

6.Run the code in the jupyter notebook or google colab and generate output.
