                                         Question Answering

Problem Statement -

Develop Question Answering System which focus on automatically answer question just like human in Natural language

Description Overview -

It’s a computer science discipline which in the fields of information retrieval and natural language processing(NLP), which generally focuses on building that systems automatically answer questions just like a human in a natural language. Come on the topic of computer understanding of our natural language which consist of the capability of the program system to translate sentences into internal representation so that the system generates some valid answers to a question asked by the user. Valid answer in the sense answers relevant to the questions asked by the user.

There are two modern paradigms of question answering:
1. IR-based Factoid – It’s goal is to answer a user’s question by just finding the short text segments on the Web or some other collection of documents. During question-processing phase there are number of pieces of information are extracted from the question. The answer type specifies some kind of entity the answer which consist of(location, person, time,etc.)

2. Knowledge-based – The idea for answering a natural language question is by mapping it to the query over a structured database. Systems for mapping from the text string to any logical form are known as semantic parsers. Semantic parsers will do like map either to some version of base calculus or the query language like SPARSQL or SQL

Technology Used -

Here we will be using  Python 3.6 , Keras 2.3.1 using TensorFlow 1.14.0

Installation -

Installation of this project is quite simple. Please do follow the following steps to create a virtual environment and then install the necessary packages in the following environment.

In Pycharm it’s easy

1. Create a new project.
 
2. Navigate to the directory of the project

3. Select the option to create a new new virtual environment using conda with python3.6

4. Finally create the project using used resources.
5. 
6. After the project has been created, install the necessary packages from requirements.txt file  using the command

pip install -r requirements.txt

In Conda also it’s easy

1. Create a new virtual environment using the command
    conda create -n your_env_name python=3.6
    
2. Navigate to the project directory.

3. Install the necessary packages from requirements.txt file using the command
         
pip install -r requirements.txt

Workflow Diagram -

![image](https://user-images.githubusercontent.com/61505882/172448615-6663436e-e04c-48c1-8df0-34890631f0fa.png)

Implementation -

1. Project Directory

![image](https://user-images.githubusercontent.com/61505882/172448882-ab2dd318-c164-44f1-99c8-7c9462214da2.png)

The above picture represents the project directory. If we open the project folder using PyCharm  different types of files are there like for clientApp,  utils, qa_predict etc where some are used for storing data into this folder.

2. clientApp.py

![image](https://user-images.githubusercontent.com/61505882/172449409-51b6ea2c-47e1-4b68-818a-6faa8812185d.png)

3. requirements.txt

![image](https://user-images.githubusercontent.com/61505882/172449815-30e9045c-e0ed-4eff-b2fd-7e60e1dc49d2.png)

4.qa_predict.py

![image](https://user-images.githubusercontent.com/61505882/172449930-1b85f67b-0a6b-4a17-a09e-44c961dc98f4.png)

In this file we would arrange functions to get the proper result by applying clientApp.py

Testing in Local/API -

To run this project in your local system just run the file clientApp.py and after that web server will start at localhost 5001 port

![image](https://user-images.githubusercontent.com/61505882/172450173-ee0a7f43-3186-4bf0-83aa-e6b15255bb8a.png)

Enter the question and keep no of paragraphs = 2 for now, Click on Predict button.

![image](https://user-images.githubusercontent.com/61505882/172450243-adef9ad2-1dce-4a8a-bf0c-db02619923a5.png)

 After clicking Predict 
 
 ![image](https://user-images.githubusercontent.com/61505882/172450435-27c7f053-81ff-4e42-94d0-fb9537dd401a.png)

![image](https://user-images.githubusercontent.com/61505882/172450859-008fe7d4-6b48-4ef2-ad20-01c2fa183b9a.png)

 
 Conclusion -
 
  Here we successfully built a Question answering model which we can use it to answer based on our data available.

 Improvements -
 
 We can create the same Question Answer model with various other pre trained models available from Hugging Face transformers.


