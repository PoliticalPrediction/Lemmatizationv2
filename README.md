# Lemmatizationv2
Firstly, the corpus reader wordnet is imported.
WordNetLemmatizer is imported from wordnet.
Word tokenize as well as parts of speech tag are imported from nltk.
Default Dictionary is imported from collections.
Dictionary is created where pos_tag (first letter) are the key values whose values are mapped with the value from wordnet dictionary. We have taken the only first letter as we will use it later in the loop.
Text is written and is tokenized.
Object lemma_function is created which will be used inside the loop.
Loop is run and lemmatize will take two arguments one is token and other is a mapping of pos_tag with wordnet value.
