## Developing Russian lexical relations database

#### Goals
* evaluate distributional models against predicting lexical relations;
* automatically compile large-scale relations database.
 
#### Approach
Lexical relations are represented as linear transformation between headword and argument spaces.
Test samples are available at ``data/`` folder.

We experiment with various distributional models from [RusVectōrēs](http://rusvectores.org/en/models/).

Linear transformation is fitted with lexical functions data (see [SynTagRus corpus](http://universaldependencies.org/treebanks/ru_syntagrus/index.html))
and [Verbal combinatory dictionary](http://dict.ruslang.ru/abstr_noun.php)

#### References
 1. Enikeeva E., Mitrofanova O. (2017) *Russian Collocation Extraction based on Word Embeddings*. In: Computational Linguistics and Intellectual Technologies. Proceedings of the International Conference «Dialogue 2017». Issue 16. Vol. 1. Moscow. Pp. 52–64.
 2. Mel’čuk, I., Zholkovsky A.(1984) *Explanatory Combinatorial Dictionary of Modern Russian \[Tolkovo-kombinatornyj slovar russkogo jazyka\]*. Vienna, 1984.
 3. Rodríguez-Fernández S., Anke L., Carlini R., Wanner L. (2016) *Semantics-driven recognition of collocations using word embeddings*, Proceedings of the 2016 Annual Meeting of the Association for Computational Linguistics (ACL), Berlin, Germany.
 
