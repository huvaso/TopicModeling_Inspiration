# TOMIAS: TOpic Modeling for Inspiration AnalysiS

Authors:
- Martín Hernani-Merino
- Harumi Gonzales-Hara
- Hugo Alatrista-Salas

The following project includes sources (notebook) and datasets for mining textual data associated with inspiration customer behavior. The project includes a dataset depository ("Data") in which tweets and survey results are included. Also, some images used in the papers were located in the "Figures" directory. These images can be obtained by executing the notebook "TopicModeling_Inspiration_Shared.ipynb".

All results of our contribution can be obtained through the "TopicModeling_Inspiration_Shared.ipynb". This notebook is organized into functions:

1) read_corpus(): read the corpus and to setup the nlp technique
2) entropy_topics(): compute the best number of topics
3) training_model(): train the LDA model and extract the topics from the corpus
4) pre_visualization(): pre-process the corpus and topics before the Sankey visualization
5) sankey_visual(): creates the Sankey visualization and stores it in a file
6) tweets_analysis(): recover, pre-process tweets, and compare them with words belonging to a topic using the cosine distance
7) embeddings_skip_inspired_to(): analyze the semantic relationship between words belonging to the topic "Inspired to" and a specific word (e.g., sport or person)
8) embeddings_skip_inspired_by(): analyze the semantic relationship between words belonging to the topic "Inspired by" and a specific word (e.g., sport or person)
9) wordclouds(): visualize the wordclouds from words found with the embeddings function

Please, if you have some questions, do not hesitate to contact us (mn.hernanim@up.edu.pe, halatrista@pucp.pe).
