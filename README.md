# Python-DictionaryCode
A dictionary program written in python to enable word searches

we have used simple else if to check if the word searched for is in the data json , or if the closest match to the word is in the data json , we used *getclosematches* from the *difflib* library to make our lives easy
## difflib 
This module provides classes and functions for comparing sequences. It can be used for example, for comparing files, and can produce information about file differences in various formats

### get_close_matches(word,possibilities)
Return a list of the best “good enough” matches. word is a sequence for which close matches are desired (typically a string), and possibilities is a list of sequences against which to match word (typically a list of strings).
