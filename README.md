# Assignment-4-portfolio-exercise

In the following assignment 4, I have created a NLP pipline using LangChain and a pre-trained transformer from Hugging Face.

Firstly, a model setup was created where the pipeline is created with the pre-trained transformer.
Afterwords, a simple retrieval augmented generation (RAG) is set up. This is done with the PyPDFLoader so that it is possible to insert your own PDF. Then the embeddings are created. This is done using HuggingFaceEmbeddings. This is all contained in a database created using Chroma, where the vectors are stored. Before creating a template and prompt for the search engine, a similarity search is created using the llm system.

Lastly, the template and prompt is created for the search engine. Afterwords, a fine-tuning of the prompt is done, so to ensure the accuracy of the output of the engine.

##Further work##

Futher work with the code entails the creation of application interface.

A mockup application has been created and is available in the repository
