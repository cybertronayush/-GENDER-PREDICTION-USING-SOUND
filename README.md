# -GENDER-PREDICTION-USING-SOUND

When you're writing code to search a database, you can't rely on all those data entries being spelled correctly.
________________________________________________________________________________________________________________________________________________________________________________

Searching for a person's name in a database is a unique challenge. Depending on the source and age of the data, you may not be able to count on the spelling of the name being correct, or even the same name being spelled the same way when it appears more than once. Discrepancies between stored data and search terms may be introduced due to personal choice or cultural differences in spellings, homophones, transcription errors, illiteracy, or simply lack of standardized spellings during some time periods. These sorts of problems are especially prevalent in transcriptions of handwritten historical records used by historians, genealogists, and other researchers.

A common way to solve the string-search problem is to look for values that are "close" to the same as the search target. Using a traditional fuzzy match algorithm to compute the closeness of two arbitrary strings is expensive, though, and it isn't appropriate for searching large data sets. A better solution is to compute hash values for entries in the database in advance, and several special hash algorithms have been created for this purpose. These phonetic hash algorithms allow you to compare two words or names based on how they sound, rather than the precise spelling.
_________________________________________________________________________________________________________________________________________________________________________________
The algorithms are:
Soundex
NYSIIS 
I chose to Work with NYSIIS becouse it provide 2.7% of better Accuracy than that of Soundex
