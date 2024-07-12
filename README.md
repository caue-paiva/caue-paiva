### Hello! My name is Cauê and I am a computer science student at USP.

-  🔭 Currently, my main interest is developing Data related projects, such as **ETL (Extract, Transform and Load) Pipelines on the cloud**, **WebScrapping with Python** and **Data Warehouses** for Analytics.
-  🌱 I am learning how to use various technologies, a few examples are: Python, Pandas, Airflow, AWS, SQL, Postgres, Selenium, Langchain
-  📫 You can reach me at the email cauepaivalira@outlook.com.

[![Caue's GitHub stats](https://github-readme-stats.vercel.app/api?username=caue-paiva)](https://github.com/caue-paiva/github-readme-stats)

<div>
<h1> My projects </h1>

<h2> Projects i develop as part of a São Paulo State Research Foundation (FAPESP) R&D grant program </h2>
<h3>  <a href="https://github.com/caue-paiva/intelli.gente_data_extraction">Data Warehouse and automatic ETL pipeline for extracting and analyzing public brazilian goverment data </a> </h3>

This project aims to develop a **Data Warehouse (DW) that consolidates multiple public government data points** over several years, focusing on socio-economic indicators. The DW will support **analytical queries and time-series analysis**, providing decision-makers with deeper insights into areas such as Economic Activity, Environmental Policies and Damage, and Public Health. Additionally, the project features an E**TL pipeline to automate the collection, transformation, and loading of data** from public sources into the DW.

<h2> Projects i develop as part of a brazilian goverment R&D grant program (PIBIT CNPq) </h2>
<h3>  <a href="https://github.com/caue-paiva/educa_gpt_publico">Educational Chatbot for Brazilian high school students</a> </h3>

The project builds upon the **educational capabilities of Large Language Models** (ex: GPT-3.5 and GPT-4) for education ,while also **mitigating weaknesses such as hallucination and lack of knowledge about certain subjects** and tests within the **brazilian university admittance standardized test (ENEM).**

To achieve these results an LLM application, using **openAI models** (gpt-3.5 turbo or gpt-4), along with **aditional modules, such as internet search and retrieval augmented generarion for extra functionality**, was developed.

### According to [feedback](https://docs.google.com/spreadsheets/d/1UaDeCpGzO5sNSsrges_OVAHg9-5cmw7FES6-4ZroLtc/edit?usp=sharing), **over 60% of users said our solution has better and more accurate answers than chatGPT**

<h3>  <a href="https://github.com/caue-paiva/educa_custom_GPT">CustomGPTs using APIs hosted on AWS </a> </h3>
Implementation of the Educational Chatbot described above but using the new OpenAI customGPTs service.

<br> 



**Helpful Prompts and data extracted from official sources** about the ENEM test was used for better results. 


For the purpose of **RAG over ENEM test questions** a GPT action and its associated API was used, the **API is hosted on AWS API gateway** and uses a **Lambda Function** for taking user inputs, embedding them with openAI embeddings and then querying 
Qdrant vectorDB for the N questions more similar to user input, with N being the number of questions the user asked.


 <h3> <a href="https://github.com/caue-paiva/PDF_to_vectorDB_ETL">ETL pipeline for processing PDFs and feeding data into vectorDBs </a>    </h3> 

For the **educational chatbots**, both the website and the customGPT version, i needed a **large dataset of ENEM questions and their correct answers** for the purpose of RAG and **reduce LLM hallucinations** (such as giving the wrong answer to a question) but no such large scale data was available online.

In such context i created this project, which combines **PDF/data mining** through libraries like PyMuPDF2 to transform the ENEM pdf into either textual data or into JSON files **(Extraction and Transform part)** and then a **Qdrant VectorDB loader** to load the data into the vectorstore **(Load part)**. That combination is able to process either single tests PDFs (and their associated answer PDFs) or entire folders with multiple tests, loading hundreds of questions at once, all while providing **metadata and stats about the extraction process (number of extracted questions per year and subject) to a CSV file, through a Pandas DataFrame.**
<br>
<br>
<h2> Projects i developed to learn new technologies and concepts! </h2>

<h3>  <a href="https://github.com/caue-paiva/airflow_project"> Crypto Data ETL pipeline with Airflow and AWS </a> </h3>

This project aims to **collect and update data on cryptocurrencies like Bitcoin and Ethereum**, storing the information in **CSV files**. These files cover extensive periods of trading data collected from the **Binance US API**.

The main technologies used are **AWS Cloud (Lambda, API gateway, EC2 and S3)**, **Apache Airflow** for Data pipeline orchestration, **Python and Pandas** for manipulating the data

Heres the architecture of the Project/Pipeline:

<img align="center" alt="Caue-airflow" src="https://github.com/caue-paiva/airflow_project/blob/master/architecture.png">
<br>
<br>
<h2> Projects i developed as part of the Universidade of São Paulo Cientific Initiation Symposium (SIICUSP 2023) </h2>

<h3>  <a href="https://github.com/EnzoTM/R2_D2">Robot with Computer Vision and Speech Recognition </a> </h3>

Project developed in group for an eletronics class in university

The goal of this effort was the **integrate Machine Learning Models , such as Computer vision and text classification,** with a robot powered by a **microcontroller (ESP-32)**

My main contribution was with **software development for the ESP-32 embedded systems, using C++ and modules such as Wi-Fi HTTP request handlers**.

Heres the [certificate](https://drive.google.com/file/d/1yw5TbL3bTsvKT0r6YJKZV02f3wh_FrvR/view?usp=drive_link) for the Symposium
 
</div>

<div style="display: inline_block"><br>
  <h1>Technologies i am familiar with: <h1>
  <img align="center" alt="Caue-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Caue-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Caue-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="Caue-GPT" height="30" width="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/ChatGPT_logo.svg/1024px-ChatGPT_logo.svg.png">
  <img align="center" alt="Caue-qdrant" height="30" width="40" src="https://avatars.githubusercontent.com/u/73504361?s=200&v=4">
   <img align="center" alt="Caue-AWS" height="50" width="60" src="https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png">
     

</div>

<div>
  <h1> My social networks: <h2>
  <a href="https://www.linkedin.com/in/caue-paiva-lira-57b44b227/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
<div>
