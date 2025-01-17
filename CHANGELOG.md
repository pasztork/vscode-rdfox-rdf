# Changelog

## 1.2.0 (14 September 2023)
- Add autocompletion and help text for RDFox commands
- Add autocompletion for SPARQL functions
- Add button to open a query in RDFox console
- Add buttons to add/delete a Datalog rule
- Add settings that determine an RDFox datastore to target with the above
- Add configuration defaults for better word-based autocompletion when working with RDF data
- Update SPARQL functions for RDFox 6.3

## 1.1.0 (28 July 2023)
- Add hover functionality for command documentation in RDFox shell scripts
- Fix highlighting of line continuation symbol when followed by whitespace in RDFox shell scripts
- Update commands highlighted in RDFox shell scripts for RDFox 6.3

## 1.0.4 (15 December 2022)
- Fix highlighting of single-quoted literals with double quotes inside ([Issue #4](https://github.com/OxfordSemantic/vscode-rdfox-rdf/issues/4))

## 1.0.3 (23 November 2022)
- Account for RDFox 6.0 syntax
- Fix highlighting of prefixed IRIs with escaped "#"
- Remove highlighting of SPARQL-only keywords in Datalog

## 1.0.2 (15 September 2022)
- Fix multi-line literal support in Turtle and other languages ([Issue #1](https://github.com/OxfordSemantic/vscode-rdfox-rdf/issues/1))
- Add query command (`select`, `insert`...) and `serverinfo` highlighting in RDFox scripts
- Fix unnecessary highlighting after `echo` and `grant` commands in RDFox scripts
- Tweak comment highlighting in RDFox scripts

## 1.0.1 (21 July 2022)
- Recognize SPARQL operators followed directly by "?"

## 1.0.0 (20 July 2022)
- Initial release