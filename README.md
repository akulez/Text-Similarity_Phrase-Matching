# Text-Similarity_Phrase-Matching
This notebook focuses on applying some classical and modern Text Similarity measures to US Patent Matching Dataset and check how well classical models including Jaro Winkler, Jaccard score as well as modern day Word2Vec and USE(Universal Sentence Encoder) can detect similarity between textual data. The project was done in several steps as follows:

1. **Exploratory Data Analysis and Basic Preprocessing**
   - In this part I have focused on conducting initial analaysis of the text columns in hand with various descriptive stats.
   - Visualisations including barplots and boxplots have been used to better demonstrate the stats.
   - Along with that, basic preprocessing of dataframe including removing duplicates and renaming of cols. was done here. 

2. **Text preprocessing**
   - In this part of the notebook, the text was cleaned up and prepared for the next part.
   - Unneccessary chars., punctuations and other things which do not add any semantic meaning to the text were removed from the dataset.

3. **Applying Text similarity measures**
   - Once the data was ready, 5 algos. which included some classical and some modern day algos. were used to find the simialrity scores between the columns.
   - Classical Algos. - Some classical text similarity were applied these included Jaccard Score, Jaro Winkler Method and Levenshtein distance.
   - Modern day algorithms - including Word2Vec and pretrained Universal Sentence Encdoing were used to convert the text into embeddings and then find the cosine distance between the vectors.
