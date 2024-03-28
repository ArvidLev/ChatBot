# ChatBot with Agents

For this project I created a chatbot that would answer question from a machine learning textbook. It is built upon Chat-GPT but also has agents that detect greetings, obnoxious prompts, and relevant prompts. For determining relevant prompts, I embedded the textbook twice with different chunk sizes, one small and one large. The ideas was by using cosine similarity between prompt and the smaller chunk size text I have a more precise way of determining relevance. After I can use the larger chunk size to extract relevant information from the textbook and let GPT use only that to provide an answer.

I use pinecone, langchain, streamlit, and openai. This current code won't run since I have removed the keys to the APIs for obvious reasons. However, I have included screenshots of it handling different kinds of requests in the notebook.
