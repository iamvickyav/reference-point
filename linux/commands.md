# wc - Word Count

```sh
> wc /usr/share/dict/words
235886 235886 2493109 /usr/share/dict/words

Prints number of lines, words, bytes and filename.

> wc -l (Number of lines)

> wc -m (Number of chars)

> wc -c (Number of bytes)

> wc -w (Number of words)
```

# grep command

```sh
> grep Hello input.txt

prints all lines with the word Hello from input.txt file (Case sensitive)

> grep -v Hello input.txt

prints all lines without the word Hello from input.txt file

> grep -n Human input.txt

prints all lines with word Human and line number

> grep -c Human input.txt

prints count of number of lines with word Human

> grep -i

case insensitive search

> grep Human *

search all files in the folder for the word Human


```

