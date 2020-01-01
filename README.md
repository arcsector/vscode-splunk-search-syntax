# vscode-splunk-search-syntax Extension README

Main repo for vscode splunk syntax highlighting.

## Initial version

- Highlights main search functions and eval functions, as well as escape keys
- Autocompletes macro ticks and brackets as well as quotes

## TODO

- [ ] Change highlighting color to match Splunk search bar
  - Not sure if this is going to happen or not, as there is a need to stick to [Textmate Naming Conventions](https://macromates.com/manual/en/language_grammars#naming_conventions)
- [X] Highlight operators (AND OR by as NOT true false)
- [X] Highlight macros
- [ ] Highlight command options
  - For example, stats has the parameter partitions=X, partitions should be highlighted in this instance only after the = sign has been placed
- [ ] Highlight variables after eval functions
- [ ] Publish to VSCE Marketplace
