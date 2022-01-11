### Using the GPT-2 model for movie synopsis generation -Description- 


We have used movies synopsis from two large Kaggle movies datasets :
<br /> ----- Wikipedia Movie Plots (~35,000 movies descriptions): https://www.kaggle.com/jrobischon/wikipedia-movie-plots 
<br /> ----- The Movies Dataset (Metadata on over 45,000 movies from MovieLens): https://www.kaggle.com/rounakbanik/the-movies-dataset/data, ((where the cleaned dataset for movieLens dataset is on this link : https://drive.google.com/drive/folders/1ZGp7ORu9nA6l3PyNK_H0MGTXNl4sNMsA ))
to fine-tune the two GPT2 models from OpenAI : the 355M model & the 124M model, by using the gpt-2-simple library (https://github.com/minimaxir/gpt-2-simple).


## Instructions :
1- Clone the repository
<br /> 2- Download the cleaned movielens movies dataset from this link : https://drive.google.com/drive/folders/1ZGp7ORu9nA6l3PyNK_H0MGTXNl4sNMsA , rename it to "movies.csv" and put it on the same folder with IPYNB files.
<br /> 3- Download the wikipedia movies dataset from this link : https://www.kaggle.com/jrobischon/wikipedia-movie-plots , rename it to "wiki_movie_plots_deduped.csv" and put it on the same folder with IPYNB files.
<br /> 4- run the "clean_datasets_wiki_&_MovieLens.ipynb" file , to get the final with which you finetune the GPT2 model.
<br /> 5- run "gpt2_355.ipynb" & "gpt2_124.ipynb" files to finetune the 355M and the 124M GPT2 models respectively 
