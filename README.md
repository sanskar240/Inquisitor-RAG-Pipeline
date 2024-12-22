# Inquisitor-RAG-Pipeline

Was a little out of touch with Inquisitor,an effective prompt generation model I am working on so decided to build a simple RAG pipeline to brush up,used all the relevant project docs as external knowlege base to generate answers to my queries.

Didnt bother storing and retreiving embeddings from a vector db(sort of not needed) so the retrieval is done directly in memory, comparing the embeddings of the query with the embeddings of the documents.
