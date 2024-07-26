Data preprocessing

All data is taken from ParlaMint GB,IT, and AT. Texts are split in individual turns for model ingestion and a batch of 500 per language is uploaded.


In this frame work, We are using a Retriver based emotional analysis system.

The system is based on Italian.

Steps used :
1. The data are chunked and stored in the vector store.
2. Based on the area which need to analyses, the question can be asked.
3. The relevant content form the vector store are retrived.
4. The retrived data are shared with the Models.

5. The models tested :
6. Bert, GPT 4o
