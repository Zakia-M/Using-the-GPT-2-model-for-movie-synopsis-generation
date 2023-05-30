### Using the GPT-2 model for movie synopsis generation -Description- 

One of the branches of artificial intelligence that has received the most attention recently is Natural Language Processing (NLP). Concretely, it is its application to the automatic generation of text that has been the subject of a large number of projects, in particular summarizing texts, automatic translation, answering questions and completing texts.
The objective of this project is to exploit the potential of one of the most powerful tools in this field: the OpenAI GPT-2 model, to build a system for generating film synopses based on two large datasets known worldwide, available on both platforms: IMDB and Wikipedia :
<br/> ----- Wikipedia Movie Plots (~35,000 movies descriptions): https://www.kaggle.com/jrobischon/wikipedia-movie-plots 
<br/> ----- The Movies Dataset (Metadata on over 45,000 movies from MovieLens): https://www.kaggle.com/rounakbanik/the-movies-dataset/data, ((where the cleaned dataset for movieLens dataset is on this link : https://drive.google.com/drive/folders/1ZGp7ORu9nA6l3PyNK_H0MGTXNl4sNMsA ))<br/>

used to fine-tune the two GPT2 models from OpenAI : the 355M model & the 124M model, by using the gpt-2-simple library (https://github.com/minimaxir/gpt-2-simple).

The motivation behind this project is the involvement of AI in the making of films by generating and offering producers synopses that can be interpreted and turned into films.



## Instructions :
1- Clone the repository
<br /> 2- Download the cleaned movielens movies dataset from this link : https://drive.google.com/drive/folders/1ZGp7ORu9nA6l3PyNK_H0MGTXNl4sNMsA , rename it to "movies.csv" and put it on the same folder with IPYNB files.
<br /> 3- Download the wikipedia movies dataset from this link : https://www.kaggle.com/jrobischon/wikipedia-movie-plots , rename it to "wiki_movie_plots_deduped.csv" and put it on the same folder with IPYNB files.
<br /> 4- run the "clean_datasets_wiki_&_MovieLens.ipynb" file , to get the final file with which you finetune the GPT2 model.
<br /> 5- run "gpt2_355.ipynb" & "gpt2_124.ipynb" files to finetune the 355M and the 124M GPT2 models respectively 
