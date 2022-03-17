# cisc489-ngrams
HW1 for CISC489 - Computing n-grams

Kevin Bookwalter

Answers to HW questions are in analysis.txt

Libraries Used:
    NLTK:
        I have a few imports from the NLTK library, which include:
            ABC Corpus:
                The corpus contains collections of short news articles from the Australian Broadcasting Comission published in 2006.
                There is one document of rural news and one document of scientific news. These are the documents used in the submitted
                version of my project.
            RegexpTokenizer:
                A class for tokenizing documents based on regular expressions. I used this to tokenize words in such a way that removed
                punctuation but kept certain non-letter charachers like apostrophes and hyphens in words.
            word_tokenize:
                A method to tokenize words. This tokenizes punctuation marks as their own words, which could be useful in some cases. It's
                not used in the version of this I submitted but I kept it in there in case I want to mess around with this later.

Output Files:
    b1_counts.txt:
        unsorted bigram counts from document 1
    b2_counts.txt:
        unsorted bigram counts from document 2
    sorted_b1_counts.txt:
        sorted bigram counts from document 1
    sorted_b2_counts.txt:
        sorted bigram counts from document 2
    word_ct_from_b1.txt:
        individual word counts from document 1 extrapolated from bigram counts (this is the same as unigram counts)
    word_ct_from_b2.txt:
        individual word counts from document 2 extrapolated from bigram counts (this is the same as unigram counts)
    word_ct_from_u1.txt:
        unigram counts from document 1
    word_ct_from_u2.txt
        unigram counts from document 2
    sentence_probabilities.txt:
        output of probability calculations for test sentences