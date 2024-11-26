# encode-homework-week-4
Llamaindex Upload, Build Index, Extract Characters, Write a story

Notes

llamaIndex is a front end platform that can be used for RAG (Retrieval Augmented Generation). THis is a process where a model does not used specifically its own training to answer prompts, it can draw relevant information from uploaded documents, and use them specifically, or to augment its own training data, to answer user prompts.

To avoid extraneous metadata dirtying the data batches, only txt docs are allowed
THe uploaded document can be queried for information. THere are parameters that can be adjusted, such as "batch size" to improve the accuracy, or get speedier replies.
On querying the doc, other parameters can be adjusted, such as "temperature". With RAG, having a low temperature means a stricter need for facts. Often with GenAI content creation, a higher temperature grants the model a more creative license.

LlamaIndex runs locally, on localhost3000, and i used an Openai API key with it
For this project, I -

Generated a story sample, and uploaded it to LlamaIndex.
After it built the index, i queried it to extract the four main characters, and present them as a table, with the values - name, description, personality

I then modified the index file to change the page, with the help of GenAI, and a code assistant. 

The batch size default was set to 3000 (max) for speedy, low computation results, and all the default settings used, so there was no need for all the text boxes, buttons and sliders on the page
Removed parameter buttons and sliders
Once the index is built, extract characters and write story buttons appear.

If write story is clicked first, the code will write a story about from the txt doc.
If extract characters is clicked, the four main characters will be presented in the table
If write story is then clicked, a story is created about one of the main characters

<img width="954" alt="week 4 lesson 16 llamaindex uploadtxt index extract write" src="https://github.com/user-attachments/assets/d16859cb-2f07-44fa-8bde-f015d600feac">


