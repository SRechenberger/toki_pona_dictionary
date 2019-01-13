# Toki Pona Dictionary
yaml file of the official toki pona dictionary,
as described in "Toki Pona - The Language of Good" by Sonja Lang (ISBN: 978-0-9782923-0-0; see also [http://tokipona.org](http://tokipona.org))

## Structure
- Every word is a key
- Every word category (*noun*, *verb*, *pre-verb*, *adjective*, *particle*, *preposition*, *number*)
  is a key under a word
- Meanings are given as lists of lists of words; e.g.: from an entry like
  
  ```
  ike
    ADJECTIVE bad, negative; non-essential, irrelevant
  ```
  
  the *yaml*-entry
  
   ```yaml
   ike:
    adjective:
      - - bad
        - negative
      - - non-essential
        - irrelevant
   ```
   is made.
    
## The Dictionary
The dictionary is written off the book, except for very slight changes.
E.g.: if there is a list of verbs, every one is initiated with *to* instead of just the first one.


## Contribution
Any greater changes than those mentioned above are mistakes; if you see any such error, please submit an issue.


## Disclaimer
*The list is yet incomplete!*
