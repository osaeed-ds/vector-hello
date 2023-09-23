# vector-hello

Sample Google Colab notebooks for the following Vector Databases
## MongoDB Atlas
I spun up an Atlas db and ran the hello world vector example.  I could not get Hugging Face workign as the embedding model so I used Sentence Transformer instead.
https://github.com/osaeed-ds/vector-hello/blob/main/Osaeed_Redis.ipynb

## Neo4j AuraDB
I spun up a cloud AuraDB on Neo4j's website.  I went through the bicycle vector example.  Had to make some minor modifications to get it to dispaly the results correctly within Colab.

## Redis
I spun up a Redis db on Redis cloud and ran the Redis example on the LangChain website with some minor modifications to change the datasource and question.

## pgVector
I spun up a postgres DB on Digital Ocean, installed the pgVector extension, and ran the pgVector example from LangChain.  It was actually the same as the Redis example, so I just cloned my Redis notebook and substituted the postgres connection info.
