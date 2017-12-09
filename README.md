# Alphabinary Codewords

These are curated lists of words corresponding to alphabinary values that have been specially selected, using similar logic to the NATO Phonetic Alphabet, avoiding words that may introduce problems when read, spoken, and written, such as:

- mishearing as other words (or verbal tics)
- misreading as other words (or instructions)
- mistranscribing with alternative spellings (such as regional variations)

Effort has been made to include between 10 and 15 words per list; however, this is not always possible (around 8% of the 8-bit patterns have fewer than ten words matching their pattern total).

In cases where there are many options available, the words selected have been narrowed down to fit the criteria above pretty conservatively; the only situation where these criteria were compromised slightly were when the compromise would have no effect on alphabinarization, such as `0100` including "cola" in its list, even though many non-English-native locales would spell it as "kola".

These are meant for use cases that wish to assign *arbitrary words* to bit patterns; tools for *authorship* should make use of a full English wordlist (such as [SCOWL](https://github.com/en-wl/wordlist)).

## using these lists

## completed bitdicts

### 2bit

Because the choices for two-letter words with no problems are so scant, supplemantary lists of words that may be potentially confused in contexts outside of two-letter words (such as "eh", "pi", "mu", and "ow") have been included as "XX-subpar". If your use case exclusively makes use of two-letter words, including these lists for added variety may be useful: otherwise, it's recommended to simply stick with the few words selected for each file (if including two-letter words is appropriate at all).

### 3bit

### 4bit

## in progress

### 5bit

### 6bit

### 7bit

### 8bit

### beyond 8bit

There are no 9bit dictionaries because I'm basing my decisions on the word list from Ubuntu 14.04's wamerican package, and that list contains no words with an alphabinary pattern of `101111110` (382). (However, after looking at the words for `1111110`, it's clear that that list is missing the word "repurpose", so this decision may get revisited.)