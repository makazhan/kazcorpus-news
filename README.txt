=== summary ===
This is the "news" sub-corpus of a Kazakh language corpus (http://kazcorpus.kz) that contains news articles in Kazakh language. Documents may contain excerpts in Russian language as well, but those are relatively rare and mostly limited to two-three word phrases.

=== document format ===
All documents have the following format:
TITLE:<whitespace>article title
URL:<whitespace>source URL
META:<whitespace>meta info, i.e. keywords, etc.
DATE:<whitespace>date released
AUTHOR(S):<whitespace>author(s) of the article (if were able to be extracted automatically, otherwise N/A)
TEXT:<newline>
article body
*The text of the article always starts on a new line following the line containing the marker "TEXT:"

=== basic stats ===
documents	55352
   tokens	14939567
    types	455072
* tokens are considered to be alphabetic sequences (no digits or punctuation)

=== citation ===
To cite in bib format, please use the following entry:
@InProceedings{KLC2013,
  author    = {Makhambetov, Olzhas  and  Makazhanov, Aibek  and  Yessenbayev, Zhandos  and  Matkarimov, Bakhyt  and  Sabyrgaliyev, Islam  and  Sharafudinov, Anuar},
  title     = {Assembling the Kazakh Language Corpus},
  booktitle = {Proceedings of the 2013 Conference on Empirical Methods in Natural Language Processing},
  month     = {October},
  year      = {2013},
  address   = {Seattle, Washington, USA},
  publisher = {Association for Computational Linguistics},
  pages     = {1022--1031},
  url       = {http://www.aclweb.org/anthology/D13-1104}
}

Otherwise search for required citation formats by the title of the publication, i.e. "Assembling the Kazakh Language Corpus".
