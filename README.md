# Big-Scale Analytics
This is the repository of group Omega for the BSA project. We will upload further documentation in the future.

## Milestone 1
### Literature Review, Methodology

For the project we had searched for some paper with the key words like “foreign language” “level” and “machine learning”. 

In one of the paper (1) published on the  internet site “Medium”, there were aslo links to the algorithmes like “BLEU” and “The Flesch–Kincaid readability tests ”. These are also explained in the wikipedia pages. 

The wikipedia page on ““The Flesch–Kincaid readability tests”   make use of the number of sylables in the sentences. It seems they take into consideration the #total sylabes,  #total words, and #total sentences.Flesch reading ease decreases with dificullty level, while the Flesch-Kincaid increases with difficulty.  Looking  some scores for Flesch reading ease test about  the daily used text materials like newspaper “Daily Digest” (score of 65), “Harward Law Review” (score of 30) , we can conclude about their precision as far as the level of these mentioned materials are concerned. As the score increases readibility level increases -becomes more easier to read.


In the paper (1), the author talks about legibility, which basically deals format styles like bold or italic to make it easier for reading and understanding. In deed, such format styles can help better understand. We thought other marks can also help reader understand better. For example a dialog which is represented inside quotation marks can be annotated for lower levels. This paper mention a list of words by sylabes, which can be found here (3)

Looking at the wikipedia page on “BLUE” (4), we think it this is basically about the quality between human and machine made translations. When we looked at the bibliographical stuedies we had observed studies based on “corpus-based comprhensive and diagnostic evaluation”, “n-gram cooccurrence statistics”, “skip-bigram statistics”.

Machine evaluation techniques can be used to infill cloze test (texts with empty places to be filled). We understand this is not restricted to guessing a right unser, bu also providing suggestions for alternatives (5).

Looking the relevant shelf in the library, "Linguistic-Language Processing", we noted that mostly the research contains many linguistics terms rather than programming codes or algorithmes. This gave us a perceptions that this domain will contain textuals terms and concepts.

We have revised the  libraries from our previous course, "Data Minning and Machine Learning".  The spacy libarary provides toolls to tokenize textes into words, sentences, their part of speach(POS).  CountVectorizer class of scikit learn enables us count the words in sentences in the corpus (6). 




### Sources

1-https://medium.com/glose-team/how-to-evaluate-text-readability-with-nlp-9c04bd3f46a2
2- Flesch–Kincaid readability tests
https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests#Flesch%E2%80%93Kincaid_grade_level

3-Sylabes Counts:
http://countwordsworth.com/download/DaleChallEasyWordList.txt

4-Bilingual Evaluation Understudy  (BLEU)
https://en.wikipedia.org/wiki/BLEU

5-Cloze Test
https://en.wikipedia.org/wiki/Cloze_test

6-https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html

