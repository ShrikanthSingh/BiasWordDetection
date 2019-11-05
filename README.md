# BiasWordDetection
### Objective:
Form a lexicon of 10 bias words from the extracted dataset. For each bias words determine 100 most similar words. So in total generate 1000 words.

### Dataset extracted from news websites:
- https://www.nytimes.com/section/education
- https://www.reuters.com/finance
- https://www.foxnews.com/world
- https://www.news18.com
- https://www.bbc.com/news/technology
- https://qz.com/africa/latest/
- https://www.studentnewsdaily.com/archive/daily-news-article/

### Libraries:
- NLP: NLTK, Gensim.
- Web scrapping: Beautiful Soup, Newspaper3k.

### Approach followed:
- Step 1 - Extraction and preparation of the dataset.
- Step 2 - Cleaning of the dataset content.
- Step 3 - Perform NLP tasks (Tokenization, Stopwords removal....).
- Step 4 - Forming lexicon of bias words (10 words).
- Step 5 - Gensim model definition.
- Step 6 - Choose one bias word from the lexicon and finding 10 similar words to it.
- Step 7 - Finding the vector representation of each of those 10 similar words (From step 6).
- Step 8 - Calculating the mean of word vectors of those 10 similar words.
- Step 9 - Determining top 100 similar words to the mean of the word vector obtained in step 8.
- Step10 - Computing the cosine distance between each of the 100 similar words to the word chosen in step 6.

Repeat step 6 to step 10 to find top 100 similar words to each bias word in the lexicon framed.
This method of finding the mean of words vectors and then determining the 100 similar words is fetched from the paper URL: http://wikiworkshop.org/2018/papers/wikiworkshop2018_paper_1.pdf

### Code execution steps:
The code is well formatted and structured to execute it cell by cell without any confusion. But do keep in mind while writing the article links to csv file. If you are just evaluating my code then you need not run the csv WRITE code snippet, but simply update the path of corresponding csv files in the csv READ code snippent which has been uploaded in the repository. 
### Note - Use the file OutputsClearedOff.ipynb or PreliminaryTask.py to see the code without any outputs, because the main file PreliminaryTaskMasterThesis.ipynb has output cells in it which will make you to scroll down a lot.
