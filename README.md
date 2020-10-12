UCCA-Annotated French-English Parallel Corpus
=============================================
Version 1.2.2 (September 23, 2018)
----------------------------------

This bundle and [its French counterpart](https://github.com/UniversalConceptualCognitiveAnnotation/UCCA_French-20K)
contain 154 pairs of French-English aligned passages, annotated
with the UCCA annotation (Abend & Rappoport, ACL 2013).
This corpus contains 492 sentences, which correspond to 12574 tokens.


The users of this dataset are kindly requested to cite [the following publication](http://www.aclweb.org/anthology/W15-3502):
```
@inproceedings{sulem-etal-2015-conceptual,
    title = "Conceptual Annotations Preserve Structure Across Translations: A {F}rench-{E}nglish Case Study",
    author = "Sulem, Elior  and
      Abend, Omri  and
      Rappoport, Ari",
    booktitle = "Proc. of S2MT",
    month = jul,
    year = "2015",
    address = "Beijing, China",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W15-3502",
    doi = "10.18653/v1/W15-3502",
    pages = "11--22",
}
```


Corpus:
-------
The French-English corpus used here is an extract (the first five chapters) from the book 
Twenty Thousand Leagues Under the Sea (Vingt Mille Lieues Sous les Mers),
a classic science fiction novel written in French by Jules Verne (from 1828 to 1905) 
and first published in 1870.

French:
[Jules Verne. 1870. Vingt Mille Lieues Sous les Mers. J. Hetzel.](http://fr.wikisource.org/wiki/Vingt_mille_lieues_sous_les_mers)

English
[Jules Verne. 1991. Twenty Thousands Leagues Under the Sea. Translated from the original French by J.P. Walter](http://jv.gilead.org.il/fpwalter)


Format and Source Code:
----------------------

Information about the format of the xml files and source code for reading and manipulating them are
available at http://www.cs.huji.ac.il/~oabend/ucca.html.


Bilingual Passages and Alignment:
--------------------------------
 
The passages in English and French correspond to the paragraphs in the original texts except in a few cases of long dialogues, 
where we split the paragraphs into several passages.

English side:
* Chapter1: Passages 36-62 
* Chapter2: Passages 286-318 
* Chapter3: Passages 814-846 
* Chapter4: Passages 880-909 
* Chapter5: Passages 968-998 
          
French side:
* Chapter1: Passages 77-103 
* Chapter2: Passages 416-448
* Chapter3: Passages 764-796 
* Chapter4: Passages 848-877
* Chapter5: Passages 911-941

Each passage in French corresponds to a single passage in English, where the two sides are ordered as above.
For example, passage 77 in French corresponds to passage 36 in English and passage 765 in French 
corresponds to passage 815 in English.



