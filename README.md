# RAG-Function-calling

OpenAI provides an inbuilt mechanism to achieve function calling. We will try to replicate the same with some local models so that you can try function calling without openAI.

![image](https://github.com/user-attachments/assets/94a98612-4108-4d27-9ea6-3fd0b8457515)   
(Image taken from Source: https://gradientflow.substack.com/)

Use case - Flight booking based on the prompt given by user.
Objective is that

the application should understand the user query, 
should retrieve Source, Destination, and time of travel from the user query in structured manner
should direct the required information to the booking function (a dummy function that is intended to do the booking).

we will try to achieve that using
 - Function Calling using langchain.agents
 - Function calling using Structured LLMs (using BaseModel from Pydantic)
