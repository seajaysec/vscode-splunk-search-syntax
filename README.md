# Splunk Search Syntax Highlighter VSCode Extension README

Main repo for vscode splunk syntax highlighting

## Features

- Language auto-recognition and highlighting associated with `.spl` and `.splunk` files
- Highlights main search, stats, and eval functions, as well as escape keys
- Autocompletes macro ticks and brackets as well as quotes
- Highlights strings, parameters, arguments, macro names, and keywords

## How to install

### Install from Source

Install from source by downloading this repo and unzipping into your vscode extensions directory (ususally ~/.vscode/extensions)

### Install in Visual Studio Code directly

Install directly in visual studio by going to the extensions tab and searching for `"splunk search"`. The quotes are imperative as the words are normally not treated as a phrase. Click the `Install` button on the  extension with the same name as this README and you're good to go.

## TODO

- [X] Highlight keywords (AND OR by as NOT true false)
- [X] Highlight macros
- [X] Highlight macro and eval command parameters/arguments
- [X] Highlight command options
  - For example, stats has the parameter partitions=X, partitions should be highlighted in this instance only after the = sign has been placed
- [X] Highlight variables after eval functions
- [X] DBConnect Command highlighting
- [ ] SQL Highlighting in `dbxquery` with `query=`
- [X] Publish to VSCE Marketplace
- [ ] Change highlighting color to match Splunk search bar
  - Not sure if this is going to happen or not, as there is a need to stick to [Textmate Naming Conventions](https://macromates.com/manual/en/language_grammars#naming_conventions)
