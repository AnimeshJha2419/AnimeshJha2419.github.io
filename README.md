# Plagarism Detection using NLTK
This is a comprehensive tutorial on how to perform Plagarism Detection using NLTK

For the tutorial, please refer to the [website](https://animeshjha2419.github.io/)

About the project:
This code is designed to help detect plagiarism in Arabic text files. The program works by training on a set of text files in a specified folder, pre-processing the texts, and vectorizing them using the TF-IDF method. The program then compares a given text file with the trained dataset using cosine similarity to determine the similarity score with the most similar training file. The program uses NLTK for pre-processing and the scikit-learn library for vectorizing and calculating cosine similarity.

To use this program, you will need to specify the folder containing the training data and the file to compare. The program will then train on the data, compare the given file with the trained dataset, and output the most similar training file and the percentage similarity score.

This program can be used to detect plagiarism in a variety of contexts, including academic work, journalism, and legal documents. It is particularly useful for Arabic text files, as it uses NLTK and scikit-learn, which both support the Arabic language.

In this project, the training dataset and testing sample were created by the author. The training dataset consists of Arabic text files that were manually collected and selected to represent a range of different topics and writing styles. The testing sample is also an Arabic text file that was created by the author specifically for the purpose of testing the program.

The natural language processing (NLP) used in this project involves several steps. Firstly, NLTK's "stopwords" corpus is used to remove common stop words from the text. Stop words are words that occur frequently in a language but do not carry much meaning, such as "and", "the", and "a". Removing these words helps to focus on the most meaningful content in the text.

Next, NLTK's "punkt" module is used to tokenize the text into individual words. Tokenization is the process of breaking down a sentence or document into individual words or phrases. This allows the program to analyze the text at a more granular level and extract more meaningful features.

After tokenization, NLTK's "SnowballStemmer" is used to reduce each word to its root form, or stem. This process is called stemming and it helps to group together different forms of the same word. For example, "running", "runner", and "run" would all be reduced to "run" after stemming.

Finally, the preprocessed text is vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) method. This method calculates the frequency of each word in the text and assigns a weight to each word based on how frequently it occurs in the text and how commonly it occurs in the entire corpus. This creates a vector for each document that can be used to compare its similarity to other documents using cosine similarity.

In summary, the NLP used in this project involves removing stop words, tokenizing the text, stemming the words, and vectorizing the preprocessed text using the TF-IDF method. These steps help to extract meaningful features from the text and create a representation that can be used to compare similarity between different documents.
