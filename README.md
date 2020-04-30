# Parsimonious Vole: A Systemic Functional Parser for English

PhD dissertation, Eugeniu Costetchi, May 2019. Defended on December 9, 2019.
Published in 2020. 

## Download

[Thesis](phd-thesis-ECO-2020-04-30.pdf)

## Citing

Please cite using the following BibTex entry:

```BibTeX
    @phdthesis{Costetchi-PhD,
     author = {Eugeniu Costetchi},
     title = {{Parsimonious Vole: A Systemic Functional Parser for English}},
     school = {University of Bremen},
     year = {2020},
     type = {Dr. Phil.},
     month = {May},
     note = {},
    }
```

## Abstract 

Building a natural language parser can be seen as a task of creating an artificial text reader that understands the meaning expressed in some text. This thesis aims at a reliable modular method for parsing unrestricted English text into feature-rich constituency structure using Systemic Functional Grammars (SFG). SFGs are chosen because of their versatility to account for the complexity and phenomenological diversity of human language.

The descriptive power of a Systemic Functional Grammar (SFG) lies in its separation of descriptive work across “structure” (i.e., syntagmatic organisations) and “choice”(i.e., paradigmatic organisations). A shortcoming for parsing, however, is that SFL has been primarily concerned with the paradigmatic axis of language, and accounts of the syntagmatic axis of language, such as the syntactic structure, have been put in the background.

Moreover, parsing with features that depart from directly observable grammatical variations towards increasingly abstract semantic features comes at the cost of high computational complexity, which still presents today the biggest challenge in parsing broad coverage texts with full SFGs.Previous research has discussed how each successive attempt to construct parsing components using SFL then led to the acceptance of limitations either in grammar size or in language coverage.

One of the main contributions of this thesis is the investigation to what degree cross-theoretical bridges can be established between Systemic Functional Linguistic(SFL) and other theories of grammar, in particular Dependency Grammar, in order to compensate for the limited syntagmatic accounts. A second main contribution is to research how suitable predefined graph patterns are for detecting systemic features in he constituency structure in order to reduce the complexity of identifying increasingly abstract grammatical features.

The technical achievement of this thesis lies in the development and evaluation of a SFG parser, named Parsimonious Vole. The implementation follows a pipeline architecture comprising two major phases: (a) creation of the constituency structure from Dependency graphs and (b) structure enrichment with the systemic features using graph pattern matching techniques.

The empirical evaluation is based on two manually annotated corpora. First one covers constituency structure and Mood features, and second corpora covers the more abstract Transitivity features. The parser accuracy at generating constituency structure(76%) is slightly lower than that achieved in previous research, while the accuracy to detect Mood (60%) and Transitivity (42%) could not be compared to any previous works because either such features are missing or the results are not comparable.

The current work concludes that (a) reusing parse results with other grammars for structure creation and (b) employing graph patterns for enrichment with systemic features constitutes a viable solution to create feature-rich constituency structures in SFL style.

##Final word

In this work I have advanced the work on automatic text analysis in SFL style. The current implementation did not succeed to employ a full SF grammar, and, just like previous attempts, had to accept limitations in the grammar size while maintaining broad language coverage. This task is particularly difficult because of the richness of such grammars. Nonetheless, modern applications desperately need deep feature-rich text analysis functionalities.

My view is that building on top of successful results achieved with other grammars by mapping them to parts of SF grammar constitutes a viable solution to the creation of SFL style constituency structures. Furthermore, employing graph patterns to enrich the structure with systemic features is the key ingredient for performing a delicate feature-rich text analysis.

By further advancing the proposed methods and exploring new ways to cut through complexity, my hope is that one day automatically generating feature-rich text analysis will become the de facto approach employed in truly intelligent agents that can, to a large extent, do with language what people do.

## Template credits

This manuscript uses [CUED template](https://github.com/kks32/phd-thesis-template).

## License
[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
