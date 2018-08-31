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

Numpy --> for writing and loading the spelling correction results.
Sklearn --> for randomly extracting the data subset.
Dataset --> Wikipedia
