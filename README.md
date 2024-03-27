# Open-Clip
The notebook has created text and image embeddings of 50,000 Amazon products.
These embeddings are then stored in a vector database named Chroma db.
I have embedded the vectors using the torch module and open clip embedding functions outside of the vector database and then the embeddings are passed and stored in chroma. I found this method more efficient and time-saving.
Semantic Search is done to retrieve a product using text and image query.
