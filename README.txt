This program is written with ipython notebook, using 4 different algorithms:

1. Levenshtein Distance (LD)
Using python-levenshtein (By Antti Haapala <antti@haapala.name>)
https://github.com/ztane/python-Levenshtein

2. Damerau-Levenshtein Distance (DLD)
Using jellyfish (by James Turk <dev@jamesturk.net> and Michael Stephens)
https://github.com/jamesturk/jellyfish

3. Weighted-Levenshtein Distance (WLD)
Using weighted-levenshtein
https://github.com/infoscout/weighted-levenshtein

4. N-Gram Distance
Self-implemented without external modules.

Other modules imported:
Numpy --> for writing and loading the spelling correction results.
Sklearn --> for randomly extracting the data subset.

Dataset:
Wikipedia contributors (n.d.) Wikipedia:Lists of common misspellings. In Wikipedia: The
Free Encyclopedia, https://en.wikipedia.org/w/index.php?title=Wikipedia:
Lists_of_common_misspellings&oldid=813410985
