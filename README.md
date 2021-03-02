# NLP-Keep-editing
Keep editing NLP resources and materials...
### what is NLP
 (NLP) is a branch of ML that deals with processing, analyzing, and sometimes generating human speech 
 What is Tokenization
Tokenization is essentially splitting a phrase, sentence, paragraph, or an entire text document into smaller units, such as individual words or terms. Each of these smaller units are called tokens (or) Tokenization or word segmentation is a simple process of separating sentences or words from the corpus into small units, i.e. tokens.

### Types of tokenization
white space tokenization, Dictionary based, Rule based, Penn Tree, spacy, Moses, Subword Tokenization(Byte pair, word piece, Sentence piece, unigram language model)

##### White Space Tokenization
This is the simplest tokenization technique. Given a sentence or paragraph it tokenizes into words by splitting the input whenever a white space in encountered.

##### Dictionary Based Tokenization
In this method the tokens are found based on the tokens already existing in the dictionary. If the token is not found, then special rules are used to tokenize it. It is an advanced technique compared to whitespace tokenizer.

##### Rule Based Tokenization
In this technique a set of rules are created for the specific problem. The tokenization is done based on the rules. For example creating rules bases on grammar for particular language.

##### Regular Expression Tokenizer
This technique uses regular expression to control the tokenization of text into tokens. Regular expression can be simple to complex and sometimes difficult to comprehend. This technique should be preferred when the above methods does not serve the required purpose. It is a rule based tokenizer.

##### Penn TreeBank Tokenization
Tree bank is a corpus created which gives the semantic and syntactical annotation of language. Penn Treebank is one of the largest treebanks which was published. This technique of tokenization separates the punctuation, clitics (words that occur along with other words like I’m, don’t) and hyphenated words together.

##### Spacy Tokenizer
This is a modern technique of tokenization which faster and easily customizable. It provides the flexibility to specify special tokens that need not be segmented or need to be segmented using special rules. Suppose you want to keep # as a separate token, it takes precedence over other tokenization operations.

##### Moses Tokenizer
This is a tokenizer which is advanced and is available before Spacy was introduced. It is basically a collection of complex normalization and segmentation logic which works very well for structured language like English.

##### Subword Tokenization
This tokenization is very useful for specific application where sub words make significance. In this technique the most frequently used words are given unique ids and less frequent words are split into sub words and they best represent the meaning independently.

This helps the language model not to learn fewer and fewest as two separate words. Byte-Pair Encoding (BPE) This technique is based on the concepts in information theory and compression. BPE uses Huffman encoding for tokenization meaning it uses more embedding or symbols for representing less frequent words and less symbols or embedding for more frequently used words.
##### WordPiece
WordPiece is similar to BPE techniques expect the way the new token is added to the vocabulary. BPE considers the token with most frequent occurring pair of symbols to merge into the vocabulary. While WordPiece considers the frequency of individual symbols also and based on below count it merges into the vocabulary. Count (x, y) = frequency of (x, y) / frequency (x) * frequency (y) The pair of symbols with maximum count will be considered to merge into vocabulary. So it allows rare tokens to be included into vocabulary as compared to BPE.

### What is Corpus (or corpora in plural) 
is simply a certain collection of language data (e.g. texts). Corpora are normally used for training different models of text classification or sentiment analysis, for instance.

### What is Token 
is a final string that is detached from the primary text, or in other words, it's an output of tokenization.
