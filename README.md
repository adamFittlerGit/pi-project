# pi-project
Codebase for my raspberry pi project.  I am going to build an deploy an application to my pi and manually setup the CI/CD pipelines etc to get a better understanding of how things work on a lower level. 

The three services we will be using are:
1. NextJS web app that handles the frontend and acts as our api as well which is nice
2. Postgress Database or NoSQL Database to store conversations and messages 
3. Inference Service for the llm inference, use c++ websockets to stream inference quickly to the web-app

Goal is to be a local llm server for people on my wifi to be able to use.  
