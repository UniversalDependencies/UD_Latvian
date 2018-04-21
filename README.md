# Summary

Latvian UD Treebank is based on Latvian Treebank ([LVTB](http://sintakse.korpuss.lv)), being created at University of Latvia, Institute of Mathematics and Computer Science, [Artificial Intelligence Laboratory](http://ailab.lv).

# Introduction

Latvian UD Treebank v2.2 consists of 7,703 sentences (110,636 tokens), and it has been obtained by automatic conversion of both the morphological and the syntactic annotations of the original LVTB treebank. LVTB data contains manually verified syntactic annotation according to a hybrid dependency-constituency schema, as well as manually verified morphological tags and lemmas.

# Acknowledgments

This work is supported by European Regional Development Fund under the grant agreement No. 1.1.1.1/16/A/219 (Full Stack of Language Resources for Natural Language Understanding and Generation in Latvian). The pilot project was supported by State Research Programme "National Identity".

# References

Grūzītis N., Pretkalniņa L., Saulīte B., Rituma L., Nešpore-Bērzkalne G., Znotiņš A., Paikens P. Creation of a Balanced State-of-the-Art Multilayer Corpus for NLU. Proceedings of the 11th International Conference on Language Resources and Evaluation (LREC). Miyazaki, Japan, 2018 (to appear)

Pretkalniņa L., Rituma L., Saulīte B. Universal Dependency Treebank for Latvian: A Pilot. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 289, IOS Press, 2016, pp. 136-143

Pretkalniņa L., Rituma L. Constructions in Latvian Treebank: The Impact of Annotation Decisions on the Dependency Parsing Performance. Human Language Technologies - The Baltic Perspective, Frontiers in Artificial Intelligence and Applications, Vol. 268, IOS Press, 2014, pp. 219-226

Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. Towards a Latvian Treebank. Actas del III Congreso Internacional de Lingüística de Corpus. Valencia, Spain, 2011, pp. 119-127

Pretkalniņa L., Nešpore G., Levāne-Petrova K., and Saulīte B. A Prague Markup Language profile for the SemTi-Kamols grammar model. Proceedings of the 18th Nordic Conference of Computational Linguistics. Riga, Latvia, 2011, pp. 303-306

# Licensing

The data set is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. Please contact us if you are interested in acquiring a commercial licence.

# Data splits

The training data covers various text types: news, fiction, academic texts, legal texts, transcripts of spoken language, etc. The development and test sets are carefully split out to cover all those types.

Train: 5424 sentences\
Dev:   1051 sentences\
Test:  1228 sentences

# Statictics

Tree count:  7703\
Word count:  110636\
Token count: 110636\
Dep. relations: 125 of which 93 language specific\
POS tags: 17\
Category=value feature pairs: 56

# Changelog

2018-04-15 v2.2
  * Repository renamed from UD_Latvian to UD_Latvian-LVTB.
  * Fixed tokenization for text errors.
  * Added notifications in the MISC field for corrected text errors.
  * Improved enhanced dependencies.
  * Added more data.

2017-11-15 v2.1
  * Removed duplicated and artificially constructed sentences.
  * Fixed a bug producing Evident=Fh,Nfh where Evident=Fh should be.
  * Added significantly more data.
  * Added enhanced dependencies.

2017-02-15 v2.0
  * Annotation changed according to UD v2 guidelines.
  * Lots of new data.
  * Some annotation errors corrected.

2016-11-15 v1.4
  * Corrected a number of syntactic annotation mistakes.
  * Multi-word conjunctions: first part is now tagged PART.
  * Added new sentences.

<pre>
=== Machine-readable metadata =================================================
Data available since: UD v1.3
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: news fiction legal spoken academic
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Pretkalniņa, Lauma; Rituma, Laura; Saulīte, Baiba; Nešpore-Bērzkalne, Gunta; Grūzītis, Normunds
Contributing: elsewhere
Contact: lauma@ailab.lv, normunds@ailab.lv
===============================================================================
</pre>
