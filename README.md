# cold_email_generator_using_Llama_3.1

### Tech stack used:
1. Llama - 3.1 gen ai model
2. Langchain => orchestation framework
3. Chroma db => for vector stores
4. Streamlit => UI
5. Python => Programming Language
6. Groq => cloud for faster inference for Llama models

# Problem Statement:

There are software companies like Accenture, TCS, Infosys, IBM, HCL etc....
These companies help clients like Nike, BOFA, JP Morgan etc, there are lot of businesses through out the globe who wants to build the software. The software compnies has software engineers and they provide services to Clients.

There is a lot of competetion in the market and many times salaes teams from this companies they use variety of marketing techniques to build to acquire projects. One of the technique is cold email.

SO a person from software services suck as Accenture will send a cold email to potential client.

Now how do they know, these clients have a specific requirements.
1. One of the technique is they will go to their job portal and their they will find out for ex: they need a software engineer AI/ML developer. They will look at all the skill set and etc

2. Now what Accenture will do is, it will send a cold email like hey you looks like a AI/ML engineeer. we have these people instead of hiring full time, may be you can hire people from us.

3. mostly these clients are operates from US, UK and other countries. They will look for a people India, indonesisa where people work for low cost.

4. instead of hiring full time employees you can hire contract base, so there are several benefits of using this models.

5. Accenture will send this kind of cold email to Nike, jp morgan, bofa etc

6. Many times this cold email technique works.

7. Now sales representative at Accenture will have to form a nice email which is relavant to job posts

8. One of the things we can use that is, LLM's

9. Using LLM's, we can generate a cold email

10. For ex: let say if i build a project where you can give a job posting url or company job portal. it will go to that job portal and it wil figure out what kind of skills are needed based on that which will write an email which is relavant to the job post

11. for example instead of going and checking manually, if it's identifies this client is looking for AI?ML and devops knowledge

12. This email exactly talk about the skills you will have this kind of portfolio

13.Portfolio nothing but,....the past projects you have done previously(Accenture previous projects)

![architecture](https://github.com/user-attachments/assets/35151284-23fc-48ab-b3e6-e98fa034008b)

Llama 3.1 is a super amazing open source LLM that uses for free. 

In this proect i am not going run the llama using ollama run or locally. because it is taking lot of time for inferencing.

Lama models ==> https://www.llama.com/docs/model-cards-and-prompt-formats/llama3_1/

what i will do is....i will groq

what is Groq?

Groq is a platform which allows you to run llama 3.1 in cloud and inference is very very fast because they use something called LPU (Language processing unit) that makes the inference that means when you ask a question, the response will come very faster.

Groq official website ==> https://groq.com/

Generate a GROQ API key:
1. login with gmail
2. create api key
3. copy the api key

Let's start the Journey
in this journey we will use
chatGroq library ==> https://python.langchain.com/docs/integrations/chat/groq/
