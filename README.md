# Knowledge-Graph-for-Walmart-ADLP-Team
It uses the ```pykeen library``` for knowledge graph embedding

The datasets were provided from the ADLP team.

Converted the data into RDF format. Around 257230 triples were formed depending on the products information.

A graph of N*N connnectivity was formed.

Used ```Word2Vec``` as well as ```BERT EMBEDDINGS``` to improve the learning of the embeddings.

The Model predicts the product number from the product description as well as closely related products with given description.
 
 It can also group the data based on nutritional information as well as ingrediants description.
 
 Due to introduction of the embeddings the model is a scalable model.
