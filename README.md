# SpellChecker
SpellChecker is a Python class that provides spell-checking functionality. It takes a dictionary of words as input and can suggest nearest words for misspelled words.

## Installation
The SpellChecker class requires Python 3.6 or later. To use it, simply copy the code into your Python code file or import the SpellChecker class from the file.

## Usage
To use the SpellChecker class, you need to create an instance of the class with a dictionary of words. The dictionary can be specified as a local file path or a URL.

### Imports
from SpellChecker import SpellChecker

### Load dictionary from local file path
s = SpellChecker("dictionary.txt")

### Load dictionary from URL
s = SpellChecker("dictionary.txt")

## Once you have created an instance of the SpellChecker class, you can use the following methods:
### Adds a new word to the dictionary.
add_word(word)

### Returns a list of the nearest words to a given word. If the given word is already in the dictionary, it returns a list containing only that word. Otherwise, it generates a list of candidate words and returns the top 4 candidates sorted by their edit distance to the input word and lexicographic order.
get_nearest_words(word)
