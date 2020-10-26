## Spam-Filter
This is an assignment of machine learning course by Andrew Ng in python (instead of Matlab).
SVM is used to classify whether the email is a spam.
Features are encoded as vectors e.g. sale is [0 0 0 1 0 0], where the length of each vector equals the total number of words.

### Preprocessing email
1. Lower-casing: The entire email is converted into lower case. \n
2. Stripping HTML: All HTML tags are removed from the emails.
3. Normalizing URLs: All URLs are replaced with "httpaddr".
4. Normalizing Email Addresses: All email addresses are replaced with "emailaddr".
5. Normalizing Numbers: numbers are replaced with the "number".
6. Normalizing Dollars: $ is replaced with the "dollar".
7. Word Stemming: Words are reduced to their stemmed form using Porter Stememr.
8. Removal of non-words: Non-words and punctuation have been re-
moved. All white spaces (tabs, newlines, spaces) have all been trimmed
to a single space character.
