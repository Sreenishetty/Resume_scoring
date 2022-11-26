# **Resume Scoring**

**Meghna Lohani 16BCE1395**

**Aman Sharma 16BCE1224**

# **Workflow**

    1. Creating corpus using Sketch Engine

    2. Creating word embedding using Genism , Word2Vec

    3. Preprocessing

    4. Removing common words that are not required

    5. Creating phrases of words that frequently occur togther (bigrams)

    6. Building word2vec model

    7. Extracting resumes (using PyPDF) and converting to string

    8. Building candidate profile using model.most_similar(skills), where skills is an array of required skills

    9. Creating a matcher using Spacy to match the wods in resume to most_similar(skills)

    10. Printing and visualizing the candidate profile

# **Creating Corpus using sketch Engine**

We used SketchEngine to create a corpus, wikipedia pages were given as input
