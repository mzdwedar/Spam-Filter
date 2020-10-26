## Spam-Filter
This is an assignment of machine learning course by Andrew Ng in python (instead of Matlab).
SVM is used to classify whether the email is a spam.
Features are encoded as vectors e.g. sale is [0 0 0 1 0 0]

### Preprocessing email
• Lower-casing: The entire email is converted into lower case.
• Stripping HTML: All HTML tags are removed from the emails.
• Normalizing URLs: All URLs are replaced with "httpaddr".
• Normalizing Email Addresses: All email addresses are replaced with "emailaddr".
• Normalizing Numbers: numbers are replaced with the "number".
• Normalizing Dollars: $ is replaced with the "dollar".
• Word Stemming: Words are reduced to their stemmed form using Porter Stememr.
• Removal of non-words: Non-words and punctuation have been re-
moved. All white spaces (tabs, newlines, spaces) have all been trimmed
to a single space character.
