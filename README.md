# Prefix-and-Suffix-Search
Given a prefix or a suffix find all matching words in a given list of words.

## Examples

Git clone the repository and run the code in the terminal.
The following examples all create with reading the list of words from standard input.
`words_list.txt` is a txt file each line of which is a word. 

1. Return usage instructions of the application.

```
python fix_search.py -h
```

2. Return a list of words with the prefix "abacul".

```
python fix_search.py -p "abacul" < words_list.txt
```

3. Return a list of words with the suffix "abacul".

```
python fix_search.py -s "abacul" < words_list.txt
```