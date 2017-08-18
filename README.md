# no-context

**The plan**: a collection of parsing tools for parsing anything, efficiently, in Node.JS.

To include:

* a super-fast tokenizer ([moo](https://github.com/no-context/moo))
* a selection of parsing algorithms (LR, Earley, RNGLR...)
* options for using ordered-choice-CFGs, capturing ambiguous parses using an SPPF, or even providing custom derivation merging behaviour (so you can control allocation)
* tools for analysing grammars (e.g. Nearley's _Unparser_)
* tools for generating syntax highlighting, e.g. CodeMirror modes, from your grammar
